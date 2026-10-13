# Dell Laptop Sentiment Dashboard

A public, data-driven dashboard tracking what people are saying about Dell laptops across forums and social platforms — sentiment analysis split by hardware vs. software, per-model complaint/praise themes, and competitor comparisons.

🔗 **Live site:** https://jameslee2324.github.io/dell-sentiment-dashboard/

## How it works

- `index.html` — page layout and rendering (rarely changes)
- `data.json` — all dashboard content: sentiment data, model tabs, charts, comment-stance tallies, competitor analysis

The page loads `data.json` when it opens. Daily updates replace only `data.json`; the layout stays untouched.

## Data

- **Update cadence:** daily (~12:00 CST, Asia/Taipei)
- **Window:** rolling six months of posts and reviews
- **Sources:** tech forums (NotebookTalk, Notebookcheck forum, Tom's Hardware, Linus Tech Tips), Reddit, Instagram, X/Twitter via web search, news and review outlets
- Sentiment is coded per model as hardware/software × complaints/praise. Instagram comment stances are measured tallies from real comment reads, not estimates.

## Disclaimer

Independent sentiment-tracking project. Data is aggregated from public sources; discussion volume reflects online chatter, not sales or market share.
