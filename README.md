## WayWay AI Chat

#### ChatGPT Chat Interface with Next.js and Vercel

#### Overview

This project provides a simple ChatGPT chat interface built with Next.js and deployed to Vercel. Users can interact with the chatbot to have a text-based conversation on a variety of topics.

#### Prerequisites

Make sure you have the following installed before running the project:

- `Node.js`, including npm or yarn package manager
- A modern web browser such as Google Chrome or Edge

#### Installation

To install the project, run the following command in the project directory:

```
yarn install
```

#### Running the Application

To start the application, run the following command in the project directory:

```
npm run dev
```

This will start the development server on http://localhost:3000. Open the URL in your web browser to view the application.


#### Configuration

To use ChatGPT with the chatbot, you will need to set up an API key from OpenAI and add it to your project. You can do this by creating a new `.env.local` file in the root of your project and adding the following line:

```
OPENAI_API_KEY=your-api-key-here
```

#### Development

This project can be easily deployed to Vercel using the Vercel CLI or by connecting your Vercel account to your GitHub repository.

To deploy using the Vercel CLI, run the following commands:

```
npm install -g vercel
vercel login
vercel
```

Follow the prompts to log in and deploy the project.

#### Forked From
This project is derived from the [ChatGPT-Next-Web](https://github.com/Yidadaa/ChatGPT-Next-Web) by [Yidadaa](https://github.com/Yidadaa). Any questions or concerns related to the original work should be directed to Original Author.

I would like to thank [Yidadaa](https://github.com/Yidadaa) for their hard work and for contributing to the open-source community.

[Anti 996 License](https://github.com/kattgu7/Anti-996-License/blob/master/LICENSE_CN_EN)
