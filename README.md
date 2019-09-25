![Protocol oriented networking in swift](https://github.com/Yoloabdo/RebootingNetwork/blob/master/head.png)
# Rebooting network(Protocol oriented networking in swift)

## Swift Cairo
<I>This repo contains a code for the network layer and talk slides that was given in the first meetup for SwiftCairo in 9May, about the topic here's for those who requested it. </I>

## Medium blog about it: 
[First Blog: Protocol-Oriented Network in swift](https://medium.com/@yoloabdo/protocol-oriented-ios-network-layer-422575314cc2)
<br>
[second Blog:Protocol-Oriented Network in swift - 2](https://blog.usejournal.com/protocol-oriented-network-part-2-921fb89af3a1)


### For using PromiseKit
Check the blog post on: [Medium](https://medium.com/@yoloabdo/promising-network-layer-f13657d3032d)
<br>
Branch: [promises](https://github.com/Yoloabdo/RebootingNetwork/tree/promises)

### For using URLSession
Branch: [Native](https://github.com/Yoloabdo/RebootingNetwork/tree/Native)

### what's new in this branch?
#### ParseModel: Now your request will contain it's parsing model as well, for a better context. 
#### Here's an example: 

```
//Before:
UserRouter.login(email: "ali@ali.gmail.com", password: "test12345").send(SwiftCairoUser.self, then: userLoginResponse)

//After:
UserRouter<SwiftCairoUser>.login(email: "ali@ali.gmail.com", password: "test12345").send(then: userLoginResponse)
```

#### In case you don't know what's swiftCairo, and you're from Cairo, you should know more about it, twitter: [@swiftCairo](https://twitter.com/SwiftCairo)

</I>

# Thanks.
Abdoelrhman.
