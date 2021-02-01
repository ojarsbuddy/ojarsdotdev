# ojarsdotdev

Changes to repository `ojarsdotdev` will trigger an AWS Amplify deployment to [ojars.dev](https://www.ojars.dev/).

## The new St. Andrews project

Let's clean sheet a new website. Once it is well along, production code can go into `~/dev/standrews`.

- Using CSS variables.
- Using the `picture` element rather than the `figure` element.
- Using flexbox.

## Kevin Powell Methods

Kevin likes to start off his css with

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}
body {
  margin: 0;
}
```

## Links are tricksy

Here is how I got the `visited` state to behave.

```css
a {
  text-decoration: none;
}
a:link {
  text-decoration: none;
}
a:visited {
  color: var(--font-color);
}
a:hover {
  cursor: pointer;
}
a:active {
  text-decoration: none;
}
a:focus {
  text-decoration: none;
}
```

## Notes

The `small` tag works better inside the paragraph element.
