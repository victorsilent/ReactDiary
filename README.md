# What I learned


## ReactJS Diary

07/01/2018 - Today I watched the section of "Styling an App with scss" of the "ReactJS Second Edition" course. It was easier to learn because I've made some examples before, but the main interest was learn about the architecture of the application, but the course teaches only "basics" stuff.

* Important things:
    * At my past examples (study cases) I had used SCSS with the same approach, but the architecture was a little bit different, I had put my SCSS files at the same folder of my components. Reasearching on differents projects at github I had found a very interesting architecture to use:

```
With that approach I gain the benefit of have all my custom styles and components togeter and can import they with normal import: 
import ComponentName from 'Components/ComponentName';

Components
└─── ComponentName
     | ComponentName.js
     | ComponentName.scss
     | index.js
```



08/01/2018 - Today I watched a couple of video from ReactJS Second Edition and learned about "React Router". I've made a simple example to test the features of that library and it was very good, the simplify of API made it easier to do!

* Important things:
    * Swtich componente create an "validator" to routes that check the routes previously created and display the first route that match with the current URL, if that URL don't have one matched route you can set a "default" route that display a 404 page.


19/01/2018 - Hihi so much time without comment here, let's update! At past days I've study so much about redux and firebase! I am almost finishing my first app with that! Ok, it's a simple todolist with crud operations, but it's ok for me at this time <3
At the end of month I want to be confident to build more complex things with react+redux+firebase, but I need to knew more about how to update my current state based on firebase database.

21/01/2018 -  Ok, yesterday and today were a rest days for me, so I haven't study at all. The only things that I made were two methods of my todo-list app with firebase and learned that I don't need to control all my data at redux if Firebase is running as backend, because the data have already state management at server, the only thing that I need to do is listen the changes and update my app correctly.
* Important things that I need to do at the next week: 
    * Use react router with one app at firebase
    * Learn more about HOC and React components patterns
    * Watch more video lessons to see more ways to build an app.
    
31/01/2018 -  So many days without update again, hihi, past week I received a challenge to learn and create an app with react-native, it was a great challenge and I've almost done, except by the problem with one lib (react-native- navigation) probably I've forgot something at configs or set it to incompatible versions of packages at project, react-native/react-native-navigation/SDKs... Btw, I learned a lot, the main thing was the concept of containers and components , because react-native uses "screens" and components, and there, I can associate with containers and components of normal reactjs project :)

10/02/2018 - Yeah, another couple days without updating here, but I'm was not studying ReactJS, I've found some lack of knowledgement that made me delay my code production, so I stopped with reactjs to start some personal projects that will bring me the confidence to continue my path at reactjs.
Just to make it registred, I'm studying flexbox grid ([Bijoux - Case Study CSS Framework](https://github.com/victorsilent/bijux)) and Javascript (Functions and DOM, this time only the advanced parts)