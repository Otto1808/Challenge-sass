# Title: SASS:

- Repository: `challenge-sass`
- Type of Challenge: `Learning Challenge`
- Duration: `1/2 day`
- Deployment strategy : `Github page`
- Team challenge : `solo`

## Learning objectives

- Being able to explain what a CSS-Preprocessor is
- Generate some CSS from your CSS preprocessor (SASS)
- Being able to minify your CSS output
- Knowledge of the following SASS features:
  - Variables
  - Mixins (Functions)
  - Nesting
  - Partials & Import
  - Extend/Inheritance
  - Operators (Math)

> 📜 Reminder : [**Slides about Sass (in French)**](https://docs.google.com/presentation/d/1wJn5m84TJmlZ5IRWUsY8HS2vuWSB7VkwS0jjnuWpMWM/edit?usp=sharing)

## The Mission

Your mission is to rewrite the example.css to a scss file with the following changes:

### Part 1

- Nest the styling rules of grouped elements, like the sections in the _Article_ or the `<p>` in the class `messages`.
- Create variables for all the colors.
- Make use of extend to re-use the same CSS for the "success", "error" and "warning" messages.
- For the "error" message, change the background in green when you hover it. Use the nested syntax.

### Part 2

- Make the general padding the same everywhere with one variable. But there are 2 execeptions :
  - The `main` should have a padding-top and padding-bottom to 0.
  - The `footer h3` should have double the padding of the other elements. Use "operations" to do this. Do NOT hardcode the padding inside your scss.
- Make one mixin for the 3 lines of the box-shadow styling using the color as a argument.
- Write all your variables in a partial file and link it to the main file.

### Part 3 - the tricky part! (optional)

- With the list of advantages (class "advantages"), create a gradation of color for the background and the text color. For it, you have to use a loop @for : [here the documentation](https://sass-lang.com/documentation/at-rules/control/for)

## Sassentional !

![sass](sass.gif)
