## v0.3.7
- 80aa0df: fixed #25 and #36
- 70411fd: fix object check in ie (#35) (thanks @judge)

## v0.3.6

- 83a990b: fixed #34

## v0.3.5

- c1c4168: fixed #33, error when trying to create a popper inside a `form` element.

## v0.3.4

- 7e98c14: fixed destroy method
- d811684: **BREAKING CHANGE**, renamed `trigger` to `reference`, you can now access `data.offsets.reference` instead of
    `data.offsets.trigger`, and `this._reference` instead of `this._trigger`.

## v0.3.3

- 1782c39: fixed #21, problem with position of poppers when inside `fixed` parent.

## v0.3.2

- 592f4c7: revert iOS fix (it wasn't effective) - it should have fixed the repaint problems of fixed poppers during scroll  
    I'm still looking for a working fix.

## v0.3.1

- b0d77ff: don't apply x-placement attr if applyStyles modifier is disabled

## v0.3.0

- 5521b0d: added support for integration with React.js and Ember.js.  
    Now popper.js will allow you to disable DOM modifications and exposes an `onUpdate` callback you can use to export the
    popper coordinates in your framework.

## v0.2.6

- 6732353: removed shared state;

## v0.2.5

- 77677f0: round top and left coordinates to prevent blur effect;

## v0.2.4

- 35bbbc6: fixed position on scroll of `fixed` poppers on Safari Mobile;

## v0.2.3

- 7a0ae40: Fixed Git URL of NPM package;

## v0.2.2

- 2a9b804: Fixed troubles with positioning when the reference element is placed inside a relative parent and the popper is placed inside the body;
