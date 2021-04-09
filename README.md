# DGL 104 - Process Portfolio
## By Taiwo Adekanmbi

### Week 1 Activities
**Activity 0101**: 

The problem was converting the website to mobile resolution. I had difficulty fully understanding flexbox, using the right html tag, or choosing to change the tag by experimenting on them, time constraint to make changes or correct the little mistakes, bad time management, CSS height, weight, margin properties.

Solution would be managing my time better to be able to consult my lecturer on any issues I had and tweak any little mistake I left unsolved. Also, I focused more on the textbook thinking the PowerPoint presentations were summary of the textbook, without knowing the lecturer provided additional resources and up to date techniques of making website.


**Activity 0102**: 
1. **Corporate coding style guides- HTML Style Guide**:  
HTML allows spaces around equal signs. But space-less is easier to read and groups entities better together.
Do not add blank lines, spaces, or indentations without a reason. For readability, add blank lines to separate large or logical code blocks. For readability, add two spaces of indentation, do not use the tab key.

2. **Structural readability features**:  
A single file is fine for very small projects. For large projects, it is smarter to split your CSS across multiple files. So, I should have spilt the stylesheet.css based on font, reset, typography, layouts, forms, lists, tables and so on. It makes it easier to manage and debugging.

3. **Exterior readability features**
    - **Comments**:  
    I should have documented my work by adding comments to each new web page. Comments are useful for both my colleagues and me to revisit those files months or even years after creating them. The comments should include:
        - The page’s filename and location
        - The page’s author and the date the page was initially created.
        - The purpose of each code
        - A list of any supporting files used in the document, such as image and audio files.
        - A list of the files that the page links to and their locations

    - **Naming things**:  
I should have used short, meaningful, and descriptive name.

**Activity 0201**:

Identify the values inherent to the app that might help to identify the target user base 
- It informs- people inform you about things that is happening around them
- It communicates – you can communicate freely and effectively with people
- It connects or network – you can have communication with different and unique people in your vicinity or around the world
- It saves person money – you are not required to pay extra for calling people in a domesticated or international setting, just pay for only internet plan to enable free communication with anybody from anywhere
- It maintain relationship – communicating with your friends, parents, family, lover etc can maintain a level of familiarity and ensure you continue to know lots of things about them to maintain a relationship.
- It ensures sales or profit making – communicate with sellers to reserve product and send payments

Briefly describe the target user base. 
- People with compatible phone
- People with functional internet
- People who like to interact with different and new people
- People who desire to maintain connection with families and friends

Do your goals in using the app match those of the target user base?
- Yes, I communicate with variety of people and maintain a relationship with family and friends

**Activity 0202**:

Examine the identifiers (i.e. variable and method names, etc.) used in the code. Are they sufficiently descriptive? Are they perhaps too descriptive (i.e. too long, or to complicated). 
- Yes they are generally short and precise

Do they make sense in the context of your project? 
- Since the project deals with creating a Restaurant website, navigation list, class and identifier like Home,Menu, Reservation, testimonal perfectly suit it

Identify between five and ten names in the code that you could consider changing either to be more descriptive, or more consistent with one another.
- paragraph – introduction
- testimonial – recommendation
- author – customer
- slide – picHeader
- menuHeader - menuSubTitle
- menu - menuItem

**Activity 0301**:
- Similar Home Page, play and connect
- Download selector icon is a little different
- The three dots for option are different: Iphone is horizontal, android is vertical
- Add to Home Screen option is available on android but not on ios
- On the browse page, the way genre list are portrayed is different: ios is row position with simple icons, android is in column position in a colourful rectangle
- New release page for android has a fading from colour to black linear gradient background colour tone, ios has a smaller section for the title.
- Filter option of the android is simple and small, in ios the filter option overshadows the screen with a translucent background.
- Podcasts categories page on android has colourful rectangle, ios has simple icons in front of rectangular pictures
- The podcasts categories when selected as fade from picture to black linear gradient for the titles on ios e.g top podcast, android just has a fading from colour to black linear gradient background colour tone
 - All artists list on Library page for ios is alphabetically with the alphabet letter crammed together at the right side of page, on andriod the artist list has alphabet on top of artists name strating with the same alphabet.

