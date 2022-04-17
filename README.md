# LoacalStorage and Event Delegation

A project from [JavaScript 30 -15](https://youtu.be/YL1F4dCUlLc).

Build a menu, where you can add things, and you can check and uncheck them. The cool thing is that if you type in an item, hit enter, and then refresh the page, it's still there. So that's going to be a persistent state with local storage.

We're also going to do something called 'event delegation'. When user add a new item and you want to add an event listener to it, since you can't add event listener to an element that only exist in the future, you should add event listener to its parent, and then check if an event is happened at your target element or not.

`JSON.stringfy()` - object to string

`JSON.parse()` - string to object
