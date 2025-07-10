# lean-canvas-generator
Creates a lean canvas from an idea statement using Snowflake. Will use an LLM model from Snowflake Cortex to generate all the components and generate a powerpoint presentation using the provided template.

### Steps
1. Import Notebook into Snowflake
2. Upload the blank template PPTX file into the notebook workspace using the "+" icon
3. Modify the notebook to point to an existing table of customer data or use the provided demo examples
4. Run the notebook and download the resulting PPT

### What is a Lean Canvas
[Here](https://medium.com/@steve_mullen/an-introduction-to-lean-canvas-5c17c469d3e0) is a great explanation of what a lean canvas is and how product teams could use it.

### Visuals

Image of Blank Canvas
![Blank Lean Canvas template](/assets/blank_canvas.png)

Image of Completed Canvas
![Completed Lean Canvas template](/assets/completed_canvas.png)
