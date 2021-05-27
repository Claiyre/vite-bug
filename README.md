# vite-demo

This demo is for reproducing a vite bug (visiting dev server url with query string ending with '.js' will cause vite internal error)

## steps

1. `npm install`
2. `npm run dev`
3. visit `http://localhost:3000/?test=aa.js`(note whether the port number is correct!)
4. internal error in terminal