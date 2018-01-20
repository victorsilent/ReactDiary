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