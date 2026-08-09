# proxy-tg-feed

Public mirror of MTProto proxies posted in the `ProxyMTProto` public Telegram
channel. The data here is not secret — it's already posted openly on a public
channel; this repo just re-publishes it somewhere reachable over
`api.github.com`, for networks where `t.me` itself is blocked.

`proxies.json` is refreshed automatically every 2 days by
`.github/workflows/refresh.yml` (also runnable on demand via
"Run workflow"). Consumed by the [Proxy TG](https://github.com/Ghoster01172726/instagram-content-hive)
Android app as a fallback proxy source when a live fetch to `t.me` fails.
