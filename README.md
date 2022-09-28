# URI-encoding
### Amazon Cloudfront JS
### [Lambda@Edge makes the internet fast](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/lambda-at-the-edge.html), 
#### thanks Jeff.

I was looking through https://futbin.com to [see where their data comes from](https://www.futbin.com/23/player/62/pele), turns out it's a JQueried CDN (content delivery network), thus effectively inaccessible. I was combing through 25ish sources in the page, most of which were ads to find the data source, as this particular set of data is demanded, closed source and highly speculated upon.

There is one semi-paywalled API: https://futdb.app that was started in 2020, and Futbin is much older than that. How they get the data is unbeknownst to me.

### ----->[The JS file](https://github.com/dkalnz/URI-encoding/blob/main/script-donotrun.js)<-----
looks like some basic encryption, but turns out it's just an encoded fetch request for Lambda@Edge that gets routed through a Tor-like network to make everyones internet faster.
I still do not understand the JS structure underneath, but someone probably got paid a lot for it.
I've noticed 'loaders' have similar types of encoding, some not so cryptic, but most ads are placed into HTML, and the script that loaded it is gone, leaving no DOM handlers on the page.

[Read about UTF-8 encoding here](https://www.urlencoder.org)
10,000 lines of code vs a URI, for the purposes of 'streamlining'.
I even tried to fold it until I realized my scrollbar had barely moved:

![image](https://user-images.githubusercontent.com/88372572/192675495-62271426-0dae-4838-862a-9a3938b51fc7.png)




