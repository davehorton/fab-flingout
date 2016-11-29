[![Build status](https://travis-ci.org/davehorton/fab-flingout.svg?branch=master)](https://travis-ci.org/davehorton/fab-flingout)

# `<fab-flingout>`

A floating action button that flings out subsidiary buttons (i.e. speed dial)

[Demo and Docs](https://davehorton.github.io/fab-flingout)

## Using **fab-flingout** Element in your Project

Install this using bower

```
$ bower install fab-flingout --save
```

Add the element element using html imports

```
<link rel="import" href="../fab-flingout.html">
```

Example:
```    
<fab-flingout>
  <paper-fab icon="dns"></paper-fab>
  <paper-fab icon="add-alert"></paper-fab>
  <paper-fab icon="build"></paper-fab>
  <paper-fab icon="event"></paper-fab>
</fab-flingout>
```

Simply add `<paper-fab>` elements to the content of this element.  
A 'trigger' fab with an 'add' icon will initially display, and will animate to show the contained paper-fabs when clicked.

### Styling
The following custom properties and mixins are available for styling

Custom property | Description | Default
----------------|-------------|----------
`--fab-flingout-trigger-color` |  Color of the trigger floating action button |
`--fab-flingout-trigger-background-color` |  Background color of the trigger floating action button |
`--fab-flingout-color` |  Color of the contained floating action buttons |
`--fab-flingout-background-color` |  Background color of the contained floating action buttons |
`--fab-flingout` | Mixin for trigger floating action button | {}
`--fab-flingout-disabled` | Mixin for trigger floating action button, applied when button is disabled | {}
`--fab-flingout-content` | Mixin for contained floating action buttons | {}
