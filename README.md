# CSSion

The simplest CSS framework and my way of organizing code.


## Layers

All CSS style rules are grouped into layers. There are three layers in total: class, state, and style. The properties of each layer are stored in separate files.

1. The “_Class_” layer \([class.css](cssion/class.css)\) contains rules for normalizing and defining default styles.
2. The “_State_” layer \([state.css](cssion/state.css)\) contains rules for defining variables, utilities, and common styles
3. The “_Style_” layer \([style.css](cssion/style.css)\) contains rules for defining theme styles.


## Groups and subgroups

The properties of each CSS style rule are divided into three groups: context, container, and content. Internally, each property group is divided into subgroups: behavior, position, size, style, and color. This separation determines the order of properties in CSS style rules.


### Scheme

1. Context
   1. Behavior
   2. Position
   3. Dimension
   4. Style
   5. Color
2. Container
   1. Behavior
   2. Position
   3. Dimension
   4. Style
   5. Color
3. Content
   1. Behavior
   2. Position
   3. Dimension
   4. Style
   5. Color


### Order

An example of ordering the CSS properties of the “_Context_” group:

+ transition
+ transition-property
+ transition-duration
+ transition-timing-function
+ transition-delay
+ transform
+ transform-origin
+ display
+ position
+ top
+ right
+ bottom
+ left
+ z-index
+ margin
+ margin-top
+ margin-right
+ margin-bottom
+ margin-left

An example of ordering the CSS properties of the “_Container_” group:

+ float
+ resize
+ overflow
+ visibility
+ opacity
+ outline-width
+ outline-offset
+ outline-style
+ outline-color
+ box-shadow
+ box-sizing
+ border-spacing
+ border-collapse
+ border-width
+ border-width-top
+ border-width-right
+ border-width-bottom
+ border-width-left
+ border-style
+ border-color
+ empty-cells
+ padding
+ padding-top
+ padding-right
+ padding-bottom
+ padding-left
+ width
+ min-width
+ max-width
+ height
+ min-height
+ max-height
+ background-attachment
+ background-position
+ background-repeat
+ background-size
+ background-clip
+ background-image
+ background-color

An example of ordering the CSS properties of the “_Content_” group:

+ text-overflow
+ white-space
+ word-break
+ orphans
+ quotes
+ content
+ clip
+ text-shadow
+ text-overflow
+ direction
+ text-align
+ vertical-align
+ line-height
+ text-indent
+ word-spacing
+ letter-spacing
+ text-decoration
+ text-decoration-line
+ text-decoration-style
+ text-decoration-color
+ text-transform
+ font-size
+ font-family
+ font-variant
+ font-weight
+ font-stretch
+ font-style
+ color
+ caption-side
+ list-style
+ list-style-type
+ list-style-position
+ list-style-image
