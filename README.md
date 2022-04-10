# Notification plugin

## Plugin for displaying messages in the layout

```
const message = new Message() // Create instance

message.notification(options) // Push notification
```

Options example

```
const options = {
  title: String,
  text: String, 
  type String // default, access, warning, error
  duration: Number // 0 - infinity, 2000 - 2 seconds
}
```
