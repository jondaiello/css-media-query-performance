# CSS Media Query Performance

This repository is to document different methodologies of utilizing CSS @media queries and then testing their performance against each other.

### The goal

> To provide performance statistics on load times, rendering times and server latency issues on both mobile and desktop sizes.

The HTML to be rendered will remain largely unchanged, however we may include CSS via a &lt;style&gt; for testing purposes. Content may also change to help example what methods are being tested.

### Methodologies for testing:
* All CSS in one file with media queries grouped together.
* CSS files broken out into different media queries.
* CSS inside &lt;style&gt; element on the page

The methods above will be tested utilizing min-width (mobile first) and max-width approaches.
