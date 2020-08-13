## Reading Day: 09

## Forms
Forms are the input areas of a web page and collect data from users. Names, Passwords, addresses and Text areas to write a note or share a story are all examples of how forms are used. Forms work when a user typically fills out a form and then presses an enter button. There are different types of selections that include text inputs, radio buttons, drop down selections and numerical inputs.

**When a user fills out a form,** 
1. The values are sent to the server.
1. The server processes the values using a programming language.
1. The server creates a new page based on the user input.

Each Form field is assigned a name so the data can be accessed through programming languages through the server. Input types can be detailed and styled using **label, fieldset and legend** tags. Fieldset allows you to group related form controls together and is helpful for longer forms. As I read about these tags I thought about ultimately what we all want to experience is interfaces that are intuitive and make sense. Some forms have form validation which ensures the user enters information that the server will understand.

## Lists, Tables, and Forms
I remember designing web pages years ago where tables were used to organize the content and layout. What a nightmare!
We're still using tables but not so much for page layout. We're able to design and style tables with font size, text align, table headers and footers, padding and background colors, border radius. Table cells can be spanned to create larger spacing or divided into smaller cells.

## Aligning form controls
Forms have been very confusing to design in the past. I wished I would have had CSS3 and HTML 5 and this book 10 years ago. The float property makes aligning and styling form controls much easier.

## Web Developer Toolbar
To see styles and HTML structure of a web page, you can got to the CSS menu of the Web Developer Toolbar and select *View Style Information*. This makes it really easy to see how a browser views your code.

## Events
Events happen when a user triggers a function in a web page. A page load, clicking on a link, scrolling through a web page and selecting an option all represent events. 
These things happen when you browse the web: 
- Interactions create events
- Events trigger code
- Code responds to users

Events Trigger javascript code by first triggering a function, say when a user clicks on a link. Then a selected **node** in the DOM model will trigger a response. Code is then run when the event occurs.

## The DOM
The other day I read about the **Document Object Model** for the first time. Being a visual person, this model really makes sense and using the elements and DOM nodes to attach functions. I think of it now like 'the nervous system' of a web page.  

## Event Listeners
Event listeners takes three properties:
1. The event you want it to listen for
1. The code that you want it to run
1. A boolean indicating how events flow

## Event Flow
Here is something I hadn't thought too about too much before. When you are interacting with a web page, there are layers that you are touching. Not only are you hovering over a link but you are also clicking on a parent element also. The flow of events only really matter when your code has event handlers on an element and its ancestor or descendant element. Or you have a 'dumb' web page.

## Event Object
When an event occurs, an event object gives you information about the event and element it happened on. Again I'm thinking of the 'nervous system' analogy.

## Events
I found it interesting to read about all the different events that I hadn't considered such as 'events' such as mouse position, keyboard and key input. 
Events are grouped in 3 categories of:
- W3C DOM events,
- HTML5 events
- Browser Object Models events

## Mutation Events
Whenever elements are added to or removed from the DOM, the structure changes and triggers what is called a 'mutation event'.







[<== Back to Table of Contents](index.md)