**Activity 0302**:
- Animation of icon or images informs the user about an action. It enables a subtle change of UI to the awareness of the user. It can provide a smooth and realistic movement of an object.  It changes the layout within a activity and between layouts in separate activities.
- The documentation structure provides general definition with illustrative examples attached to it. It provides codes and links to expand more on the topic.

**Activity 0401**:
- Slack: ONBOARDING - Sign Up Flows
1. Skeleton Views:

When loading the app after completing the signing process, the skeleton view is first displayed to create the feeling that the app will soon load the images and info. It encourages patience and anticipation from the user, rather than displeasure. It occurs because the network is not fast enough for the app. It appears in form of grey rectangle for images, grey circle for profile, grey slightly rounded rectangle with a small height for the text and so on. 

2. Two-Step Authentication:

Ensuring the email address is valid, a six-digit confirmation code is sent to the email to enter in the app. It is for security purpose which occurs by generating a one time password remotely from the app server and is shared with user through the SMS or email to be typed in, thereby completing part of the log in process. 

**Activity 0402**:

- The second exercise is more orthogonal because you are not tied to a particular product or file, so it is reusable. The concept of orthogonality relates to MVC because it follows similar principle of decoupling your code and avoiding duplicating codes. This is for the purpose of isolating the code to make changes and fixes to some parts of it without affecting the overall project for the worst.

**Activity 0501**:

- MVC (model-view-controller) – Model is the business logic of the project with no tie to the view or controller, so reusable and testable. View is the visual representation of the project, UI, that communicates with the controller when the user interacts with the project. It is more connected to the Controller which ensures flexibility. Controller is the middleman that connects the view to the model. It is difficult to test and inflexible because of its strong coupling with view, which can almost be an extension, and can be overloaded with too code. It is for simple project.

- MVP (Model–view–presenter) - Model has the same function as MVC. View now has the Activity and a view interface to allow unit testing. Presenter is similar to the controller from MVC with its own interface and no ties to the View, which ensures testability and flexibility. But it can receive more business logic over time, which makes it difficult to maintain. It is for more complex project but could increase the number of codes in the project.

- MVVM (Model–view–viewmodel) - Model has the same function as MVC. Views binds to observables and actions shown by the ViewModel. ViewModel wraps the model and provides observable data for the view to use. It also passes events from the view to the model, with no ties to the view. MVVM is testable and independent, but view can receive presentation logic over time in the xml if values are not taken directly from the ViewModel, so makes maintenance difficult. It is for more complex project that can have less codes.

**Activity 0502**:
- I can avoid global variables by ensuring that i only ever pass anything to or from functions via parameters & return values.


## SECOND HALF

**Activity 0801**:
MVI|MVP|MVC|MVVM
---|---|---|----
Uses interfaces as a View|Uses Activity/Fragment as a UI|Uses View to render UI|Uses Activity/Fragment and Binder  
Models handles both business logic and represent the state of the app (app response to changes from input of values or button click, through UI change with a new info, progress bar or different screen)|have Model as a business logic or data of application|have Model as a business logic or data of application|Model as a business logic or data of application
Intent represents an intention or a desire to perform an action, either by the user or the app itself|Uses Presenter |Uses Controller to handle the View input.|Uses ViewModel

MVVM  is useful for bigger app with many background tasks and states, but requires moderate to advanced knowledge on reactive programming, multi threading, Kotlin and RxJava. The other three patterns are utilized by novice Android developer.


**Activity 0802**:

***Skip the Dishes***

- Locations are crucial for the app to display the restaurant available around your area and direct the delivery person to know to deliver the food.
- Provided notification for the arrival of the delivery person without requiring you to open the app constantly.
- Used a server for bigger tasks such as payments, GPS and so on to reduce resources used by the app
- Used cache for storing username and password information, location, payment information to reduce processing time
- Used eager and lazy loading combined within the app
- Made sure the app functioned well to the battery saving mode of the device.

