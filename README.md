# cl-each (🧑🏽‍🤝‍🧑🏽) [TODO]

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
    class MedalMent extends HTMLElement {
        isExpanded = false;
    }
    customElements.define('medal-ment', MedalElement);
</script>



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
    <tbody>
        <template 🧑‍🤝‍🧑-ish=medal-ment>
            <tr>
                <td itemprop=team></td>
                <td itemprop=goldCount></td>
                <td itemprop=silverCount></td>
                <td itemprop=bronzeCount></td>
            </tr>
            <t 🎚️="on when isExpanded">
                <tr>
                    <td colspan=4>
                        <medal-element itemscope></medal-element>
                    </td>
                </tr>
            </t>
        </template>
    </tbody>
</table>
```

[TODO]