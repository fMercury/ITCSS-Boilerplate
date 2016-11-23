# ITCSS Boilerplate


## Intro

This boilerplate structures a SASS codebase following the [ITCSS principles](https://speakerdeck.com/dafed/managing-css-projects-with-itcss). It includes two different reset options (full reset and normalize) and two optional grid systems, bootstrap's and [flexboxgrid](flexboxgrid.com) (both with similar class names).

It also has some predefined styles based in the [Skeleton framework](getskeleton.com).

The class names of the incuded styles are based in the [SUIT naming convention](https://github.com/suitcss/suit/blob/master/doc/naming-conventions.md) (similar to BEM).


## Structure

The styles are separated according to their pourpose.

1. **Settings**: Global variables, config switches.
2. **Tools**: Default functions and mixins.
3. **Generic**: Ground-zero styles (normalize.css, resets, box-sizing).
4. **Base**: Unclassed HTML elements (type selectors).
5. **Objects**: Cosmetic-free design patterns.
6. **Components**: Designed components, chunks of UI.
7. **Trumps**: Helpers and overrides.


## Settings

There are two reset options and two alternative grid systems to choose from. The settings can be changed in `_settings.scss`.


## Gryd Systems

The two grid systems are optional
- "Bootstrap", is the exact grid system that comes with bootstrap.
- "Flexboxgrid", is similar to use but based on the flex display property so it has some additions like the posibility to reorder or change the alignment of the the columns.


## Base Styles

The styes included by default in the boilerplate are based in the Skeleton framework.
