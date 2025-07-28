# Gmail Email Fetcher with Google API

This project fetches and decodes emails from a user's Gmail account using the Gmail API. It is implemented in a Jupyter Notebook and extracts plain text from emails.

## Features

- Connects to Gmail via OAuth2
- Retrieves and decodes email bodies
- Outputs emails (presumably in Markdown format)

## Prerequisites

- Python 3.x
- Google Cloud Project with Gmail API enabled
- `credentials.json` file downloaded from Google Cloud Console

## Installation

Install dependencies via pip:

```bash
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
```

## Usage

1. Place your `credentials.json` file in the working directory.
2. Run the Jupyter Notebook.
3. Authorize access through the Google authentication flow.
4. Extracted emails will be saved in the `emails_md` directory.

## Notes

- This project uses read-only access to Gmail.
- All decoded email content is stored locally.

