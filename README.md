# CS-360-Mobile-Architect-and-Programming

****Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?****
  
  The goal of this app was to provide a user-friendly inventory application to track and manage a physical inventory. The requirements for the application were that it was a mobile app, had a user login/create account page, and allowed users to add new items with names, quantities, and dates, as well as update item attributes and delete items. The app was to be made in Android Studios and uses an intuitive design that implemented a grid-style page as well as SMS messages to update a user on low quantity counts. 

****What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?****

  Starting from the launch of the application, the first screen a user interacts with is the login/create account screen. After a user enters existing credentials or creates a new account, they are passed to the main screen. The main screen on the new account had no items so is quite bare. At the top of this screen is a header for the item grid as well as an add item button. When this add item button is pressed it brings the user to a new add item page where they can name, quantity, and date for an added item and save it to the database. After the item is added a user is directed back to the main page where the added item is shown on the list. The list is a recycler view that uses an item layout to scroll and load the needed inventory items. All the screens mentioned use a consistent color theme and similar overall styling. Texts are easy to read on contrasting backgrounds and functionality is made clear with intuitive button and function designs. The design I created was successful because of how simple it was.
  
****How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?****

  The development of my application came down to two large steps. The first step was to create all the layouts needed to incorporate the needed functionality. After I was pleased with the layout and had all the fields needed, I began to add functionality to the areas that needed action. This included adding activity to button presses, managing editText fields, and loading different views at various times based on which screen the users selected to move to. Both steps were refined under iterative programming. When creating the layouts it was a matter of making one small adjustment, seeing how it looked, altering it again, and checking again. It was through this process that I was able to create a well-crafted UI for the user to use. I followed a similar strategy when adding functionality. I developed and evaluated a singular screen and or method before moving on to the next so that when things went wrong, I did not have a lot to look back on and test. 

****How did you test to ensure your code was functional? Why is this process important, and what did it reveal?****

  The testing I conducted was solely user testing. I went through the application and assessed all inputs, outputs, and other edge cases other users may try within the application. If I were to go back, I would incorporate some unit tests on methods and classes to better understand how they would handle certain inputs, but for the basic functionality there was, it passed my personal use cases. 

****Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?****

  The entire UI/UX design phase was something I had not spent a large amount of time working on before developing this application. It was challenging to think of how the larger user base would like to interact with the application sometimes instead of just myself. I had some biases towards design that I had to put to the side. I had a different view of what was intuitive vs what a regular first-time user would see as intuitive as I created the application. This was challenging at first but with practice became easier and easier. 

****In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?****

  I think that overall, the application was a success. The principal areas that I gained experience in were Android Studios as a platform, creating and enhancing UI/UX design, as well as managing permission, saving to, and accessing system files via an application. All three of these topics were new to me, and I found the end product to incorporate them all quite nicely.
