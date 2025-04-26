# Action Discord Message

Send message inclues commit message, commiter, commit hash and branch

```yaml
inputs:
  webhook_url:
    description: "Discord Webhook URL"
    required: true
  short_sha:
    description: "Short SHA"
    required: true
  image_name:
    description: "Image name"
    required: true
```
