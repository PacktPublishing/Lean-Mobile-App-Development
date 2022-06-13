# Lean Mobile App Development
This is the code repository for [Lean Mobile App Development](https://www.packtpub.com/application-development/lean-mobile-app-development?utm_source=github&utm_medium=repository&utm_campaign=9781786467041), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Lean is the ultimate methodology for creating a startup that succeeds. Sounds great from a theoretical point of view, but what does that mean for you as an a technical co-founder or mobile developer?

By applying the Lean Start-up methodology to your mobile App development, it will become so much easier to build apps that take Google Play or the App Store by storm. This book shows you how to bring together smarter business processes with technical know-how.

It makes no sense to develop a brilliant app for six months or longer only to find out later that nobody is interested in it. Build a Minimum Viable Product (MVP) first. Validate your
hypotheses early and often. Discover effective product development strategies that let you put Facebook's famous axiom "move fast and break things" into practice.


## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
func refresh (sender: AnyObject!) {
...
 let cngQuery = client.queryDataset("wwmu-gmzc")
 cngQuery.orderAscending("title").get { res in
 switch res {
 case .Dataset (let data):
 self.data = data
...
 }
 }
Data (XML, JSON or otherwise) is shown as:
<key>UberClientID</key>
 <string>your uber client id</string>
 <key>UberCallbackURI</key>
 <string></string>
 <key>LSApplicationQueriesSchemes</key>
 <array>
 <string>uber</string>
 </array>
```

In the first place, this book is to inspire technical-oriented cofounders of start-ups and
existing business technical leaders seeking to integrate lead into their development
operations. In addition, there are some Android and iOS code samples that we discuss to
explain some of the concepts. Although the concept is more important than the code, you
can try the sample for yourself. Where applicable, you can find a link to the Github
repository, containing the code.
For the Android examples, you need to have Android Studio 3 (or above) and the Android
SDKs installed on your computer. Android Studio is available as a free download for
Windows, OSX, and other operating systems. The Android examples are written in Kotlin
and Java.
The samples for iOS requires xCode 9 or above (xCode is available on OSX only and you
need to have a paid Apple developer's account). The iOS examples are written in Swift 4.
Some examples require a (free) registration at Firebase, Facebook, Fabric, or other services.

## Related Products
* [Professional Oracle Mobile](https://www.packtpub.com/virtualization-and-cloud/professional-oracle-mobile?utm_source=github&utm_medium=repository&utm_campaign=9781788830959)

* [Mastering Machine Learning Algorithms](https://www.packtpub.com/big-data-and-business-intelligence/mastering-machine-learning-algorithms?utm_source=github&utm_medium=repository&utm_campaign=9781788621113)

* [Beginning Reinforcement Learning](https://www.packtpub.com/big-data-and-business-intelligence/beginning-reinforcement-learning?utm_source=github&utm_medium=repository&utm_campaign=9781788834247)

