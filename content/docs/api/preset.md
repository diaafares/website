---
title: 'Preset (object)'
sidebar: 'docs'
prev: '/docs/api/context/'
next: ''
---

## Preset

This is the reference for the `generator` object that you pass to `Preset.make()` if you are using the object syntax.

## Properties

### `name`

- **Type**: `string`

The name of the preset. This name is displayed in the output of the console when the preset is applied.

### `templates`

- **Type**: `string`
- **Default**: `templates`

The path to the directory that contain the templates, relative to the root of the preset project.

### `actions`

- **Type**: `(context: Context) => Action[]`

A method that takes the context as a parameter and return a list of actions.

### `parse`

- **Type**: `object`

A method that indicates how to parse extra command line arguments.

### `before`

- **Type**: `(context: Context) => void`

A callback that is executed before the actions start to be executed.

### `beforeEach`

- **Type**: `(context: Context) => void`

A callback that is executed before an action is executed.

### `after`

- **Type**: `(context: Context) => void`

A callback that is executed after the actions have been executed.

### `afterEach`

- **Type**: `(context: Context) => void`

A callback that is executed after an action is executed.