# 100 Days Of Code - Log

## Day 0.0 - 15. July 2020

I am starting with a couple of zero days, since I go on vacation in August and the notebook doesn't come along ;) So the real challenge will start end of August.

### Preparation for the #100DaysOfCode challenge. 

The challenge includes several projects:
- todo app (flutter firebase & sqlite)
- Work Life Balance app (flutter moor)
- simple flutter timetracking app
- ESCR (motivation flutter app)

> Thats quite a scope, but X preparation days plus 100 days means 150 to 300 hours... We'll see what's possible.

### Additional tasks:
- Design
- UX
- Plattform specific behaviors and guidelines
- Setup Apple Store
- Data Privacy
- Internationalization

#### While preparing my flutter sdk, playground and projects, i found a Flutter Version Management package
I'll have a ['spike'](https://en.wikipedia.org/wiki/Spike_(software_development)) on this later in the 100 days of flutter coding.

https://pub.dev/packages/fvm  
https://github.com/flutter/flutter/wiki/Flutter-build-release-channels  
https://flutter.dev/docs/development/tools/sdk/releases  

#### Some inspirations 
[Flutter UI Tutorial | Login and Signup Page Design & Animation - day 23](https://www.youtube.com/watch?v=Hq7Wj6DshNs&list=PLf-j0Hs0PF3u5WSVX_x3GzU0sAP6oIwA5&index=23)  
https://github.com/erluxman/awesomefluttertips  
https://www.hackingwithswift.com/100/swiftui  
https://mobile.twitter.com/search?q=100DaysOfCode%20flutter&src=typed_query

#### Today's Progress:
Started project txtty with desktop macos enabled. Installed [supercharged](http://pub.dev/packages/) which only works iOS, Android and web (but who knows... until userstory 'parse_chat_messages', this could change). Added simple BottomNavigationBar with 3 empty views (dashboard, chats, settings).

#### Thoughts:
Thought i could use a shortcut with [settings_ui](https://pub.dev/packages/settings_ui) - but this package supports only iOS and Android.

> The example of settings_ui uses [device_preview](https://pub.dev/packages/device_preview) - **that's a todo for the userstory 'flutter and responsive layout'**.

In my ESCR project i use the [shared_preferences_settings](https://pub.dev/packages/shared_preferences_settings) package, wich supports web. But i think there was a textColor issue with my dark theme. I'll check this later, when i am working on that project.

> ToFigureOut - How much additional time will it cost, to log the 100 days?

#### Link to work ...

## Day 0.1 - 16. July 2020

#### Today's Progress:
Lost in state management. Cloned and tested so many different flutter architecture examples. Read and watched countless tutorials. I am confused.

#### Links:
https://flutter.dev/docs/development/data-and-backend/state-mgmt/options  
https://flutter.dev/docs/development/data-and-backend/state-mgmt/simple  
https://github.com/rrousselGit/provider  
https://resocoder.com/2020/04/09/flutter-state-management-tutorial-provider-changenotifier-bloc-mobx-more/  
https://resocoder.com/2019/10/26/flutter-bloc-library-tutorial-1-0-0-stable-reactive-state-management/  
https://bloclibrary.dev/#/fluttertodostutorial  
https://bloclibrary.dev/#/flutterfirestoretodostutorial  
https://github.com/felangel/bloc/tree/master/examples  
https://www.youtube.com/watch?v=knMvKPKBzGE  
https://pub.dev/packages/hydrated_bloc  
https://www.youtube.com/watch?v=vSOpZd_FFEY  
https://www.raywenderlich.com/4074597-getting-started-with-the-bloc-pattern  
https://medium.com/flutter-community/making-sense-all-of-those-flutter-providers-e842e18f45dd  
https://www.raywenderlich.com/6373413-state-management-with-provider  
https://www.filledstacks.com/post/flutter-state-management-with-stacked/  
https://github.com/FilledStacks/stacked-example/tree/master  
https://riverpod.dev (experimental provider rewrite)  
https://mobx.netlify.app/getting-started  
https://github.com/mobxjs/mobx.dart  
https://github.com/mobxjs/mobx.dart/blob/master/mobx_examples/lib/todos/todo_widgets.dart  
https://www.youtube.com/watch?v=hio1Avj5lOg  
https://www.youtube.com/watch?v=8j7W91ZJuV0  
https://circleci.com/blog/state-management-for-flutter-apps-with-mobx/  

#### Thoughts:
I think this basic research takes more time than i thought.

#### Link(s) to work...

> **Highlight:** Add a PageStorageKey to your list for maintaining the position. Found at [filledstacks](https://www.filledstacks.com/post/bottom-navigation-with-stacked-architecture/). 


## Day 0.2 - 17. July 2020

#### Today's Progress:
Found [flutter get/getx](https://pub.dev/packages/get) package, which looks very promising. Created a new playground for only moor, statemanagement and firebase.

Playing again with moor code/examples. Upgraded the [ResoCoder/flutter-moor-tutorial](https://github.com/ResoCoder/flutter-moor-tutorial) to moor_flutter: ^3.1.0 (this example uses MultiProvider and DAOs).

The [flutter moor todo example from Rody Davis](https://github.com/rodydavis/moor_shared) uses rxdart and 'blocs'.

#### Links flutter moor:
https://moor.simonbinder.eu/docs/getting-started/  
https://github.com/simolus3/moor/tree/master/moor_flutter/example  
https://resocoder.com/2019/07/17/moor-room-for-flutter-3-foreign-keys-joins-migrations-fluent-sqlite-database/  

#### Links Get/GetX:
[Amateur Coder - Complete GetX State Management](https://www.youtube.com/watch?v=CNpXbeI_slw)  
https://github.com/jonataslaw/getx  
https://github.com/tadaspetra/getx_examples  
https://pub.dev/documentation/get/latest/  
https://github.com/loicgeek/todo_getx  
https://medium.com/@loicgeek/flutter-how-to-create-a-todo-app-using-firebase-firestore-and-firebase-authentication-with-getx-6a9265ca5f00  

#### Thoughts:
Routing with GetX looks so easy. And i'll fixed some null problems in the todo_getx code to run it on the Simulator. All in all a good day with more flutter moor findings.

#### Todo:
- https://github.com/kauemurakami/getx_snippets_extension  
https://github.com/kauemurakami/getx_pattern  
https://www.youtube.com/watch?v=RaqPIoJSTtI  

#### ToLookAtLater:
[Deploying App to the App Store](https://www.youtube.com/watch?v=NT-W5sAarco)  
https://github.com/cybdom/storage_manager  
https://www.raywenderlich.com/10794904-internationalizing-and-localizing-your-flutter-app

#### Todays Takeaway:
[flutter pub upgrade](https://flutter.dev/docs/development/tools/sdk/upgrading#upgrading-packages) solved some wired multi_headers.dart:97:8: Error...  
pod install solved as well an error 

#### Link(s) to work...

> **Highlight:** Found this flutter moor ['issue'](https://github.com/simolus3/moor/issues/151) wich leads to a really [nice moor shopping cart gist](https://github.com/simolus3/moor/issues/151)

## Day 0.3 - 18. July 2020

#### Today's Progress:
Forked #100DaysOfCode. Moved and converted the content from my blog post to this log  
Created 'journals' for each project in Paper App  

![](assets/0.3-project-journal-screenshot.jpeg)

First look at the eatsleepcoderepeat code. So alpha... that has to be a fresh start with some steps from

> The optional not-so-optional steps that flutter doesn't mention when creating your project.
https://dash-overflow.net/articles/getting_started/

#### Thoughts:
Feels demanding to switch between the projects. I hope this is the 'project cleanup/setup phase'.

#### ToDo:
- Create new eatsleepcoderepeat flutter project  
- Record times for logging

## Day 0.4 - 19. July 2020

#### Today's Progress:
Created new flutter project. Checked my ['dart settings'](https://dartcode.org/docs/recommended-settings/) in vscode. Used (regex) search and replace ```//.*``` to remove the flutter main.dart boilerplate comments.

Implemented [analysis_options.yaml](https://github.com/flutter/flutter/blob/master/analysis_options.yaml) which was one step from [Rémi Rousselets article](https://dash-overflow.net/articles/getting_started/). The linting step is a later todo.

Played with [json](https://flutter.dev/docs/development/data-and-backend/json) and [shared_preferences](https://pub.dev/packages/shared_preferences)

Moved and fixed first code from old project to eat_sleep_repeat.

#### Thoughts:
Renamed project to eat_sleep_repeat. The code part is too specific for an app name but was really a lifesaver during the past few months.

From [shared_preferences](https://pub.dev/packages/shared_preferences): There is no guarantee that writes will be persisted to disk after returning, so this plugin must not be used for storing critical data.

Not critical, but a bad user experience, if the stored  'motivations' are lost.

So there is a todo, maybe the [localstorage package](https://pub.dev/packages/localstorage/) will solve this. 

#### Links:
https://medium.com/better-programming/flutter-how-to-save-objects-in-sharedpreferences-b7880d0ee2e4  
https://codingwithjoe.com/flutter-saving-and-restoring-with-sharedpreferences/

#### ToDo:
Test the [localstorage package](https://pub.dev/packages/localstorage/)  
Fix wired output [link](https://stackoverflow.com/questions/55399209/update-flutter-dependencies-in-pub-cache)

#### Todays Takeaway:
Enabled [flutter-ui-guides](https://dartcode.org/releases/v3-1/#preview-flutter-ui-guides) (restart vscode) and installed [pubspec-assist](https://marketplace.visualstudio.com/items?itemName=jeroen-meijer.pubspec-assist) this could be very useful. Less pub.dev search package and copy to pubspec.yaml


## Day 0.5 - 20. July 2020

#### Today's Progress:
Implemented a drawer. Found after i watched a [talk](https://youtu.be/FCyoHclCqc8) from the flutter europe conference 2020. [drawer_challenge](https://github.com/MarcinusX/drawer_challenge)

Added 'GetX' and implemented first controller for the logic stuff.

Played with sliders (link below)

#### Thoughts:
I'll have to reduce the features for stept 1. Remembered the agile [skateboard](https://m.dotdev.co/the-agile-bicycle-829a83b18e7) 

#### Links:
https://pub.dev/packages/flutter_xlider/  
https://fidev.io/complex-ui/

#### ToDo:
Use/Test [get_storage](https://pub.dev/packages/get_storage) for step 1 instead of shared_preferences or the localstorage package

## Day 0.6 - 21. July 2020

#### Today's Progress:
Fixed 'disable onDoubleTap' in HomeView if drawer is open. Removed sliders. Implemented get_storage to 'observe' the TextField value onChange and save it.

#### Thoughts:
Lost in GetX. It's late. Let go and start fresh tomorrow.

#### ToDo:
Use a model with 'word', 'xcord','ycord' etc.

#### Todays Takeaway:
Always a good idea to 'inspect' the used widget (see highlight;)

> **Highlight:**
There is a maxLength for TextField...

## Day 0.7 - 22. July 2020

#### Today's Progress:
#### Thoughts:
#### Links:
#### ToDo:
#### ToLookAtLater:
#### Todays Takeaway:
#### Link(s) to work...
> **Highlight:**

## Day 0.8 - 23. July 2020

#### Today's Progress:
#### Thoughts:
#### Links:
#### ToDo:
#### ToLookAtLater:
#### Todays Takeaway:
#### Link(s) to work...
> **Highlight:**

## Day 0.9 - 24. July 2020

#### Today's Progress:
#### Thoughts:
#### Links:
#### ToDo:
#### ToLookAtLater:
#### Todays Takeaway:
#### Link(s) to work...
> **Highlight:**

## Day 0.10 - 25. July 2020

#### Today's Progress:
#### Thoughts:
#### Links:
#### ToDo:
#### ToLookAtLater:
#### Todays Takeaway:
#### Link(s) to work...
> **Highlight:**

## Day 0.11 - 26. July 2020

#### Today's Progress:
#### Thoughts:
#### Links:
#### ToDo:
#### ToLookAtLater:
#### Todays Takeaway:
#### Link(s) to work...
> **Highlight:**