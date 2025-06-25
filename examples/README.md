# Example Workflows

This directory contains example ComfyUI workflows demonstrating how to use the ASCII Generator node.

## Basic Workflow (`basic_workflow.json`)

A simple workflow that demonstrates the core functionality:

1. **Load Image** - Load any image file
2. **ASCII Generator** - Convert to ASCII art
3. **Save Image** - Save the ASCII art image
4. **Show Text** - Display the raw ASCII text

### Parameters Used:
- **Columns**: 100 (good balance of detail and performance)
- **Language**: simple (basic ASCII characters)
- **Background**: black (classic ASCII art style)
- **Font Size**: 12 (readable output)

## Usage Instructions

1. Open ComfyUI
2. Load the workflow: `File > Load > basic_workflow.json`
3. Replace the input image with your own
4. Adjust parameters as needed:
   - Increase `num_cols` for more detail (slower)
   - Try different `language` options for varied styles
   - Switch `background` for different aesthetics
5. Queue the workflow

## Parameter Recommendations

### For Portraits:
- **Columns**: 80-120
- **Language**: complex or simple
- **Background**: black

### For Landscapes:
- **Columns**: 100-150
- **Language**: simple or english
- **Background**: black or white

### For Text/Documents:
- **Columns**: 60-100
- **Language**: simple
- **Background**: white

### For Artistic Effects:
- **Columns**: 50-200
- **Language**: chinese, japanese, or korean
- **Background**: black

## Tips

1. **Performance**: Lower column counts process faster
2. **Detail**: Higher column counts preserve more detail
3. **Style**: Different character sets create unique aesthetics
4. **Readability**: Simple character sets are more readable
5. **Contrast**: Black background works well for most images
