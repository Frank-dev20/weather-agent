# HNG 13 STAGE 3 BACKEND TASK

# Weather Reporter Agent
## Overview
An intelligent weather report Agent built with Mastra and TypeScript
This agent helps users become aware of weather situation in select in their favorite cities.

## Features
- Powered by Mastra – Built using Mastra AI Framework with @mastra/core, @mastra/memory, and @mastra/libsql.

## Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/Frank-dev20/weather-agent.git
cd weather-ai
2️⃣ Install dependencies
npm install
3️⃣ Create a .env file

GOOGLE_GENERATIVE_AI_API_KEY=<your_API_Key>
4️⃣ Run the app in development
`npm run dev`
5️⃣ Build and serve for production
`npm run build`


## How It Works
The Weather Report Agent listens to user prompts and identifies their goals.

It uses the weather-tool to create weather report

The agent saves user progress and past conversations using Mastra Memory with a LibSQL store.

The agent responds in a formal tone.

## Live demo
[Weather Report Agent](https://telex.im/telex-ai-intergration/home/colleagues/019a3bc5-a374-7671-8abb-69322c656994/019a3bc5-6adf-766b-a68b-45ee9ab7ade2)
