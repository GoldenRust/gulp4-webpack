# Gulp 4 with Webpack
This is the demo repo for the [CSS Tricks article]().

## Test HMR
To test **Hot Module Reloading** switch to the `hmr` branch and run `npm install` again.

Demo is set up with **Vue**. To see it in action run `npm run dev`, open the given localhost address and change the message in `site/js/App.vue`.
The new message will be hot reloaded - no whole window refresh.

```js
export default {
    data() {
        return {
            msg: 'Hello World!' // <- change the string
        }
    }
}
```
