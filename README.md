
# Google Store Chat App

This repository contains the Google Store chat app, created using the steps provided in the [Vertex AI Conversation Codelab](https://codelabs.developers.google.com/codelabs/vertex-ai-conversation#0). Click [https://ikinsey9188.github.io/](https://ikinsey9188.github.io/) to use.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [License](#license)

## Introduction

The Google Store chat app is a simple web-based application that integrates with Google's Dialogflow to provide a conversational experience for users. This app can be used to interact with a virtual assistant for the Google Store, allowing users to get help with various queries related to Google products.

## Features

- Integrates with Dialogflow for natural language processing.
- Customizable chat interface.
- Provides a seamless user experience for interacting with a virtual assistant.

## Setup and Installation

To set up and run this app, follow these steps:

1. **Clone the Repository:**
   \`\`\`bash
   git clone https://github.com/ikinsey9188/ikinsey9188.github.io.git
   cd ikinsey9188.github.io
   \`\`\`

2. **Rename HTML File (if needed):**
   Make sure the main HTML file is named \`index.html\`.

3. **Edit the HTML File:**
   Customize the \`index.html\` file with your Dialogflow project details:
   \`\`\`html
   <df-messenger
     project-id="main-voltage-431109-k1"
     agent-id="66561e3c-20fe-43ec-90c4-b72a5abaa203"
     language-code="en"
     max-query-length="-1">
     <df-messenger-chat-bubble
      chat-title="Google Store">
     </df-messenger-chat-bubble>
   </df-messenger>
   \`\`\`

4. **Deploy on GitHub Pages:**
   - Go to the repository settings.
   - Scroll down to the "GitHub Pages" section.
   - Ensure the source is set to the \`main\` branch and the root directory.
   - Save the changes.

## Usage

Visit the following URL to access the Google Store chat app:

[https://ikinsey9188.github.io/](https://ikinsey9188.github.io/)

## License

This project is licensed under the MIT License. See the LICENSE file for details.
