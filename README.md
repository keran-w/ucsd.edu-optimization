# UCSD-Site-Clone

Creating a static clone of UCSD website and optimizing for performance and accessibility

Original homepage: [https://ucsd.edu/](https://ucsd.edu/)

New homepage deployed on [netlify](https://phenomenal-sopapillas-1546c3.netlify.app/)

## Lighthouse Reports

[Original homepage Lighthouse Report](
https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fucsd.edu%2F&strategy=desktop&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext)

[New homepage Lighthouse Report](
https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fphenomenal-sopapillas-1546c3.netlify.app%2F&strategy=desktop&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext)

## Metrics

- Performance score: 39 -> 54
- First Contentful Paint: 3.3 s -> 2.0 s
- Largest Contentful Paint: 7.3 s -> 2.9 s
- Cumulative Layout Shift: 0.411 -> 0.41
- Speed Index: 3.3 s -> 2.0 s

## Fixes

- Compress all images with [tinypng](https://tinypng.com/)
- Remove document.write
- Remove some unused CSS files
- Update links to static resources if the file is available
- Compress large CSS files [cssminifier](https://www.toptal.com/developers/cssminifier)
