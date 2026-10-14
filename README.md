# Reserve Trade Planner

This is a static, browser-only site. It stores your selected reserve days and pasted pool snapshots in the browser's local storage; it does not send the data anywhere.

## Publish with GitHub Pages

1. Create an empty GitHub repository (for example, `reserve-trade-planner`).
2. Upload the three files in this folder (`index.html`, `styles.css`, and `app.js`) to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main`, select `/ (root)`, and save.
5. GitHub will show the site URL after it finishes deploying.

## How to use it

1. Choose **This month** or **Next month**.
2. Choose **Edit reserve days**, then click each day you are assigned reserve.
3. Paste the reserve-pool table and select **Use this pool**. Partial-month tables are supported.
4. Choose **Plan a trade** and click a blue reserve day. Eligible target days appear green when their End Result is strictly more negative.
5. For days you want protected, choose **Pick days off** and click them. If a protected day is also a reserve day, the helper suggests the toughest eligible replacement date.

Always verify final eligibility in the company system before submitting a trade.
