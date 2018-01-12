# JavaScript

## Libraries and code snippets
[`shortcuts.js`](http://www.openjs.com/scripts/events/keyboard_shortcuts/) - A small and easy-to-use library which can be used to implement keyboard shortcuts.

## Nuggets and Advice
- **Dispatching a [`MouseEvent`](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent) or [`.click()`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/click) not working for an element?** - Try to make the event bubble so event listeners in ancestral nodes can catch the event and do something. Example to create a bubbling event: `new MouseEvent('mousedown', {bubbles: true})`
