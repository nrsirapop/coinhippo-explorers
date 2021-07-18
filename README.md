# CoinHippo - Explorers

## Explorers URL
[https://explorers.coinhippo.io](https://explorers.coinhippo.io)

## Data provider / APIs
All data presented on the explorers are retrieved from [Covalent API](https://www.covalenthq.com/docs/api/)

## Technology stacks
This project is built as a serverless system, getting inspiration from the [Covalent AWS Serverless](https://github.com/nrsirapop/covalent-aws-serverless) project.

The technologies used include
- [React.js](https://reactjs.org) is used for building the user interface of the explorers.
- [Covalent AWS Serverless](https://github.com/nrsirapop/covalent-aws-serverless) is used as a bridge of requesting data from Covalent's endpoints with our serverless setup.
- [AWS Lambda](https://aws.amazon.com/lambda) is used for setting up a lambda function to retrieve the data from [Covalent API](https://www.covalenthq.com/docs/api/).
- [AWS S3](https://aws.amazon.com/s3) service is used for hosting the explorers as a static website.

The setup instructions can be found in the [README.md](https://github.com/nrsirapop/covalent-aws-serverless#readme) of the Covalent AWS Serverless project

## Follow us
- [Website](https://coinhippo.io)
- [Twitter](https://twitter.com/coinhippoHQ)
- [Telegram](https://t.me/CoinHippoChannel)