# Frontend Layout Exercise Solution

## Explanation:

Since the primary goal of this exercise is to produce the layouts quickly and
efficiently, we "pre-create" the pieces in advance so that all that needs to be
done is to compose them later.

Each layout is made up of between 3 and 6 "boxes". These are block elements with
unique colors placed in a row, column, or grid.

Normally, we think of a grid as having at least 2 rows and 2 columns, but to make
things easier here, I consider everything as a grid layout.

Each layout will be its own grid, defined by composing "boxes".

The body itself is a grid of the layouts, so it needs to be styled as well.

It's a good practice to save incremental changes as separate commits, that's 
how we'll do it here, too.

Note that we assume here that we just need to get this done. Refactoring the
project structure (like moving things into folders) is left for another time.

How you like to use git is up to you. In this solution, I will use the cli.

It is important to note that in the interests of saving time, the markdown will
be as simple as possible, so that it is easy to create. I will be using
emmet to save a lot of time and keystrokes as well.

## Solution

### Scaffold the Project
1. create the project directory: `mkdir -p project && cd project`

2. initialize a new git repo: `git init .`

3. create a README.md for your project: `echo "Layout Exercise" > README.md`

4. create the html file: `touch index.html`

5. create the css file: `touch site.css`

6. open the html file in vscode: `code index.html`

7. using emmet, create the initial html:

   ![scaffold html](img/create-html.gif)

8. link the stylesheet:

   ![link the stylesheet](img/link-the-stylesheet.gif)

9. create the reset style and make sure that everything works using live server:

    ![make sure the stylesheet works](img/make-sure-stylesheet-works.gif)

10. commit: 
```
   git add -A
   git commit -m 'initial commit'
```

### Style the <body> and commit
   
   ![style the body](img/style-the-body.gif)


### Create Reusable Pieces
1. default all divs to be display: grid with a white background so that grid holes are visible



2. create a box class that centers its own contents, has a default background,  and has an outline

   Note: use outline instead of border to prevent double borders

3. create styles for specific child divs 1 through 6. We only create 6 because that's the most that any of these layouts need.

![create css foundation](img/create-css-foundation.gif)

### Create Layout1

1. HTML
2. CSS
3. Commit

![create layout 1](img/create-layout-1.gif)

### Create Layout2

1. HTML
2. CSS
3. Commit

![create layout 2](img/create-layout-2.gif)

### Create Layout3

1. HTML
2. CSS
3. Commit

![create layout 3](img/create-layout-3.gif)

### Create Layout4

1. HTML
2. CSS
3. Commit

![create layout 4](img/create-layout-4.gif)

### Create Layout5

1. HTML
2. CSS
3. Commit

![create layout 5](img/create-layout-5.gif)

### Create Layout6

1. HTML
2. CSS
3. Commit

![create layout 6](img/create-layout-6.gif)
