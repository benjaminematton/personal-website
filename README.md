# personal-website

Source for my personal site. Single static `index.html` — no build step.

## Local preview

```sh
python3 -m http.server 8000
# or: npx serve .
```

Then open `http://localhost:8000`.

## Deploy

### Vercel

```sh
npx vercel        # preview
npx vercel --prod # production
```

Or drag the project folder onto [vercel.com/new](https://vercel.com/new). Auto-detects as static.

### Netlify

```sh
npx netlify deploy            # preview
npx netlify deploy --prod     # production
```

Or drag the project folder onto [app.netlify.com/drop](https://app.netlify.com/drop).

## Images

All images live in [`images/`](images/). Swap files in place using these names:

| File | What it is |
|---|---|
| `ben-headshot.jpg` | Headshot |
| `screen-home.webp` | VaBene — upcoming events |
| `screen-itinerary.webp` | VaBene — day-by-day itinerary |
| `screen-expenses.webp` | VaBene — Stripe Connect payment splitting |
| `screen-chat.webp` | VaBene — group chat with poll |
| `proj-beastchain.gif` | BeastChain animated terminal demo |
| `proj-election.webp` | oath_score Streamlit dashboard |
| `proj-agents.webp` | vabene-agents Telegram lead card |

## Links

- LinkedIn: [www.linkedin.com/in/benmatton](https://www.linkedin.com/in/benmatton)
- GitHub: [github.com/benjaminematton](https://github.com/benjaminematton)
