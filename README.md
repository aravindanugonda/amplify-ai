# Amplify AI Example: Amplify AI

This is a NextJS application that is built like ChatGPT where you can see past conversations and resume conversations.

This example uses:

- Amplify Gen2
- NextJS App router
- Amplify UI components

### Prerequisites

- Node.js 18+ installed
- AWS account that has been set up for AWS Amplify and has access to the AWS Nova models in Amazon Bedrock

### Installation

1. Clone the repository and `cd` into the `amplify-ai` directory.
2. Install the dependencies with your favorite JavaScript package manager. For example, `npm install`.
3. Configure your AWS Amplify profile by running:
   ```bash
   npx ampx configure profile
   ```
4. Spin up a sandbox cloud backend by running:
   ```bash
   npx ampx sandbox
   ```
5. Start up NextJS locally by running:
   ```bash
   npm run dev
   ```
6. (Optional) If you need to delete the sandbox environment, run:
   ```bash
   npx ampx sandbox delete
   ```
   