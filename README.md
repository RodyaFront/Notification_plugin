# Notification plugin

## Plugin for displaying messages in the layout

First - create instance
```
const message = new Message() // Create instance

message.notification(options) // Push notification
```
or in Vue
```
Vue.$message = new Message()
// next in vue component
this.$message.notification(options)
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
