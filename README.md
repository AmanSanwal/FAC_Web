# FAC_Web

# Install & Run commands:
1. Clone the repository
2. cd FAC_Web
3. npm i
4. (if no errors move ahead) npm i --legacy-peer-deps
5. npm run dev

To view the components storybook:

```bash
npm run storybook
```

To create a production build:

```bash
npm run build
```

## Deployment

I've set up the site using AWS for hosting and serverless functions. You'll need an AWS account and the AWS CLI installed in order to deploy.

Deploy the site to s3:

```bash
npm run deploy
```

Deploy serverless functions:

```bash
cd functions
```

```bash
npm run deploy:api
```

