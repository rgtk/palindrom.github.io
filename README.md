# Website

This website is created with React. Minimal React knowledge might be needed in order to modify it.

## Why `source` branch is the main branch?

To have a website that is on `org.github.io` and not `org.github.io/websites-repo` you need to have HTML files in `master` branch. To keep the source close to the website itself (HTML files) I created `source` branch that has the React app's source. You can build the app into `master` instead of `gh-pages`, typically.

## Contribution

### Method I - Preferable

1. Add an issue with your suggestions.

### Method II

1. Clone this repo.
2. Run `npm install` to install the deps.
3. Run `npm start`.
4. Navigate to `localhost:3000` (probably, `npm start` will do that automatically for you).
5. Hack what you need to hack.
6. Run `npm build`.
7. Commit your changes to a feature branch if needed, or to `source` branch directly if not.
8. Run `npm run deploy`.
9. NOTICE: step 8 actually publishes the website to the wild. Deploy with a little caution.

## Why React?

No production-related reason. But the development cycle is a big time savor.

## License 
MIT
