# 1. Introduction
![alt text](image.png)![alt text](image-1.png)![alt text](image-2.png)![alt text](image-3.png)![alt text](image-4.png)![alt text](image-5.png)![alt text](image-6.png)![alt text](image-7.png)
# 2. Hello World
## Software required
![alt text](image-8.png)![alt text](image-9.png)
## Creating react app
![alt text](image-10.png)
## Code
![alt text](image-11.png)![alt text](image-12.png)
## For running app - navigate inside folder and run command
![alt text](image-13.png)![alt text](image-14.png)
## Edit app.js
![alt text](image-15.png)![alt text](image-16.png)
## Ways to create react app
![alt text](image-17.png)
- npm mein pkg globally install karo
- then create karo project
# 3. Folder Structure
## package.json 
![alt text](image-18.png)
-Contain dependency and script require for project
## package-lock.json 
![alt text](image-19.png)
- ensure consitent installation of your dependency.
## We have gitIgnore and readme file
## node-module
![alt text](image-20.png)
- yaha sari dependency hoti hai
- jab create-react-app command chalate tab ye folder create hota.
## public
![alt text](image-21.png)
- yaha hum react ko controll denge.
## src folder
### Starting point is index.js
![alt text](image-22.png)![alt text](image-23.png)
### App component
![alt text](image-24.png)
- jo browser mein dekh rahe wo yaha se aa rha
- app.css for css styling
- app.test for unit test
- index.css apply style in body tag
## Flow
- jab bhi npm start command chalate tab index.html serve hoti browser mein
- iske baad control index.js mein jata
    - yaha react component dom render karta dom node ko
- yaha se app.js mein jata.. yaha se html dikhta
# 4. Components
- Component is a part of UI
- Components are reusable
- components also contain other component
## Eg
![alt text](image-25.png)
- Yaha total 5 component hai
- jo main component hai usse root component bolenge.
## How component translate code in our app.
![alt text](image-26.png)
- component ko hum js file mein rakhte generally.
## Components types
![alt text](image-27.png)
## Apne code ko khangalo
![alt text](image-28.png)
## Imp
![alt text](image-29.png)
# 5. Functional Component
![alt text](image-30.png)
- ye ek js function
- ye input leta hai optionally object of property(prop)
- Aur  output  deta hai jsx i.e UI
## Create functional component
#### Target hai greeting karna
![alt text](image-31.png)![alt text](image-32.png)![alt text](image-33.png)![alt text](image-34.png)
### Via Arrow function
![alt text](image-35.png)![alt text](image-36.png)
## Intresting thing 
## 1) Default export
### Yaha hum default export kar rahe hai Greet.js mein
![alt text](image-37.png)
### Isse hum isse kisi bhi name se import kar sakte
![alt text](image-38.png)![alt text](image-39.png)
## 2) Named Export
![alt text](image-40.png)
### Exact same name se import karna honga wo bhi curly braces mein
![alt text](image-43.png)![alt text](image-44.png)
### Agar galat name se import  kiya
![alt text](image-41.png)![alt text](image-42.png)
# 6. Class Component
![alt text](image-45.png)![alt text](image-46.png)
## Create class component for Greeting
![alt text](image-47.png)![alt text](image-48.png)![alt text](image-49.png)
## Comparison
![alt text](image-50.png)
# 7. Hooks Update
![alt text](image-51.png)![alt text](image-52.png)![alt text](image-53.png)
# 8. JSX
![alt text](image-54.png)
## Create component using Jsx 
![alt text](image-55.png)![alt text](image-56.png)![alt text](image-57.png)
## Create component without using JSX
![alt text](image-58.png)![alt text](image-59.png)
### Varaition-1
![alt text](image-60.png)![alt text](image-61.png)
![alt text](image-62.png)
### Variation-2
![alt text](image-63.png)![alt text](image-64.png)
### Variation-3
![alt text](image-65.png)![alt text](image-66.png)
### Imp
![alt text](image-67.png)![alt text](image-68.png)![alt text](image-69.png)
### Class bhi dalte, id ke jaise
![alt text](image-70.png)![alt text](image-71.png)
### Imp 2
![alt text](image-72.png)![alt text](image-73.png)![alt text](image-74.png)![alt text](image-75.png)
### Imp3
![alt text](image-76.png)
- jsx mein aise likhenge.
- jsx ke liye aapko React lib import karna hota hai
- jsx se code likhne padne mein aasan hota
- kaha tak React.createElement() likhte baithonge, aaj 2 component hai kal payli ke 50 honge.
### Imp4
![alt text](image-77.png)![alt text](image-78.png)![alt text](image-79.png)
# 9. Props
## Components are reusable(app Greet component ko mulitple time use kar sakte)
![alt text](image-80.png)![alt text](image-81.png)![alt text](image-82.png)
### Ab yadi hume 3 alag alag logo ko greet karna hai - so for this props comes in picture
- props is property object(optional)
- it allow component to dynamic
### Hum aap component se name bhejehge Greet component ko.. and that will be render in browser
![alt text](image-86.png)
![alt text](image-83.png)![alt text](image-84.png)![alt text](image-85.png)
### Var -1 
![alt text](image-87.png)![alt text](image-88.png)![alt text](image-89.png)
### var-2 hum react lib ko expression evaluate karne bolenge
![alt text](image-90.png)![alt text](image-91.png)![alt text](image-92.png)
## Passing other prop
![alt text](image-93.png)![alt text](image-94.png)![alt text](image-95.png)
## Unknown content aap Opening closing tag ke bich likhe..
![alt text](image-96.png)
### Ab isse retrieve kaise kare.
![alt text](image-97.png)![alt text](image-98.png)
### Why? kyuki jsx mein sirf ek hi element return hota, so wrap all element into 1
![alt text](image-99.png)![alt text](image-100.png)
### Next one
![alt text](image-101.png)![alt text](image-102.png)
## Props with class Component
![alt text](image-103.png)![alt text](image-104.png)![alt text](image-105.png)
## Imp
- props are immutable
- i.e value cannot be change
- react component have to act like pure function with respect to props parameter.(isiliye aap change nhi kar sakte.)

