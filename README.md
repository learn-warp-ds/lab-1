>  Warp Field Guide

# Lab 1

Goals for this lab:
- Become familiar with utility classes
- Get a better idea of the output from each utility class
- Gain an early understanding of what a component built using utility classes looks like
- See the documentation for Warp's CSS

*Note: This lab has additional non-semantic classes enabled that will not be available in Warp - e.g. `bg-blue-500`*

## Part 1

Go to the Github Page for this lab, you should see a playground site that greets you with "Hello Warp!".

- The upper-left is a textarea that can be edited with your HTML
- The lower-left is the CSS generated given your HTML
- The right side is an `iframe` with the result
  - Note that for breakpoints (e.g. 480px), these will occur on the width of the `iframe` and not the width of the whole page!

### Notes:

- All of this functionality should work together, so f.ex completing the 2nd bullet point should not cause the 1st one to break!
- For now, don't worry about accessibility - e.g. when you open the page you can see we've abused `h1` tags just to get the right size text 🙈
- For this part, you'll be focusing on the first `section` and its content
- The documentation on [breakpoints](https://warp-ds.github.io/css-docs/class-variants#breakpoints-and-media-queries) is relevant for completing these tasks

### Tasks:

1. Make it so that on **mobile** screens "Hello Warp" is stacked on top as shown [here](/.github/assets/task-1-1.png?raw=true)
2. Make changes so that on **tablet** screens the word "there" appears between "Hello" and "Warp" as shown [here](/.github/assets/task-1-2.png?raw=true)
3. 'Improve' the **desktop** version so "Hello" and "Warp" appear above and below each other as shown [here](/.github/assets/task-1-3.png?raw=true)
    - You'll need to modify the height of the section element for this to work

## Part 2

You'll work from the same Github Page for this lab. If you nuked the button section, or would like to start fresh you can use [this link](https://learn-warp-ds.github.io/lab-1?html=DwCwTABAxgNghgZwQXgEQFsAuBaAzGVAPgE0B7AVwCcIAjczTUgOwhAFNK2JBeDcHEd4APThCAKGAI2UTAEtm0eEjQAHPJBqlKAEw5ERECMDoNmhAMIxpUANYR0bQUcZNRgiVNnOgA)

### Notes:
- You can refer to available colors [here](https://tailwindcss.com/docs/customizing-colors). As mentioned above, these aren't available in Warp, but are more fun to use when learning!
  - Setting background (e.g. `bg-blue-500`), text (e.g. `text-blue-500`), and border (e.g. `border-blue-500`) should all work using these colors.

### Tasks:
1. Make the button look like a button from your favorite brand!
2. Give your button `hover`, `focus`, and `active` effects.
    - Pseudo-classes work similiarly to breakpoints in the previous lab - `hover:bg-blue-500` will assign that background-color when the element is hovered.
    - Pseudo-classes can be combined with breakpoints! `hover:lg:bg-blue-500` will assign that background-color only on desktop sized screens and when the element is hovered.
