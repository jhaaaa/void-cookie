# void-cookie

Message voidcookie.eth for your nihilistic fortune.

A nihilist fortune cookie agent on XMTP. Send it any message and it replies with a darkly funny fortune — existential dread delivered with a wink, not a sigh.

Built with the [XMTP Agent SDK](https://docs.xmtp.org/agents/build-agents/connect-to-xmtp) and Claude.

## Setup

```bash
npm install
cp .env.example .env
```

Generate your XMTP keys:

```bash
node -e "console.log('XMTP_WALLET_KEY=0x' + require('crypto').randomBytes(32).toString('hex'))"
node -e "console.log('XMTP_DB_ENCRYPTION_KEY=0x' + require('crypto').randomBytes(32).toString('hex'))"
```

Add your keys and Anthropic API key to `.env`.

## Run

```bash
npm start
```

## Deploy

See the [deployment guide](https://docs.xmtp.org/agents/build-agents/connect-to-xmtp#step-6-deploy-to-railway) in the XMTP docs.