![alt text](image-106.png)![alt text](image-107.png)
# 10. State
![alt text](image-108.png)
- Jaise hum props ko render karte dynamically waise hi same hum state ko bhi render kar sakte
## Create class Component
![alt text](image-109.png)![alt text](image-110.png)![alt text](image-111.png)
## Variation-1 use state to render message
![alt text](image-112.png)![alt text](image-113.png)
- Now we have abliity to change value
## Varaition-2 create a button
![alt text](image-114.png)![alt text](image-115.png)
## Variation-2
![alt text](image-116.png)![alt text](image-117.png)![alt text](image-118.png)
- state is nothing but object which is privately maintain inside the component.
- It can influence what is render on browser.
- State can be change within component
# 11. setState
## Do's and Don't in state and setState
### Counter component we have count value and button to increment count value.
## Note:***Shortcut : - Type rce*** class component
![alt text](image-119.png)![alt text](image-120.png)![alt text](image-121.png)
###  count state  to track counter value
## Note: ***shortcut*** rconst for parmeterize constructor
![alt text](image-122.png)![alt text](image-123.png)
### Variation-1 write click event code
![alt text](image-125.png)
![alt text](image-124.png)
## Yaha hum state directly modify kar rahe hai.
## Note : ***Never modify state directly***.
- aap ***this.state*** sirf constructor mein initialize kar sakte ho
- uske alawa aap use karonge tab ***browser render nhi karbe***.
- aur kahi bhi aapko change karna hai state ko so use ***setState()*** method.
## Varaition-2
![alt text](image-126.png)![alt text](image-127.png)
## ***Do's Never modify state directly***
### Observation
![alt text](image-128.png)![alt text](image-129.png)
## Variation-3
- Isko hatene ke liye use callBack() function
- it's 2nd parameter to setState() method
- callback function is again arrow function
### Code
![alt text](image-130.png)![alt text](image-131.png)
## Do's ***Whenever you need to execute the code after state has been change, so don't place the code right after setState() method***
- Instead place within call function which is pass as 2nd arg to setState() method
## Complicate Scenario
### incremnet hona chaiye 0 to 5 jab bhi clk kare increment button
![alt text](image-132.png)![alt text](image-133.png)
## Imp:
- abhi aap previous state ke hisab se update nhi kar rahe..
- agar previous state ke hisab se update karna hai tab
- So pass function as argument to setState() instead of an object

