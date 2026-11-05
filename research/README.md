# Niche research for /ig-viral

Fill `captured.tsv`: one row per Reel, tab-separated.

- `median` = the account's middle view count across its last 12 Reels. This is the most important column.
- `hook` = the first spoken line, word for word.
- 6–12 accounts, about 6–12 Reels each (the top 3 and a few ordinary ones).

Then run `/ig-viral` and it ranks them by outlier multiple (views ÷ median).
