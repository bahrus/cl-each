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
        isExpanded = false;
    }
    customElements.define('medal-element', MedalElement);
</script>

<template id=medals-parent-row>
    <tr>
        <td itemprop=team></td>
        <td itemprop=goldCount></td>
        <td itemprop=silverCount></td>
        <td itemprop=bronzeCount></td>
    </tr>
    <template blow-dry 🎚️="on when isExpanded">
        <tr>
            <td colspan=4>
                <medal-element itemscope></medal-element>
            </td>
        </tr>
    </template>
</template>



<table itemscope=medal-list>
    <caption>Medal List Summer 2024</caption>
    <thead>
        <tr>
            <th>Team</th>
            <th>Gold Medals</th>
            <th>Silver Medals</th>
            <th>Bronze Medals</th>
        </tr>
    </thead>
    <tbody 🧑‍🤝‍🧑-ish=medal-element 🧑‍🤝‍🧑-src="#medals-parent-row">
    </tbody>
</table>
```

[TODO]