![alt text](image-135.png)![alt text](image-134.png)![alt text](image-136.png)

- prvious State ke hisab se aapko calculate karna hai state tab pass function to setState() as argument instead of object
- yadi props bhi aaa raha hai aur usse add karna hai
### Code snippet
![alt text](image-137.png)![alt text](image-138.png)
# 12. Destructuring Props and State
![alt text](image-139.png)![alt text](image-140.png)![alt text](image-141.png)
## Destructuring props in functional Component
### in function parameter
![alt text](image-142.png)
### Destructuring in function body
![alt text](image-143.png)
## Destructur props in Class Component
![alt text](image-144.png)![alt text](image-145.png)![alt text](image-146.png)
### in render() you destructure it
![alt text](image-147.png)![alt text](image-148.png)
### Similary for state property
![alt text](image-149.png)
# 13. Event Handling
- When user Interacts with your application events are fired.
- mouse clk, mover hover, key press so on.
- your app able to handle such events and execute necessary code.
## Handle events in Functional Component
## ***Shortcut: type rfce***
![alt text](image-150.png)![alt text](image-151.png)![alt text](image-152.png)
- When user click on this button 
- clk event is fired 
### Target: to capture that clk event and execute the basic code
![alt text](image-153.png)![alt text](image-154.png)
## Common Mistakes
![alt text](image-155.png)![alt text](image-156.png)
### Problem with function call
![alt text](image-157.png)![alt text](image-158.png)
- button click kiye tab bhi, button clk console mein nhi aaya.
- Event handler ye function hai {function} and not the function call {function()}
## Event Handling in Class component
## ***Shortcut rce- class component***
![alt text](image-159.png)![alt text](image-160.png)![alt text](image-161.png)
### Adding event handler in class compnent
![alt text](image-163.png)
![alt text](image-162.png)
# 14. Binding Event Handler
### How to bind event handler in react component
#### knowledge of this keyword in javascript required
### Target: Clk on button and change the state
### rce - class component
![alt text](image-164.png)![alt text](image-165.png)![alt text](image-166.png)
### Create a state and bind it to UI
### rconst - for constructor(where state is initialilzed)
![alt text](image-167.png)![alt text](image-168.png)
### Change this message to GoodBye! when user click on button
![alt text](image-169.png)![alt text](image-170.png)![alt text](image-171.png)
### let's console this keyword
![alt text](image-172.png)![alt text](image-173.png)
- so this keyword in eventHandler is undefined..
- Typical behaviour of js
- so that's why event binding is necessary in event handler
### 1) Bind the handler in render() method
![alt text](image-174.png)![alt text](image-175.png)![alt text](image-176.png)
- badhiya hai small app ke liye
- but bade app ke liye nhi 
### 2) Use arrow function in render() method
![alt text](image-177.png)![alt text](image-178.png)
- having performance issue in some scenario
### 3) Binding the event handler in constructor
![alt text](image-179.png)![alt text](image-180.png)
- this is better since binding happens once in constructor
### 4) Arrow function as a class property
#### Basically change a way you define method in calss
![alt text](image-181.png)![alt text](image-182.png)
- 1st and 2nd approach sahi nhi
- 3rd approach better
- 4rth is expreimental feature.
# 15. Methods as props









