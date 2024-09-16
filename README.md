# t4-cms-flexbox
Flexbox container and items for Terminal Four CMS


## Package content

Content Type
- Flex Container (470)

Lists
- flex_container_justifyContent (182)


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


| Property Name | Options |
|---------------|---------|
| ct_justifyContent | - flex-start<br>- flex-end<br>- center<br>- space-between<br>- space-around<br>- space-evenly |
| ct_alignItems | - stretch<br>- flex-start<br>- flex-end<br>- center<br>- baseline |
| ct_flexDirection | - row<br>- row-reverse<br>- column<br>- column-reverse |
| ct_flexWrap | - nowrap<br>- wrap<br>- wrap-reverse |
| ct_alignContent | - stretch<br>- flex-start<br>- flex-end<br>- center<br>- space-between<br>- space-around |

