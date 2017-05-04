# Simple slack notifier as golang package

## Create new connection

```go
slackConn := slack.New("https://hooks.slack.com/services/TTTTTTTT/BBBBBBBB/bi43fdi347bdi3b4bf")

// Send notification
slackConn.Notify("username", "Hello, man")
```

## List all methods

* slack.New(webHook) - initializes configuration
* slack.Name(name) - to set notifier name
* slack.Face(face) - to set notifier face from Emoji
* slack.Notify(username, message) - to set notification