# <i>n</i><sup>2</sup>&nbsp;&minus;&nbsp;1 Sliding Squares Puzzle

This is a video-game implementation of the
[15-puzzle](https://en.wikipedia.org/wiki/15_Puzzle),
8-puzzle, or more generally,
any <i>n</i><sup>2</sup>&nbsp;&minus;&nbsp;1 puzzle,
a sliding-block puzzle
featuring an <i>n</i>&times;<i>n</i> grid of squares,
where all but one square has a unique block.

## Technology

This implementation is written in the
[Civet](https://github.com/DanielXMoore/Civet) programming language
using the [Solid](https://solidjs.com) web framework,
[Vite](https://vitejs.dev/) bundler, and
[Vitest](https://vitest.dev/) testing framework.

Most notably, it uses
[CSS transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_transitions/Using_CSS_transitions)
to achieve smooth animations of piece slides.

## Local Development

```bash
$ pnpm install # or npm install or yarn install
```

Then you can use the following scripts:

### `pnpm dev` or `pnpm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.<br>
The page will reload if you make edits.

### `pnpm run build`

Builds the app for production to the `dist` folder.<br>
Bundles Solid in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `pnpm test`

Runs some built-in tests in Vitest.
