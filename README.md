# tinkerfestival-web

## Basic usage
just clone/fork this repo, enable github pages for the forked repo and go ahead.

## modifying 
tinkerfestival-web uses vuetifyjs (also vue.js) for content delivery. 
Please have a look at (https://vuetifyjs.com/en/getting-started/quick-start)[vuetify] for additional details on theming with vuetify, for general porpuse just look up the vue.js documentation at (https://vuejs.org/v2/api/)[vue.js].

## Icons:
(https://materialdesignicons.com/)


## Add right forms id:
Create a google form, click send and copy the embedded form, i.e.
`<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScA0dGYLIS44WV0sVbh1tXQFnug-BnDESKDEeZpdUjDTPqdZLA/viewform?embedded=true" width="640" height="991" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>`

Extract the id from the embedded link, behind the slash after "e", before the next slash, i.e. `1FAIpQLScA0dGYLIS44WV0sVbh1tXQFnug-BnDESKDEeZpdUjDTPqdZLA`. Place the id in the variable for `signUpForm`
