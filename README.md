# Push Notification Test

# Run

## Notix

```shell
npx http-server -p 3000 -c-1 notix
```

## One Signal

```shell
npx http-server -p 3000 -c-1 onesignal
```

Use ngrok to run behind HTTPS (requires [free] access token)
```shell
ngrok http 3000
```

# Notes

You might need to set-up your own Notix and One Signal accounts and apps for this to work. Not sure if One Signal will work if the domain doesn't match.
