# cl-each (🧑🏽‍🤝‍🧑🏽)

Windows:  🪟 + "." => hol

```TypeScript
export interface Medal{

}
```

```html
<script>
    //@ts-check
    class MedalList extends HTMLElement {
        /** @type{Array<Medal>} */
        list;
    }
    customElements.define('medal-list', MyList);
    class MedalElement extends HTMLElement {

    }
    customElements.define('medal-element', MedalElement);
</script>
<template id=medal>
</template>

<table itemscope=medal-list>
    <thead>
        <tr>
            <th>
        </tr>
    </thead>
</table>
```