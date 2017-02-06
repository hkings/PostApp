# Post APP


We go into the directory and install npm and bower dependencies and set up gulp.

```
cd node-express-mongo-bower-gulp-template
npm install && bower install && gulp
```

Now that we have all the files, to develop on this template locally, you should have 5 terminals/terminal tabs open.

- 1st terminal: `mongod --dbpath data/`
- 2nd terminal: `mongo`
- 3rd terminal: `gulp watch`
- 4th terminal: `npm start`
- 5th terminal: `Extra terminal for miscellaneous commands.`

After running `npm start`, you can open a web browser and visit [http://localhost:3000](http://localhost:3000) to see your locally developed website.
