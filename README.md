### Hi there 👋

My name is Simon Senger. I have an AP degree in Computer Science and started working as a Software Developer in March of 2020.

I mainly work within the Microsoft space of frameworks/sdks/packages/tools/etc. but sometimes venture into other languages and technologies (mostly here on my private profile writing silly apps just to learn new stuff).

In the short amount of time i've been developing code, i've started developing my own clean code principles, which i describe below.

## Cool Code Calisthenics

1. Code is book with a story to tell, so write it as such, not as your personal notes.
Use full, detailed names which are long enough to describe what they are and do, but don't forget your context and do too long and meaningless names.

2. I'd rather be a short guy with a straight back, rather than a tall guy with a crooked back.
Methods should never be longer than what can be viewed on a screen (on a 24" 1920x1080 monitor).
Minimize indentations by returning early and breaking out methods into several smaller which describe the flow of the main method.
You should ofcourse also keep classes short, but as long as its name describes its purpose singularly and clearly, and all methods/functionality fall under that name, then its fine by me.

3. Code as if copy paste was never invented.
Dont write the same line of code twice. Writing something twice has a 99.9% chance of being written a third time and at that point, you should be able to
write a generic method with this code in it, which can be used by others, whether it is an Extensions, static Util method or something else. 

4. A good program is one maintained by its users, not its developers.
This is just a preference, but i like writing programs generically, in a way where the user should be able to configure all the important stuff. Either through input in a GUI which is a part of the system/application, or through config files, pipeline variable, etc. This way, its way easier to respond to feature/functionality changes in the future without having to rework your code.

## Current "Roadmap"/Ongoing projects
1. Todays Todo's
A todo application, with a twist. All todo's are cleared each day and you will have to readd them if you did not complete them on the same day that they we're added. 

2. Minimal IoT
This is not something that specific, other than me having fun. I have worked with IoT devices in my career and wanted to try building my own little IoT system, with a frontend, backend and use a raspberry pie as IoT device, maybe to use for some custom home automation later on.

3. Extensions
As mentioned, i mainly work within the Microsoft "namespace". This means that my main language of choice is C#. Therefore i have started this library to add all sorts of extensions which i find i need in my day to day work. I plan on publishing this to nuget at some point, no idea when though, heh.
