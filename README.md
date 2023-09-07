# feedly-helper

TODO: get all the unread entries under the "global.all" category
https://developer.feedly.com/v3/streams/#get-the-content-of-a-stream

```bash
curl -H "Authorization: Bearer YourAccessToken" https://cloud.feedly.com/v3/streams/user%2F00000000-0000-0000-0000-000000000000%2Fcategory%2Fglobal.all/contents\?unreadOnly\=true | jq
```

TODO: need both FE and BE code to handle authentication
https://developer.feedly.com/v3/auth/