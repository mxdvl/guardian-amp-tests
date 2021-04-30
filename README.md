[![Netlify Status](https://api.netlify.com/api/v1/badges/60e62081-81bc-4896-9567-559b55fbd55c/deploy-status)](https://app.netlify.com/sites/guardian-amp-tests/deploys)

# The Guardian’s AMP tests repo
Make it easy to get test AMP URLs that can be shared.

The `main` branch is automatically [deployed to Netlify](https://guardian-amp-tests.netlify.app/).

## How to add a new test page

1. Generate an AMP page, [locally](#local-amp-page) or [from PROD](#prod-amp-page)
3. Save the resulting HTML to this repo
4. Make the required changes to the HTML

### Local AMP page

1. Clone the [`dotcom-rendering`][] repo
2. Navigate to an `AMPArticle?url=…` page

### PROD AMP page

1. Go to an article on The Guardian
2. Change `www.` to `amp.` to get the AMP version



[`dotcom-rendering`]: https://github.com/guardian/dotcom-rendering
