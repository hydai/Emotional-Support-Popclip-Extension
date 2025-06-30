# Emotional Support

Transform selected text into emotionally supportive messages filled with love and encouragement using an OpenAI compatible LLM service, such as [OpenAI](https://platform.openai.com/docs/overview).

It will show as a popup screen with the supportive message, and copy it to the clipboard.

You can press `shift` to paste it directly.

## Features

- **Robust Error Handling**: Comprehensive error handling for network issues, API errors, and invalid responses
- **Input Validation**: Validates text input and configuration parameters before processing
- **Automatic Retry**: Smart retry logic with exponential backoff for improved reliability
- **Secure Configuration**: Password-protected API key field for enhanced security
- **Customizable Prompts**: Configure your own emotional support instructions with tone placeholder support
- **URL Validation**: Ensures API endpoints are properly formatted before use

![LOGO](./Emotional-Support.popclipext/icon.svg)

### Configuration

#### API Endpoint

You can configure the API endpoint to send your emotional support requests.

* **OpenAI:** defaults to `https://api.openai.com/v1`

#### API Key

You need to provide an API key to use this extension. You can get it from [OpenAI API](https://platform.openai.com/account/api-keys).

#### Model Name

You can choose the model you want to use for generating supportive messages. The default model is `gpt-4o-mini`.

#### Support Tone

The default support tone is `Warm and Encouraging`. You can change it to other tones like `Compassionate`, `Gentle`, `Uplifting`, or any tone that suits your needs.

#### Support Prompt

You can customize the emotional support instructions by modifying the "Support Prompt" setting. The default prompt includes a `{tone}` placeholder that will be automatically replaced with your chosen tone. This allows you to fine-tune how the AI transforms your text into supportive messages.

## About

This is an extension for [PopClip](https://pilotmoon.com/popclip/).

### Requirements

Requires PopClip 2022.12 or later.

## Credit

### Icons

* Heart icon designed for emotional support and love
* Extension based on the original LLM Translation extension structure