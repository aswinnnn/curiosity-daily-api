## Curiosity Daily API

The reverse engineered API endpoints of the official Curiosity Android App, which was discontinued in 2020 since Discovery bought them and fucked it up.

This app offerred some real educational facts, on the daily, with their sources. They bought it and replaced it with a shitty podcast. Why is discovery ruining actual, educational content? Corporate envy and greed? No idea.

## Endpoints
The apk version used for decompiling was `v3.21.6`, the last known update to the app.

The URIs are categorised by the HTTP methods that can be (or used to be) utilized on them.

<details>
<summary>♾️ GET</summary>

|------|
|uri   |
|:-----|
| `/subscriptions/list` |
| `/trending/{type}/{period}` |
| `/paths/video/{id}` |
| `/content/{id}&view=app_3.0` |
| `/actions/followed/tag?view=app_3.0` |
| `/likes/{type}?view=app_3.0` |
| `/feeds/search/{content_type}?view=app_3.0` |
| `/feeds/search/terms?view=app_3.0` |
| `/feeds/daily/{date}?view=app_3.0` |
| `/feeds/discover?view=app_3.0` |
| `/{search_path}?view=app_3.0` |
| `/feeds/profile/{user_id}/actions/liked/content/{content_type}?view=app_3.0` |
| `/feeds/profile/{user_id}/actions/followed/tag/{namespace}?view=app_3.0` |
| `/tags/namespaces/subject?view=app_3.0` |
| `/feeds/tags/search/subject?view=app_3.0&order_by=name` |
| `/tags/namespaces/{namespace}/{name}?view=app_3.0` |
| `/feeds/tags/{tag_id}/content/{content_type}?view=app_3.0` |
| `/feeds/tags/{namespace}/{tag}?view=app_3.0` |
| `/feeds/tags/{tag_id}/tags/related?view=app_3.0` |
| `/content/types/topic/{id_or_slug}?view=app_3.0` |
| `/content/types/digest/{date}` |
| `/tags/namespaces/{namespace}/{name}/content/topic?view=app_3.0` |
| `/users/{id}/content/likes/{type}/count` |
| `/users/{id}/content/likes/topic?view=app_3.0` |
| `/users/{id}/content/likes/video?view=app_3.0` |
| `/content/types/video/{id_or_slug}?view=app_3.0` |
| `/tags/namespaces/{namespace}/{name}/content/video?view=app_3.0` |
| `/api_v2/auth/user` |
| `/api_v2/auth/logout` |
| `/facebook/sign-in` |
| `/google/sign-in` |
| `/twitter/sign-in` |

</details>

<details>
<summary>♾️ POST</summary>

|------|
|uri   |
|:-----|
| `/subscriptions/byid/{id}` |
| `/subscriptions/3.12/email/subscribe` |
| `/subscriptions/push/subscribe` |
| `/actions/followed/tag/{tag_id}?view=app_3.0` |
| `/likes/{type}/{id}?view=app_3.0` |
| `/paid_subscriptions/verify_receipt/android?view=app_3.0` |
| `/api_v2/auth/forgot-password` |
| `/api_v2/auth/login` |
| `/api_v2/auth/merge` |
| `/api_v2/auth/register` |
| `/facebook/sign-in` |
| `/google/sign-in` |
| `/twitter/sign-in` |
| `/api_v2/auth/nonreg` |

</details>

<details>
<summary>♾️ DELETE</summary>

|------|
|uri   |
|:-----|
| `/subscriptions/byid/{id}` |
| `/actions/followed/tag/{tag_id}?view=app_3.0` |
| `/likes/{type}/{id}?view=app_3.0` |

</details>

---

### Im open to archiving the content since most of it is removed. If you have found or know someone who has archived Curiosity articles or app content, open an issue so we can get in touch.