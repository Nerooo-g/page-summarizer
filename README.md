# Page Summarizer (Enhanced Edition)

## Notice

This project is an enhanced version of [sysread/page-summarizer](https://github.com/sysread/page-summarizer) and remains under the original [MIT License](./LICENSE).

### Key Enhancements

Building on the original, this version introduces several significant improvements:

- **Expanded Model Support:**  
  The original version was limited to fetching only GPT-4o, GPT-4o-mini, o3-mini, and o4-mini models. This update removes those restrictions, enabling access to a wider range of state-of-the-art language models. You can further tailor supported models by modifying `gpt.js` to suit your needs.

- **Modern UI Redesign:**  
  Enjoy a completely refreshed, modern interface with vibrant color schemes—delivering enhanced usability and a visually appealing user experience.

- **Automatic Dark Mode:**  
  The interface now dynamically adapts to your system’s light or dark mode settings, ensuring a seamless and consistent appearance.

- **Instant Translation:**  
  Effortlessly translate your generated summaries between English and Chinese with a single click, right after summarization.

Feel free to further customize or extend these features to best fit your requirements!

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
