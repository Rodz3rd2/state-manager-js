# State Manager JS

Handle state of user action is quite difficult ... State Manager JS to the rescue!

State Manager is a jQuery plugin that handle all possible(I think) user action.

## Options

- enabledStateLogs (boolean) - To see in logs what the current and previous state user does.
- beforeLeave (function) - Trigger before leave of the current state.
- leave (function) - Trigger on leave of the current state.
- afterLeave (function) - Trigger after leave of the current state.
- beforeLoad (function) - Trigger before load of the current state.
- load (function) - Trigger on load of the current state.
- afterLoad (function) - Trigger after load of the current state.

## Usage

```js
$(selector).stateManager({
    enabledStateLogs: true, // enable logs

    beforeLeave: function() {
        // code
    },
    leave: function() {
        // code
    },
    afterLeave: function() {
        // code
    },
    beforeLoad: function() {
        // code
    },
    load: function() {
        // code
    },
    afterLoad: function() {
        // code
    },
});
```

## LICENSE

State Manager JS is released under the MIT Licence. See the bundled LICENSE file for details.
