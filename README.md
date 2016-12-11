# ParseDemo
This project build from sources of this tutorial: http://www.appcoda.com/login-signup-parse-swift/
but I could not integrate Parse framework, that's way I merge this project with another one (more spesifice http://www.kaleidosblog.com/how-to-create-a-login-screen-page-in-swift-3-authenticate-an-user-and-keep-the-session-active)


## References

1. Adding internet access: http://stackoverflow.com/questions/31254725/transport-security-has-blocked-a-cleartext-http/33712228?stw=2#33712228

2. Go to another view programmatically http://stackoverflow.com/a/27562874/1746258
```
let storyBoard : UIStoryboard = UIStoryboard(name: "Main", bundle:nil)

let nextViewController = storyBoard.instantiateViewControllerWithIdentifier("nextView") as NextViewController // here 'nextView' is Storyboard ID of view which we want to open 
self.presentViewController(nextViewController, animated:true, completion:nil)
```