**Activity 0901**:

***YouTube***

Passage of Time (i.e. loading time):
- Display: YouTube Logo
- Display: Loading screen – Animated spinner only because it was greater than 200ms
- Display: video

Use of Notifications:
- YouTube requires you to click subscribe for a channel and the bell icon for a notification, so you can prioritize what channel notification you desire. The Rich or interactive push notification gives you the option to play, watch later or turn off.

A Lack of Internet Connectivity:
- The status bar displays that the internet is in airplane mode and YouTube provides an animated spinner, a suggestive graphic picture, a text telling me that I am offline, but I can still watch downloaded videos with a button to link to that screen.

***Spotify***

Passage of Time (i.e. loading time):
- Display: Logo
- Display: Black screen
- Display: Song playlist

Use of Notifications:
- Spotify displays only the music you can playing as a notification with the play, next, previous and like option.

A Lack of Internet Connectivity:
- Spotify displays most of the playlists, some with pictures, others blank, with a small text saying no internet connection available. You can only play music that is downloaded offline.

**Activity 0901**:
- Did you use a strategy similar to one of these three?
I used logging and tracing by watching the data structure to see where the error stops at or program starts being affected. Then I google what the error message means to resolve it. But I did not create a tracing statement.

 - Did you take a different approach?  No, I did not. 
 - What can you learn from these strategies that you will take forward to future projects? I will see if I can use tracing statements, explain every step of the program so that something will click, acknowledge it could be software, OS or complier issue as a last thought/resolute.

 **Activity 1001**:
- I assume things about codes a lot, how they function and their position on the project. It can affect how I utilize the code with a limited perspective. So, I need to learn to expand my knowledge through research about several codes to limit my assumptions about them. I also need to have a good understanding of every code I input, to able explain it, plan ahead, write on what I assume the code will do, always be ready, willing and educated on updating code. This prevent the code from being slow, not really working, having new bugs, weird changes, fear of making changes to the work that you do not fully understand. 

**Activity 1002**:
- I could use it on the switch statement of add icon in Assignment 3
```
public boolean onOptionsItemSelected(MenuItem item) {
    switch (item.getItemId()) {
        case R.id.action_add:
            FragmentManager manager = getSupportFragmentManager();
            AddItemDialogFragment dialog = new AddItemDialogFragment();
            dialog.show(manager, "addItem");
            return true;
        default:
            boolean answer = super.onOptionsItemSelected(item);
	   assert boolean;
    }
```
- Assertions is used for conditional or switch cases, can replace the “if” statement, used in arguments for private methods and to check if my assumptions are right.

**Activity 1101**:

***Amazon web service Mobile***

