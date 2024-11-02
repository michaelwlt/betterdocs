---
Title: Limitations
type: docs
---
## Daily Message Limits for the entire platform
- 1,500 messages per day per flash-model
  - 1,500 requests for Gemini Flash 1.5
  - 1,500 requests for Gemini Flash 1.5-8b
- 50 messages per day per pro-model
- Limits reset at midnight UTC

## Rate Limiting
- Maximum of 15 messages per minute per flash-model
- Maximum of 2 messages per minute per pro-model
- Exceeding this limit will result in a temporary block

## File Handling
- Maximum file upload size: 3MB per file
  - Consider compressing images before upload
- Maximum files per message: 12 files
- For complex documents containing more than just text, using images is recommended over PDF files
- Supported file formats: PDF, PNG, JPEG, JPG
- Images should be clear and legible for best results

## Model Constraints
- Google models have a context window of 1M tokens
  - Approximately 750,000 English words
- Response generation typically takes 2-10 seconds
  - For best performance, break down large documents into smaller chunks
- Multi-language support available
