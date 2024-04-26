# Adapting the Script for Russian PDF Parsing

This document outlines the steps for modifying a Google Apps Script provided by [Aaituov](https://github.com/Aaituov) to effectively parse and extract information from Russian PDF documents.

## Language Setting
**No changes required:** Gemini, the language model used by the script, should automatically detect and process Russian text without needing specific language settings.

## Prompt Engineering
1. **Translate instructions:** The `q` variable within the script contains the instructions for Gemini. Translate these instructions into Russian to ensure accurate understanding and processing.

## Data Validation
1. **Running the scritp:** In oreder to run the script that you can find in this repository you need to uncert your own API Key into the `Sample.gs` file.
2. **Review the output:** After running the script, carefully examine the generated JSON object to ensure it accurately reflects the extracted information from the PDF (see attached file).
3. **Refine prompts:** If the output is inaccurate or incomplete, adjust the prompts within the `q` variable to provide clearer guidance for Gemini's parsing.

## Additional Considerations
- **Font and formatting:** Complex fonts or formatting within the PDF might impact text extraction accuracy. Consider pre-processing the PDF to improve clarity before parsing.
- **Table structures:** Varying table layouts in different PDFs might require additional script logic to handle diverse structures effectively.