Amazon Web Services (AWS) offers one of the best hosting servers in the world. AWS is a backend server for mobile apps. It offers a broad set of tools to develop backend apps for Android apps. Trusted by top apps like Netflix, Adobe, Comcast, Airbnb, Twitch, LinkedIn and more, Amazon Web Services is highly reliable and offers uncompromising security options.
[Top 5 Best Mobile App Hosting Servers](https://appsopinion.com/top-5-best-mobile-app-hosting-servers/)

The following are the main features of AWS:
- AWS is scalable.
- The tools are very easy to use.
- You can build a plentiful backend app with its comprehensive set of tools.
- Its features include Push Notification, Authentication, Cloud Storage, etc.
- A lot of features including Notification, Authentication, Cloud Storage, data warehousing, Device Farm
- SDK for a lot of platform including iOS, Android, Xamarin, React Native, Unity.
[Best Mobile App Backend](https://os-system.com/blog/what-is-backend-and-how-to-choose-the-best-mobile-app-backend-for-your-application/)
- The cost to host an app on AWS depends on the number of users your app has. They also have a free tier that can be used for 1 year for hosting a mini-site or a small app, after that the price is $8-10 a month, but if you have more users, then the price rises exponentially, and for big startups and corporations, it can be as high as $5,000 a month. [Where to host Mobile App Backend](https://www.devteam.space/blog/where-to-host-mobile-app-backend/)

***Firebase***

Firebase is a great platform to develop high quality apps, grow user base, and earn money. Backed up by Google servers, trusted by top apps like Gatsby, Flutter, Musixmatch, Runtastic and Shazam. This platform is highly reliable and got features like real-time analytics, authentication, storage, crash reporting, Cloud Storage, Hosting, Test Lab for Android, File Storage and Push notifications etc. The firebase takes out the burden of managing backend servers, user engagements and monetizing options.
[Top 5 Best Mobile App Hosting Servers](https://appsopinion.com/top-5-best-mobile-app-hosting-servers/)

Firebase help you develop apps for multiple platforms fast and quickly without worrying about the infrastructure. Since it is on Google cloud, scalability of servers is as easy as click of a button (can be automated too). There are lot of tools to develop and test your app before the mass release. With the in-house tools like analytics and AdWords, tracking the growth and promoting the app is very easy.
They have a free tier, and you pay beyond a threshold.

***MySQL database***

MySQL is an open-source relational database management system, so wisely choosing MySQL hosting service that secures this database will allow you to enjoy all the benefits of a quality hosting. In short, connecting an app to MySQL database is configured in the backend for which a MySQL server and a simple Application programming interface (API) are necessary. The application will connect to the database only by sending requests to an API that has to be previously written in form of a script (usually PHP) whose job is to process a request and respond to the app. [Mobile Apps Need Hosting](https://designsmaz.com/do-mobile-apps-need-hosting-and-how-it-works/)

***Trello***

Trello is visual project management and collaboration tool that utilizes Kanban boards (which represent projects), cards (which represent tasks), and lists (which can be used to track the statuses of different projects) to move tasks or organize your resource materials in real-time. As with Kanban, the app lets you manage multiple projects simultaneously through visual ticklers. You can see who’s working on what as well as what the statuses of tasks and projects are. It can help you track your entire work progress from start to finish.

Trello lets your teams work more collaboratively so you can get more done. Keep everyone in the loop, get the most out of each meeting, and multiply your productivity with features that make work fun, flexible, and rewarding. Every team, from startups to enterprises, use Trello to organize, track, and coordinate workflows.

Freelancers and small businesses will find the pricing appealing (a freemium is available), while larger companies will have no problem scaling its features. Other key features include built-in rule-based workflow automation with buffer, custom card/board buttons, and a checklist tool.

Trello integrates with key software such as productivity apps, email apps, time tracking apps, and IM apps.

Pricing starts at $9.99 with the paid plans giving you more file storage, team features, and priority support, among others. [Trello](https://reviews.financesonline.com/p/trello/)

***Postman***

Postman is a simple user-friendly application used for testing APIs. It sends a request to the webserver and gets the response back. The user only needs to fill up the headers and cookies that API expects and send a request which in turn gets the response.[Postman Api Testing](https://teknotrait.com/postman-api-testing-features-benefits/)

First known as an API validation browser extension, Postman has emerged to be the tool of choice for API development, testing, and managing APIs for QA professionals. Postman was once a side project by Abhinav Asthana that simplified API workflow in software testing and development. By now, the tool has had over 4 million users worldwide. 

Postman can run on multiple operating systems from Windows, Mac OS to Linux. It offers developers more room to develop APIs. For functional testers, Postman allows testers to create tests for API calls without much effort spent on coding scripts. [Pros and Cons for Postman](https://dzone.com/articles/postman-for-api-testing-pros-cons-and-alternative)

***GitHub***

GitHub helps software teams to collaborate and maintain the entire history of code changes. You can track changes in code, turn back the clock to undo errors and share your efforts with other team members. It is a repository to host Git projects. Git is an open source version control system that features local branching, multiple workflows, and convenient staging areas. Git version control is an easy to learn option and offers faster operation speed. [Version History](https://dzone.com/articles/top-10-version-control-systems)

**Activity 1102**:

There is a command palette for all the actions or open keyboard shortcuts in VS Code. Under Help section on the Welcome page, there is the printable keyboard cheat sheet. This can be a quick replacement for mouse to perform tasks directly from the keyboard.

