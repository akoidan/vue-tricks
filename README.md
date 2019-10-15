# vue-tricks
Advantages over reactjs:
 - Cleaner code (separetion between logic and view)
 - Code is intuitive
 - Handling state in react could be really a pain in the ass: https://stackoverflow.com/questions/46185343/react-rerenders-whole-component-when-its-properties-change
 - Vue automatically updates input state, no need to overhead code with "<input onChange" to apply changes from input.
 - wtf is that reactjs stacksize of about 110 calls for update action. 
 - When react crashes, components just dissapear ( i mean no divs in html are present). Impossible to view the current html state after that
 - Say hello to ecosystem, and different extensions to react-chrome and react-redux (that requires tinkering to get it work). Yeah, guess what happens when react crashes? Correct, it displays nothing!
 - shouldComponentUpdate tells you anything? aha components should be reactive and not longer than 5 lines of code. Have you really seen it in huge enterise? Say hello to 500 lines jsx template and flashing green `<body` on simple textinput
 - react doesn't have single file components, and even is some not known libs support it, your favorite IDE will go crazy about it. So what, who needs SFC? Tell me that when you start importing css files to jsx and end up with coupled together css/js across different component in huge enterpice reactproject
 - no `v-model` attribute, what do you need to update prop on parent, Yeah correct go proxy 
 - Redux complexity, no comments... Yeah you can go with different libs like graphql/mobx, is that what happens when you come to the project that has rect?. Oh yeah add saga to separate the code it becomes more intuitive (*joke)
 - vuex-module-decorators, vue-property-decorator, simplifies the code even more, than declaring state in react with static init, or having it in constructor
 - Scoped css, any alternative in react, go watch for duplicates in your css imports across all files
 - Template tag, v-for, v-show, v-show, v-if- v-else-if (hello do expression tc39 stage 1) having html exatly as it is, don't need to change classNames and etc, computed props (yeah go declare it twice from state), watch property
 - Pipes v-on:submit.prevent=, creating own attributes, custom pipes.
 - Different types of class declaration out of the box, string, array, object.
 - v-show on components are lazy out of the box, try hard that with virtual dom, yeah the truth hurts.
 - Mutliples slots ( react children only has one)
 - vue 3 supports ts out of the box, 
 - css transitions out of the box (automatic class triggering and detecting appropriate timings)
 
