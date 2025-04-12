# Recipe

This is a webpage for handling the Markdown recipes in https://github.com/caryguan/Recipes to display. It uses Marked to convert Markdown Files to HTMl and display and Vite as the front end and handling.

This samples from 
* https://github.com/tanabe/markdown-live-preview
* https://github.com/markedjs/marked

# Running
We use a Makefile to do most of the running

### Dev
```
make dev
```

### Build
1. Clears old folders
2. Installs npm dependencies
3. Pull latest gitsubmodules
4. Runs build
```
make build
```

### Deploy
Requires all files to be committed. 
1. Clears old folders
2. Installs npm dependencies
3. Pull latest gitsubmodules
4. Runs build
5. Deploys to github repository
```
make deploy
```

Alternative, npm commands can be used
* For development: `npm run dev`
* to build: `npm run build`, creating the dist/ folder