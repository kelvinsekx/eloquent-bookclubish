# What I learned using NextJS in a day

## _app.js
replaces the need to ever import wrapper components for pages

## Public directory
I had the need of where to place my bits reusable components. On a default CRA, I would have created a components directory in the public folder. But this is
highly expensive in NextJS. It is carefully written on the NextJS platform : "Only static files and assets should stay in the public folder"
https://nextjs.org/docs/basic-features/static-file-serving

## Donot create your components in the pages folder
https://stackoverflow.com/questions/53854104/is-this-next-js-folder-structure-recommended. Reading through 
the preceeding page would expose you to how expensive it is to put your components here too.
The best approach found is to create a separate folder for the components.

