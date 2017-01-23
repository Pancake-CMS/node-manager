# node-manager
A web component that is used to provide a tabular layout for the nodes. It also comes with a `fork` and `open` button. `fork` button will let you fork the template or the page under consideration and will save it in `pages` node. Open will let you edit the template or page depending on what it is.

### Installation

```shell
bower install --save pancake-cms-node-manager
```

### Attributes

| Name | Description | Type | Sample Value |
|-------|------------|--------------|------|
| `fbnode` | This is node to display. It can either be `template` to show the user a list of templates, or can be `pages` to show the users a list of pages. | String | `template` or `pages` |
| `route` | The route object, used to open the template or pages in edit mode | Object | this value comes from parent, do not change it. |
| `is-approvals-page` | A value that tells if it needs to show pages from the approvals node. | Boolean | `true` or `false` |