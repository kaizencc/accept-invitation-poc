# accept-invitation-poc

> A GitHub App built with [Probot](https://github.com/probot/probot) that proof of concept for invite accepting app

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t accept-invitation-poc .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> accept-invitation-poc
```

## Contributing

If you have suggestions for how accept-invitation-poc could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2022 Kaizen Conroy
