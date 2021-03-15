# Life Cycle

A component represents an object or content in the game such as screens, menus and all other visual or structural elements.

## Mounting Cycle

The life cycle of an component follows the Mounting cycle for actions.

The mounting cycle has 3 steps:

1. Setup - Here the action needs to set up everything it will need for working generally, in this section a component will generally add its HTML content to the global Monogatari object and will set up any needed configuration or state variables.
2. Bind - Once the component has been setup, its time to bind all the necessary event listeners or perfom more operations on the DOM once all elements have been setup. Components will generally bind all the listeners needed for their inner elements to work correctly.
3. Init - Finally, once the component was setup and it performed all the needed bindings, it may start performing its operations and perform all further needed operations.

