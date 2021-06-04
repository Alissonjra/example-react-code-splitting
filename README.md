# Improving the performance of React applications using Code Splitting

> Example using lazy and suspense of react and magic comments webpack.
 
## Repo
> Using this example repository to apply the concepts.
 - [Repo](https://github.com/flatlogic/react-material-admin)

## Getting started:
 - `
 yarn
 `
 - `yarn start`


## Analyze your bundle:
 - `yarn run build:analize`
 - `yarn run build -- --stats && npx webpack-bundle-analyzer build/bundle-stats.json -m static -r build/bundle-stats.html -O`

## More details:

 - [Doc react](https://reactjs.org/docs/code-splitting.html)
 - [Webpack: Bundle Analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer)
 - [Webpack: Bundle Analyzer + Create React App](https://github.com/facebook/create-react-app/issues/3518#issuecomment-454144586)
 - [Webpack: Magic Comments](https://webpack.js.org/api/module-methods/#magic-comments)
 - [Webpack: Preloading/Prefetching](https://webpack.js.org/guides/code-splitting/#prefetchingpreloading-modules)
 - [JavaScript Start-up Optimization](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/javascript-startup-optimization)


