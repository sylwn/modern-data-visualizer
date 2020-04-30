# Details list

Icon type


# People layout

By default, the user profile pictures are fetched from the SharePoint User Profile Service. If your user pictures are stored in Active Directoy, make sure you synchronized them with SharePoint User Profile Service. Otherwise, a placeholder image will be displayed.

### Hover card

Activating this option may slightly reduce loading performances because the user information are fecthed individually for each user (i.e result). **This option shouldn't be used with large page count.**

### Microsoft Graph Toolkit

 The hover card uses Microsoft Graph Toolkit. This means you can add additional information providing your own template like this:

 ```
 <mgt-person-card inherit-details>
    <template data-type="additional-details">
    <h3>Stuffed Animal Friends:</h3>
    <ul>
        <li>Giraffe</li>
        <li>lion</li>
        <li>Rabbit</li>
    </ul>
    </template>
</mgt-person-card>
 ```
More information here: [https://docs.microsoft.com/en-us/graph/toolkit/components/person-card](https://docs.microsoft.com/en-us/graph/toolkit/components/person-card)