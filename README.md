# Page Summarizer (Modified Version)

## Notice

This project is a modified version of [sysread/page-summarizer](https://github.com/sysread/page-summarizer) and continues to follow the original [MIT License](./LICENSE).

### Key Modifications

- Added [describe your changes here]
- Improved [describe improvements]
- Fixed [describe bug fixes]

---

## Original README

Page Summarizer is a Chrome extension that utilizes OpenAI's chat completions
API to summarize text from a web page. Just highlight the text you want to
summarize, click the extension icon, and get a concise summary.

## Features

- Summarize the content of any web page
- Summarize the contents of selected text
- Fill in text with GPT
- Customize instructions to get the information you want
- Add persistent custom instructions for all summaries
- Uses the OpenAI conversations API

![Summarize a web page](./docs/summarize-page.gif)
![Summarize selected text](./docs/summarize-selection.gif)

## Installation

### Prerequisites

You'll need to have Google Chrome or a Chromium-based browser installed. This
_might_ work on Firefox, but I took exactly zero minutes ensuring my API calls
were cross platform. It does work on Opera, though.

- Sign up for an [OpenAI API account](https://platform.openai.com/signup)
- Create an [API key](https://platform.openai.com/api-keys)

### Installation from the Chrome Web Store

Go [here](https://chromewebstore.google.com/detail/page-summarizer/mcebcgkikhcjigekcekkicnppoldnikf).

### Installation from latest release

1. Go to the [Releases](https://github.com/sysread/page-summarizer/releases) page of this repository.
2. Download the latest `chrome-extension.zip` or `firefox-extension.zip` based on your browser.
3. Unzip the downloaded ZIP file.
4. Open Google Chrome and navigate to `chrome://extensions/`.
5. Enable "Developer mode" in the top-right corner.
6. Click "Load unpacked" and select the directory where you unzipped the downloaded ZIP file.
7. The extension icon should now appear in your Chrome toolbar.
8. Right-click the extension icon and choose "Options", then enter your OpenAI API key and preferred model.

### Manual Installation from repo

1. Clone this repository to your local machine:

```bash
   git clone https://github.com/sysread/page-summarizer.git
