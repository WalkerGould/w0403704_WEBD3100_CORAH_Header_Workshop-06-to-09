Mini knowledge check (3 quick questions):


Why is aria-current="page" only on “Home”?

It shows that the current page is home.

Why use <nav aria-label="Main"> instead of just a <div>?

It helps with accessibility and narrator use, telling it this is main navigation.

Which elements in this header are decorative vs informational?

Separator. Most of it is informational, that's the point.



Micro reflection:

“What is one way this structure is clearer than a div soup?”

It has proper html structure and proper css selector use to work with the html structure.
Everything is clearly labeled.


Mini knowledge check:


Which parts of the layout are controlled by Flexbox vs media queries vs clamp()?

the root variables are controlled by clamp. e.g padding, 'link' button, etc.

display: flex and flex direction for example in the css .header-section-container
is controlled by flexblock but the clamps are called in a variable as well.

The media queries are set for nav container and header container to wrap
when the view port gets too small, to ensure proper responsiveness.



What happens to the nav links if the viewport becomes very narrow?

They wrap and stack as a column because of the media queries and flexboxes.


Micro reflection:

“What surprised you about how little CSS was needed to make this header feel modern and fluid?”

Not too surprised, just how easy the CSS selector language is.

Where is contrast strongest or weakest?

The highlighted buttons and logo corah name.

How do alignment and proximity help group related items (logo + wordmark, nav links)?

It provides a natural visual hierarchy structure that visually tells you 
items are grouped together.

Is hierarchy clear: brand first, then nav?
 
Yes. Branding is clearly visible from the first look of it.