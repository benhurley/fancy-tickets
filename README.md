[![Netlify Status](https://api.netlify.com/api/v1/badges/a81204a5-d6c4-4a7f-807b-3fcecda118ee/deploy-status)](https://app.netlify.com/sites/prettytickets/deploys)

# Pretty Tickets™

## Elevate Your Electronic Tickets

Transform your electronic ticket receipt into a beautiful online ticket that's perfect for gifting and sharing.

![Homepage](./public/screenshot.png)

## Tools

1. [OpenAI](https://openai.com) Chat Completions API to generate gift message
2. [TinyURL](https://tinyurl.com) API to create short links to share

## Architecture

- React create-react-app (using Typescript and Tailwind CSS)
- Netlify serverless backend (functions)
- Netlify hosting

## Getting Started

1. [Download Netlify CLI](https://docs.netlify.com/cli/get-started/)

2. Install Packages:

    ```bash
    npm i
    ```

3. Run website and serverless backend locally (will be hosted on port 8888):

    ```bash
    netlify dev
    ```
