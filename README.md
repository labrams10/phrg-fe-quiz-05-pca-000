# Responsive Sites and CSS3 Media Queries

???

# Responsive Layout Quiz

?: Responsive site layouts are ideal because they allow for the creation of a single site as opposed to multiple iterations each tailored to a specific device's layout.

(X) TRUE
( ) FALSE

?: What is another term for the 'modern-first' approach to creating responsive websites in which the site is first designed to look and function the best on newer browsers, but still provide functionality and compatibility for older browsers?

( ) progressive enhancement
( ) mobile-second development
(X) graceful degradation
( ) regressive enhancement

?: What is another term for the 'mobile up' approach to creating responsive layouts, in which the site is first designed to fit mobile devices and is then scaled up for larger screens?

(X) progressive enhancement
( ) mobile-second development
( ) graceful degradation
( ) regressive enhancement

?: Each CSS3 media query may only be given one conditional expression to evaluate.

( ) TRUE
(X) FALSE

?: A `meta` tag with the name of `viewport` allows us to set the device width, initial scale, and maximum scale, so we can disable zoom in the browser.

(X) TRUE
( ) FALSE

?: Select the most appropriate CSS media query statement to change the `#wrapper` selector's `width` value to `90%` on `screen` devices not wider than 1024px.

( ) `@media only screen and (min-width: 1024px) { #wrapper { width: 90%; } }`
(X) `@media only screen and (max-width: 1024px) { #wrapper { width: 90%; } }`
( ) `@media all and (min-width: 1024px) { #wrapper { width: 90%; } }`
( ) `@media print and (max-width: 1024px) { #wrapper { width: 90%; } }`

?: Select the most appropriate CSS media query statement to change the `font-size` of `nav` elements to `1.5em` when the screen is between 480 and 1024px wide on any type of device.

( ) `@media only screen and (min-width: 1024px) { nav { font-size: 1.5em; } }`
( ) `@media (min-width: 481px) and (max-width: 1023px) { nav { font-size: 1.5em; } }`
(X) `@media all and (min-width: 480px) and (max-width: 1024px) { nav { font-size: 1.5em; } }`
( ) `@media print and (min-width: 480px) and (max-width: 1024px) { nav { font-size: 1.5em; } }`

?: Select the most appropriate CSS media query statement to set `section` elements to stop floating on `screen` devices with an available width of 480px or less.

(X) `@media only screen and (max-width: 480px) { section { float: none; } }`
( ) `@media (min-width: 480px) { section { float: none; } }`
( ) `@media all { section { float: none; } }`
( ) `@media only screen and (width: 480px) { section { float: none; } }`

?: It is important to make media elements (e.g., `img`, `form`, `input`, `table`, `video`, `audio`, and `iframe`) responsive by setting their `width` and `max-width` properties to `100px`.

( ) TRUE
(X) FALSE

?: Select the most appropriate CSS media query statement to split the paragraph text in `article` elements into two columns on `screen` devices that are at least 480px wide.

( ) `@media only screen and (max-width: 480px) { article p { column-count: 2; } }`
( ) `@media only print and (min-width: 480px) { article p { column-count: 2; } }`
( ) `@media only screen and (min-width: 480px) { article p { number-of-columns: 2; } }`
(X) `@media only screen and (min-width: 480px) { article p { column-count: 2; } }`

?: Assuming the `font-size` property for `body` elements is set to `100%`, for `h1` elements to `2.5em`, and for `p` elements to `1em`, select the most appropriate CSS media query statement to proportionally double the `font-size` of both `h1` and `p` elements on `screen` devices no more than 400px wide.

( ) `@media only screen and (max-width: 400px) { h1, p { font-size: 5em, 2em; } }`
( ) `@media all and (max-width: 400px) { body { font-size: 2em; } }`
(X) `@media only screen and (max-width: 400px) { body { font-size: 200%; } }`
( ) `@media only screen and (max-width: 400px) { html { font-size: 200%; } }`

???

## Does this need an update?

Please open a [GitHub issue](https://github.com/learn-co-curriculum/phrg-fe-quiz-05-pca-000/issues) or [pull-request](https://github.com/learn-co-curriculum/phrg-fe-quiz-05-pca-000/pulls). Provide a detailed description that explains the issue you have found or the change you are proposing. Then "@" mention your instructor on the issue or pull-request, and send them a link via Connect.

<p data-visibility='hidden'>PHRG Responsive Sites and CSS3 Media Queries</p>
