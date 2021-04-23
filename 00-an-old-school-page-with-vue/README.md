
#### Vue compponent link

`https://unpkg.com/vue/dist/vue.js`

#### how they get alone with each other?

```javascript
    /* Create a Vue instance*/
    new Vue({
        template: '<h3 style="color:purple; text-align:center; margin: 300px;">{{ name }}</h3>',
        data: function() {
            return {
                name: 'ch2c'
            }
        }
    }).$mount('#app');
```
