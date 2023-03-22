# Coding Nomads JavaScript 201 Labs

**Important**: Do _not_ fork!

Go to the [cloning instructions](cloning.md) and follow the steps there to get set up.

## How to Go Through These Labs

You'll see the course structure mirrored in the `labs` folder. At the end of each corresponding chapter, you should do the labs in the folder.

Some folders don't have any labs, usually because that chapter was focused on building the module project.

Throughout the course there are "spoilers" and exercises for you to do. Place the results of those exercises in the [scratch folders](scratch) corresponding folders in your repository so that your tutor can look over your work.

### Present Your Solutions

For many of the exercises, you'll need to create corresponding HTML files so that the solutions can be loaded in a live server.

For example, say one of the chapter folders had three files:

```text

00_SAMPLE
├ 01 - exercises
│ ├ process data.md
│ ├ create table.md
│ └ special methods.md
│
...

```

You will generally only need to create one sandbox per chapter:

```diff

  00_SAMPLE
  ├ 01 - exercises
  │ ├ process data.md
  │ ├ create table.md
  │ ├ special methods.md
+ │ └ solutions
+ │   ├ solutions.html
+ │   └ script.js
  │
  ...

```

Though in some cases, you may be asked to create more sandboxes, and along with the sandbox you may need to complete the "spoiler" exercises, you could end up with many sandboxes per chapter:

```diff

  00_SAMPLE
  ├ 01 - exercises
  │ ├ process data.md
+ │ ├ process data
+ │ │ ├ process_data.html
+ │ │ └ script.js
  │ ├ create table.md
+ │ ├ create table
+ │ │ ├ create_table.html
+ │ │ └ script.js
  │ ├ special methods.md
+ │ ├ special methods
+ │ │ ├ special_methods.html
+ │ │ └ script.js
+ │ ├ mini project
+ │ │ ├ mini_project.html
+ │ │ └ script.js
+ │ └ chapter exercises
+ │   ├ chapter_exercises.html
+ │   └ script.js
  |
  ...

```

You will be told when you need to break out into new sandboxes. By default, you should start a `solutions` sandbox in each chapter.

If you have a few, keep things organized by keeping an `index.html` file at the top level with links to all your sandboxes:

```diff

  00_SAMPLE
  ├ 01 - exercises
+ | ├ index.html
  │ ├ process data.md
  │ ├ process data
  │ │ ├ index.html
  │ │ └ script.js
  │ ├ create table.md
  │ ├ create table
  │ │ ├ index.html
  │ │ └ script.js
  │ ├ special methods.md
  │ ├ special methods
  │ │ ├ index.html
  │ │ └ script.js
  │ ├ mini project
  │ │ ├ index.html
  │ │ └ script.js
  │ └ chapter exercises
  │   ├ index.html
  │   └ script.js
  |
  ...

```

The top level index file can then be populated with links, the `href` attribute can point to the folder, if the folder has a `index.html` file:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- ... -->
  </head>

  <body>
    <a href="process data">Process Data</a>
    <a href="create table">Create Table</a>
    <a href="special methods">Special Methods</a>
    <a href="mini project">Mini Project</a>
    <a href="chapter exercises">Chapter Exercises</a>
  </body>
</html>
```

Within each sandbox, you can optionally use the HTML to present the results of the labs, along with the console outputs.
