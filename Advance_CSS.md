Critical Render Path
    - a path that a website takes to display something to the user.

CSS - Render(display) blocking file meaning you won't be able to render a webpage until you receive the CSS.

CSS Minify => makes you css file size smaller.
    https://www.cleancss.com/css-minify/

CSS Tricks =>
    https://css-tricks.com/
    https://css-tricks.com/snippets/

Flexbox froggy => site to practice flexbox
    https://flexboxfroggy.com/

CSS 3 => latest version of CSS

    New addition:
        transition:
        transform:

    Previous version of CSS you need to use the following to render box-shadow.
    -mz = mozilla browser
    -ms = Microsoft Edge browser
    -webkit = Chrome & Safari browser
    -o = opera browser

    visit
    https://caniuse.com

Transitions and transform
    transition-property: [property]; <!-- all, width, height, background etc., -->

    transition-duration: [duration in ms or sec];

    transition-timing-function: [timing-function];
        ease: gradually speeds up and gradually slows down.
        ease-in: gradually speeds up.
        ease-out: starts abruptly then gradually slows down.
        ease-in-out: gradually speeds up and slows down at the end.
        linear: constant speed.
    
    transition-delay: [duration of delay];

Shorthand transition

    transition: [property] [duration] [timing-function{optional}] [delay{optional}]
        ex. div {
                div:hover & {
                    transform: translateX(200px);
                }
            }

            div {
                transition: all 2s ease-in-out 1s;
            }

CSS Grid:

 fr => fraction of the free space of the grid container.