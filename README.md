<h1><img align="left" height="157" style="background:none; border:none; box-shadow:none;" src="Me.png">Software Developer - About Me</h1>
In my spare time I like to create video games, spend time with my wife, read books, roller blade on trails, and socialize with friends & family.

I'm an ever learning programmer. I've found I can do anything I set my mind to. As would be expected, online resources help out a lot! Often when I write code, hours go by unnoticed.

# Skills:
Unity:
Unity, C#, Fish-Networking, Git, Input System, MonoBehaviour, Components, ScriptableObject, Coroutines

Android:
Android Studio, Visual Studio, GitHub, Kotlin, Java, C#, Python, Java Spring, REST APIs, Mvvm, Room, Retrofit, Debugging, RxJava, Dagger, GraphQL, ApolloAndroid, NavComponent, Picasso, Jetpack Compose

# Contact
- LinkedIn: https://www.linkedin.com/in/justinbgent/
- GitHub: https://github.com/justinbgent

# Projects:
## Astrodawn - Unity
[![Astrodawn](https://github.com/justinbgent/justinbgent.github.io/assets/50253022/5c6c8577-9fba-4d77-bd22-05723dad25f6)](https://www.youtube.com/watch?v=bsVMCfSxPXY "Astrodawn")

As seen in the video, Astrodawn is a fast paced online multiplayer video game. Astrodawn, built in Unity and shared with my brother Kevin, is a ton of fun to create. I am the one programming the game mechanics and Kevin does all of the sounds, models, animations, and shaders. [Here's](http://www.kevingent.com/p_si.html) Kevin's portfolio showing some more in an earlier build!

Multiplayer UDP oriented code, used in Astrodawn, may be the most challenging thing I've ever worked on but so rewarding when I found I successfully created smooth fast paced networked gameplay. I'm still celebrating the acheivement. It's taken many many tries over the years and quite some time to get it working. It's something I was self taught via hours of research and working through my own custom solutions. I was aided by online resources that pointed me to the right principles for accomplishing it successfully.

I did all the network code using [Fish-Networking](https://fish-networking.gitbook.io/docs/) built on top of [LiteNetLib](https://github.com/RevenantX/LiteNetLib), a UDP library. I first used Fish-Net's version 1 client-side prediction to create networked gameplay. Upon finding jitter in our gameplay, we decided their solution wouldn't cut it. I quickly got to work creating a custom solution handling user inputs using the unreliable channel in RPCs and with time, I got it working.

In regards to multiplayer, I've learned so much. Here's a few things:
- How to handle UDP's unarrived, out of order, and sometimes late packets.
- Ways to account for varying user round trip times, or ping. 
- Client-side prediction and interpolation techniques to create smooth gameplay.
- How much fun it is to have a successful solution. Quality plays a big role here.

## Rekor Blue (Owned by Rekor Systems) - Android Studio
[This](https://play.google.com/store/apps/details?id=ai.rekor.rekorblue) is the project I've worked on most at Rekor. Here I learned much adding features and fixing unforseen bugs. I worked a lot with CameraX fine tuning configurations and sending frames to the License Plate Recognition library we interacted with through the JNI framework. I helped structure the Room database for saving plate reads, hot lists, and other data pieces. To be brief here are a few other contributions, REST API interactions for signing in, uploading plate reads, downloading hot lists, downloading and extracting zip configuration files, and creating application settings among other things.

## Plate Reader (Owned by Rekor Systems) - Android Studio
Plate Reader was both our playground application where we tested out many features before implementing them in Blue and a place where we created a "base library" module for general use in company Android applications. We generated a aar file from the base library and implemented it in Blue. To name a few things our base library provided, date string manipulation, frequently used methods like fragment navigation, and base classes like a base view model. I periodically would add or update the base library module for use in other apps.

## Community Calendar - Android Studio
You can find the repository [here](https://github.com/Lambda-School-Labs/community-calendar-android). The goal of the app is to help community members conveniently find upcoming events. This was a remote project done with a team that had Android, Web, and iOS counterparts. I was on the Android team and used many libraries on the project. I primarily developed the functionality of the home, event details, and search screens.
Android libraries: Apollo-Android, NavComponent, Picasso, OkHttp, Koin, RxJava2, Room, Moshi

<img src="MainScreen.png" width = "235"/> <img src="Campfire.png" width = "235"/> <img src="Search.png" width = "235"/> <img src="Results.png" width = "235"/>

## Game Engine - MonoGame
This is a old hobby project. I learned a lot about game dev working on this, it was quite fun. I've built collision boxes for sprites I can move around the screen. It handles rectangle, circle, and triangle collisions in which I admit each took me some time to figure out. Lots of algebra and geometry. I am currently working on a map editor for it. Github says it has reached 12,500+ lines of code via commits.

## Snake 1v1 - MonoGame
You can find the repository [here](https://github.com/justinbgent/FirstGame). As titled this is a Snake 1v1 game I made using C# in MonoGame, a library made to work like Microsoft’s XNA. I like to play with it every now and then. If you download it you may run into multiple files named "CalebsIdea". This is because my nephew Caleb came up with the idea and I figured I'd make it!

<img src="Snake1v1.png" />
