# Flexbox Container & Items for Terminal Four (t4) CMS

Flexbox container and items for Terminal Four (t4) website content management system.

Allows users/editors to set up containers and add flex items to them.

<a href="https://ct-457.netlify.app/demo.html" target="_blank" rel="noopener noreferrer">View of Advanced Flexbox Controls (static HTML demo)</a>


## Status

- In development, not production or test ready

## Goals

- Application-agnostic: ability to import to TEST or PROD applications
- Utilize handlebars.js for conditionals as required
- Direct edit (?)

## Requirements

- min version: 8.3.20.1 <a href="https://docs.terminalfour.com/release-notes/" target="_blank" rel="noopener noreferrer">View terminalfour releases</a>
- <a href="https://docs.terminalfour.com/documentation/developer-resources/handlebars/" target="_blank">handlebars</a> enabled

## Package content (updated Oct 07, 2024)

Complete package located at:

<a href="packages/t4CmsFlexbox.zip">t4CmsFlexbox.zip</a>

### Content Types

1. Flex Container (470)
2. Flex-Container -- Close -- (472)
2. Flex Item (471)


### Lists for Flex Container

<ol>
<li>flex_container_justifyContent (182)
<li>flex_container_alignItems (183)
<li>flex_container_flexDirection (184)
<li>flex_container_flexWrap (185)
<li>flex_container_alignContent (186)
</ol>

### Lists for Flex Item

<ol>
<li>Flex Item Button Link (188)
</ol>



## Flex Container

The following properties are available for the flex container:


### Properties list

| Property Name | Type | Mandatory | Description |
|---------------|------|-----------|-------------|
| ct_justifyContent | Reference List | Yes | Defines how flex items are aligned along the main axis of the container |
| ct_alignItems | Reference List | Yes | Specifies how flex items are aligned along the cross axis of the container |
| ct_flexDirection | Reference List | Yes | Establishes the main axis, determining the direction flex items are placed in the container |
| ct_flexWrap | Reference List | Yes | Controls whether flex items are forced onto a single line or can wrap onto multiple lines |
| ct_alignContent | Reference List | No | Aligns a flex container's lines within when there is extra space in the cross-axis |
| ct_gap | Range | No | Sets the gap between flex items in both row and column directions simultaneously |
| ct_rowGap | Range | No | Specifies the size of the gap between rows in the flex container |
| ct_columnGap | Range | No | Defines the size of the gap between columns in the flex container |
| ct_padding | Range | No | Sets the padding area on all four sides of the flex container |
| ct_borderWidth | Range | No | Determines the width of the border around the flex container |
| ct_borderColor | Color Picker | No | Specifies the color of the border around the flex container |
| ct_backgroundColor | Color Picker | No | Sets the background color of the flex container |
| ct_width | Range | Yes | Defines the width of the flex container, crucial for determining the layout space |
| ct_height | Range | Yes | Sets the height of the flex container, important for vertical space allocation |

### Reference List

(*) Selected

| Property Name | Options | t4 List Name | ID
|---------------|---------|---|---|
| ct_justifyContent | - flex-start<br>- flex-end<br>- center<br>- space-between<br>- space-around<br>- space-evenly | flex_container_justifyContent
| ct_alignItems | - stretch<br>- flex-start<br>- flex-end<br>- center<br>- baseline | flex_container_alignItems | 183
| ct_flexDirection | - row (*)<br>- row-reverse<br>- column<br>- column-reverse | flex_container_flexDirection | 184
| ct_flexWrap | - nowrap (*)<br>- wrap<br>- wrap-reverse | flex_container_flexWrap
| ct_alignContent | - stretch (*)<br>- flex-start<br>- flex-end<br>- center<br>- space-between<br>- space-around | flex_container_alignContent



## Flex Item


| Property Name | Type | Description |
|---------------|------|-------------|
| ct_itemIcon | Reference List | Selects the icon to display for the flex item |
| ct_itemTitle | Text | Sets the title text for the flex item |
| ct_itemDescription | Textarea | Provides a description for the flex item |
| ct_itemLinkText | Text | Sets the text for the item's link |
| ct_itemLinkURL | Text | Specifies the URL for the item's link |
| ct_itemFlexGrow | Number | Determines how much the item will grow relative to the rest of the flex items |
| ct_itemFlexShrink | Number | Specifies how much the item will shrink relative to the rest of the flex items |
| ct_itemFlexBasis | Text | Sets the initial main size of the flex item |



## Questions

Maintained by Anthony Lepki

