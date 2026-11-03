# BuildLikeNew Pulse

Daily NewsBreak traffic dashboard for BuildLikeNew (impressions, views, native views, followers, shares, likes, comments, engagement, view rate).

- Live: https://vivekattri05.github.io/buildlikenew-pulse/
- Data: the "Daily" tab of the Google Sheet, read through its published CSV link (set in `config.js`). If the Sheet can't be reached, the page uses `data.csv` in this repo.
- The page re-reads the Sheet every 5 minutes and when the tab comes back into view. Google can take up to ~5 minutes to refresh a published CSV after an edit.
- Sheet columns (row 1, in this order): Date, Impressions, Views, Native Views, Followers, Shares, Likes, Comments, Total Monthly page views.
- View settings (period, compare, metric) are kept in the link, so a copied link opens the same view.
