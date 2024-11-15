
# OCUWallet

### The source code for the OCU Wallet App

#### What is OCU Wallet

The OCU wallet app is a project started by the OCU chapter of ACM that (ideally) will be used by students at OCU to view point and meal swipe balances, check out at the cafeteria and Alvin's, and possibly open doors to buildings. 

#### Who can contribute? 

Every OCU student is welcome to contribute, just make sure you follow our [Code of conduct](https://github.com/ocu-acm/OCUWallet/blob/main/CODE_OF_CONDUCT.md) and adhere to the [Github Flow](https://docs.github.com/en/get-started/using-github/github-flow). 

#### Branching strategy 

The branching strategy will be a simplified version of [Gitflow](https://nvie.com/posts/a-successful-git-branching-model/). We will have a main branch, and devlop branch, and feature/bugfix branches.

In summary, the main branch will be the [working build](https://www.techtarget.com/searchsoftwarequality/definition/build#:~:text=a%20software%20build%20is%20a%20set%20of%20executable%20code%20that%20is%20ready%20for%20use%20by%20customers.) that students will have on their phones, the devlop branch will be where we will compile a series of changes before being merged into main. The feature and bugfix branches will be for individual changes and bug fixes. 

#### Tech stack

##### Front end 

The front end will be [React Native](https://reactnative.dev/), a cross platform javascript component library that allows developers to use [native components](https://reactnative.dev/docs/intro-react-native-components) for their applications while still using javascript/trypescript. 

Application development is a complex and time consuming process, and a lot of the students that are going to be contributing are beginners. This is why we'll be using a front end framework, [Expo](https://expo.dev/), for our project. This may seem counterintuitive, as frameworks tend to bring more complexity than just the library they're built around. While there may be an initial difficulty in navigating the framework, I think that the work it does for you will allow, with a little time, an easier development experience. 

##### Back end

For our back end, we will be using [Node.js with Express](https://expressjs.com/). Express is a lightweight routing framework that is crucial for handling HTTP requests. 

We decided to go with Express because, not only is it easy to learn and minimalist, but it is also built with javascript, the same as React Native. This will allow for a (mostly) seemless development experience.

##### Deployent 

We don't know yet! 

#### Getting Started 

This section is a work in progress. Come back later, or feel free to look at the documentation pages and get started yourself!