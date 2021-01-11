# How to Code Like a Pro

These are some notes that I take from the Dylan C. Israel's video from FreeCodeCamp.

### Why?

Because your code needs to look like you **care**.

Your code had to be:

- **Searchable**.
- **Readable**.
- **Understandable**.

First of all use linters because yo get:

- More redabilty.
- Catches syntax errors.
- Automation.

## Variables

- The less variables the better.
- The name should be what it does, not how it does.
- The name should be short if the scope of the variable is short.
- The Object variables shouldn't have the object name as a prefix, (e.g. Object *Cat* has *name* and *age*, but no *catName* and *catAge*).
- Don't use "*magic numbers*", use a variable for some, example:

```
// Don't let this number due to you can forget what it is.

...
const c = Math.pow(6367.4447 + obj.avgAlt, 3)
...

// Use instead a variable:

...
const earthRadius = 6367.4447
const c = Math.pow(earthRadius + obj.avgAlt, 3)
...
```

## Functions

Functions should be verbs, actions that are happening.

- Small functions.
- Eliminating boolean flags.
- Reads top to bottom.
- Correct function naming.
- Limiting parameters.
- DRY.
- Avoid globals.
- Avoid side effects.

## Comments

#### What makes comments BAD?

- Comments used when they are unneeded.
- Comments are typically used to explain bad code.
- Commented code.
- Visual Markers.
- TODOs.

#### What makes a GOOD comment?

- Short and concise.
- Provides value.
- Clarifies code that a business purpose but looks out of sort.
- Sometimes a warning or aplification of importance.
- Legal comments.

## SOLID

- Single responsibility principle.
- Open closed principle.
- Liskov substitution principle.
- Interface segregation principle.
- Dependency inversion principle.