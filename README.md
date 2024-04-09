# PDF-CHAT AI

An AI-powered PDF chat built with Next.js 13, Vercel's AI SDK, Langchain, and PineconeDB

## 👩‍🚀 Description

Built with:
- ✅ Next.js 13
- ✅ Vercel's AI SDK
- ✅ Langchain TypeScript integration
- ✅ PineconeDB as the knowledge store

## 🗃️ Pre-requisites
- Create a free account and get an OPEN_AI key from platform.openai.com
- Create a free account and get access to PineconeDB
- And populate your `.env` file with the required information.

## Github Link
- https://github.com/woruz/langchain


## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command               | Action                                          |
| :-------------------- | :-----------------------------------------------|
| `npm install`         | Installs dependencies                           |
| `npm run prepare:data`| Splits your PDF file under the /docs folder into chunks, embeds them, uploads them to Pinecone|
| `npm run dev`         | Starts the local dev server at `localhost:3000` |
