# Lecture slides

These slides have been created using [reveal.js](https://revealjs.com/), an open-source HTML presentation framework. Aside from being a tool that I'm familiar with, I felt this would work well as something easily sharable on GitHub. To present using the existing HTML files (which I recommend), download the entire `slides/` directory as-is, navigate to the relevant folder, and open `index.html` in your browser of choice. Pressing `S` on your keyboard with the presentation open will open a Speaker View window, with notes and a timer that should be familiar to users of PowerPoint or Google Slides.

## Individual folder contents

### Presentation folders

Most of the folders contain individual presentations and are labeled with a class number (e.g., "c02" for Class 2) and the theme of the slide deck. Each presentation folder contains an `index.html` file, which is the presentation itself, and a `img/` folder, which contains any images specific to that presentation. Each folder also includes a PDF version of the presentation, which some users might prefer.

If you have some basic understanding of HTML you probably know enough to make changes to the presentations' `index.html` files in order to adjust the content to suit your own purposes. The reveal.js website provides [pretty robust documentation](https://revealjs.com/markup/), and I'd encourage having a look at that if you'd like to adjust the content of the slides.

### Supporting files

The `slides/` directory also contains the `reveal/` and `css/` folders, which contain files essential to the formatting of the slide decks but do not affect the content of the slides themselves. I update the contents of `reveal/` directly from the [reveal.js](https://github.com/hakimel/reveal.js) repository and don't mess with it (aside from removing unused files).

I've mostly put together the files in `css/` myself, so feel free to adjust as you see fit. It contains a CSS file for each presentation that requires one, and the file `theme.css` determines the consistent style of the presentations. It is based on the the `serif.css` file distributed with `reveal.js`.