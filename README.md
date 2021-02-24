# Instabot
Instagram bot implemented in Kotlin to perform all major operations supported by Instagram app.

## Features
- Like medias
- Comment medias
- Direct messages
- Watch stories
- Download medias
- Hashtag targeting
- Location targeting
- And more...

## Built with
[Kotlin](https://kotlinlang.org/) - A modern programming language for Android/JVM that makes developers happier.

[Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - For asynchronous programming

[Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/-flow/) - A cold asynchronous data stream that sequentially emits values and completes normally or with an exception.

[JsonPathLite](https://github.com/codeniko/JsonPathLite) - A lighter and more efficient implementation of JsonPath in Kotlin

## Installation

Add JitPack to your build.gradle file
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Add Gradle dependency to your build.gradle file
```
dependencies {
    implementation 'com.github.hadiyarajesh:insta-bot:2.0.0'
}
```

## Quick start
Initialize InstagramBot class with your username and password and call prepare method. Then call login method to login into instagram. (Prepare method must be called before login)

![start](https://user-images.githubusercontent.com/12107428/88461018-2189ab80-cebe-11ea-94cb-5ba368005fb5.png)


Now you can perform any operations of your choice. 
![main](https://user-images.githubusercontent.com/12107428/88461015-1f275180-cebe-11ea-9805-2be90a036ad8.png)

For more details, refer [BotTest](https://github.com/hadiarajesh/insta-bot/blob/master/src/main/kotlin/BotTest.kt) file.

## Samples
[You can find ready to use sample scripts here](https://github.com/hadiyarajesh/insta-bot/tree/master/src/main/kotlin/samples)

## Documentation
[You can find documentation here](https://hadiyarajesh.github.io/docs/index.html)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Terms and conditions
- You will NOT use this API for marketing purposes (spam, botting, harassment).
- We do NOT give support to anyone who wants to use this API to send spam or commit other crimes.
- We reserve the right to block any user of this repository that does not meet these conditions.

## Legal
This code is in no way affiliated with, authorized, maintained, sponsored or endorsed by Instagram, Facebook inc. or any of its affiliates or subsidiaries. This is an independent and unofficial API. Use it at your own risk.

## License
[MIT License](https://github.com/hadiyarajesh/insta-bot/blob/master/LICENSE)
