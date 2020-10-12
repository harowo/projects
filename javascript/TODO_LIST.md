# Javascript / ToDo List

In this project, you will be creating a super simple todo list application using vanilla JavaScript! All the application needs to be able to do is add, remove, and complete todos. You can achieve this using any means necessary.

## Hint(s)

**ID's:** To remove and complete todos, you need to be able to fetch them using DOM, a good way to do this is by assigning each todo an ID, a good way of doing this is with the `Date.now()` method. Adding an ID to an element is simple, just set the `id` attribute to `your_ID`, here's how you can do it with DOM:

```js
let element = document.createElement('p');
let text = document.createTextNode('This element has an ID!');
element.appendChild(text);

let id = Date.now()

element.setAttribute('id', id);
document.body.appendChild(element);
```

Submitted by Sqwyer

Edits: *None*
