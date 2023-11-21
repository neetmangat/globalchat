# GlobalChat

## Production

- Deployment Link: https://globalchat-nm.vercel.app
- GitHub Repo Link: https://github.com/neetmangat/globalchat
- YouTube Build Link: https://www.youtube.com/watch?v=OOUsvDOKlGs

## Development

1. Clone the repository and install dependencies

```bash
git clone https://github.com/neetmangat/globalchat.git globalchat && cd globalchat && npm install
```

2. Start new Firebase Project, Get ProjectID, Client Email, Private Key, Google Client ID, Google Client Secret

3. Register Stripe account and get Secret Key and Product Price ID

4. Add the server environment variables

```bash
cp .env.example .env.local
```

5. Run the development server:

```bash
yarn run dev
```

6. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
