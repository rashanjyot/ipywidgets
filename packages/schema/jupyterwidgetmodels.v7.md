# Model State

This is a description of the model state for each widget in the core Jupyter widgets library. The model ID of a widget is the id of the comm object the widget is using. A reference to a widget is serialized to JSON as a string of the form `"IPY_MODEL_<MODEL_ID>"`, where `<MODEL_ID>` is the model ID of a previously created widget of the specified type.

This model specification is for ipywidgets 7.0, @jupyter-widgets/base 3.0.0, and @jupyter-widgets/controls 3.0.0.

## Model attributes

Each widget in the Jupyter core widgets is represented below. The heading represents the model name, module, and version, view name, module, and version that the widget is registered with.


### LayoutModel (@jupyter-widgets/base, 3.0.0); LayoutView (@jupyter-widgets/base, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/base'` | The namespace for the model.
`_model_module_version` | string           | `'3.0.0'`        | A semver requirement for namespace version containing the model.
`_model_name`    | string           | `'LayoutModel'`  | 
`_view_module`   | string           | `'@jupyter-widgets/base'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'LayoutView'`   | 
`align_content`  | `null` or string (one of `'flex-start'`, `'flex-end'`, `'center'`, `'space-between'`, `'space-around'`, `'space-evenly'`, `'stretch'`, `'inherit'`, `'initial'`, `'unset'`) | `null`           | The align-content CSS attribute.
`align_items`    | `null` or string (one of `'flex-start'`, `'flex-end'`, `'center'`, `'baseline'`, `'stretch'`, `'inherit'`, `'initial'`, `'unset'`) | `null`           | The align-items CSS attribute.
`align_self`     | `null` or string (one of `'auto'`, `'flex-start'`, `'flex-end'`, `'center'`, `'baseline'`, `'stretch'`, `'inherit'`, `'initial'`, `'unset'`) | `null`           | The align-self CSS attribute.
`border`         | `null` or string | `null`           | The border CSS attribute.
`bottom`         | `null` or string | `null`           | The bottom CSS attribute.
`display`        | `null` or string | `null`           | The display CSS attribute.
`flex`           | `null` or string | `null`           | The flex CSS attribute.
`flex_flow`      | `null` or string | `null`           | The flex-flow CSS attribute.
`height`         | `null` or string | `null`           | The height CSS attribute.
`justify_content` | `null` or string (one of `'flex-start'`, `'flex-end'`, `'center'`, `'space-between'`, `'space-around'`, `'inherit'`, `'initial'`, `'unset'`) | `null`           | The justify-content CSS attribute.
`left`           | `null` or string | `null`           | The left CSS attribute.
`margin`         | `null` or string | `null`           | The margin CSS attribute.
`max_height`     | `null` or string | `null`           | The max-height CSS attribute.
`max_width`      | `null` or string | `null`           | The max-width CSS attribute.
`min_height`     | `null` or string | `null`           | The min-height CSS attribute.
`min_width`      | `null` or string | `null`           | The min-width CSS attribute.
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`order`          | `null` or string | `null`           | The order CSS attribute.
`overflow`       | `null` or string (one of `'visible'`, `'hidden'`, `'scroll'`, `'auto'`, `'inherit'`, `'initial'`, `'unset'`) | `null`           | The overflow CSS attribute.
`overflow_x`     | `null` or string (one of `'visible'`, `'hidden'`, `'scroll'`, `'auto'`, `'inherit'`, `'initial'`, `'unset'`) | `null`           | The overflow-x CSS attribute.
`overflow_y`     | `null` or string (one of `'visible'`, `'hidden'`, `'scroll'`, `'auto'`, `'inherit'`, `'initial'`, `'unset'`) | `null`           | The overflow-y CSS attribute.
`padding`        | `null` or string | `null`           | The padding CSS attribute.
`right`          | `null` or string | `null`           | The right CSS attribute.
`top`            | `null` or string | `null`           | The top CSS attribute.
`visibility`     | `null` or string (one of `'visible'`, `'hidden'`, `'inherit'`, `'initial'`, `'unset'`) | `null`           | The visibility CSS attribute.
`width`          | `null` or string | `null`           | The width CSS attribute.

### AccordionModel (@jupyter-widgets/controls, 3.0.0); AccordionView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'AccordionModel'` | 
`_titles`        | object           | `{}`             | Titles of the pages
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'AccordionView'` | 
`box_style`      | string (one of `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the box.
`children`       | array            | `[]`             | List of widget children
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`selected_index` | `null` or number (integer) | `0`              | The index of the selected page. This is either an integer selecting a particular sub-widget, or None to have no widgets selected.

### BoundedFloatTextModel (@jupyter-widgets/controls, 3.0.0); FloatTextView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'BoundedFloatTextModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'FloatTextView'` | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`max`            | number (float)   | `100.0`          | Max value
`min`            | number (float)   | `0.0`            | Min value
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | number (float)   | `0.0`            | Float value

### BoundedIntTextModel (@jupyter-widgets/controls, 3.0.0); IntTextView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'BoundedIntTextModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'IntTextView'`  | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`max`            | number (integer) | `100`            | Max value
`min`            | number (integer) | `0`              | Min value
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | number (integer) | `0`              | Int value

### BoxModel (@jupyter-widgets/controls, 3.0.0); BoxView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'BoxModel'`     | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'BoxView'`      | 
`box_style`      | string (one of `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the box.
`children`       | array            | `[]`             | List of widget children
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.

### ButtonModel (@jupyter-widgets/controls, 3.0.0); ButtonView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ButtonModel'`  | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ButtonView'`   | 
`button_style`   | string (one of `'primary'`, `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the button.
`description`    | string           | `''`             | Button label.
`disabled`       | boolean          | `false`          | Enable or disable user changes.
`icon`           | string           | `''`             | Font-awesome icon name, without the 'fa-' prefix.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to ButtonStyle widget | reference to new instance | 
`tooltip`        | string           | `''`             | Tooltip caption of the button.

### ButtonStyleModel (@jupyter-widgets/controls, 3.0.0); StyleView (@jupyter-widgets/base, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ButtonStyleModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/base'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'StyleView'`    | 
`button_color`   | `null` or string | `null`           | Color of the button
`font_weight`    | string           | `''`             | Button text font weight.
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.

### CheckboxModel (@jupyter-widgets/controls, 3.0.0); CheckboxView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'CheckboxModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'CheckboxView'` | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes.
`indent`         | boolean          | `true`           | Indent the control to align with other controls with a description.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | boolean          | `false`          | Bool value

### ColorPickerModel (@jupyter-widgets/controls, 3.0.0); ColorPickerView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ColorPickerModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ColorPickerView'` | 
`concise`        | boolean          | `false`          | Display short version with just a color selector.
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | string           | `'black'`        | The color value.

### ControllerAxisModel (@jupyter-widgets/controls, 3.0.0); ControllerAxisView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ControllerAxisModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ControllerAxisView'` | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`value`          | number (float)   | `0.0`            | The value of the axis.

### ControllerButtonModel (@jupyter-widgets/controls, 3.0.0); ControllerButtonView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ControllerButtonModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ControllerButtonView'` | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`pressed`        | boolean          | `false`          | Whether the button is pressed.
`value`          | number (float)   | `0.0`            | The value of the button.

### ControllerModel (@jupyter-widgets/controls, 3.0.0); ControllerView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ControllerModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ControllerView'` | 
`axes`           | array            | `[]`             | The axes on the gamepad.
`buttons`        | array            | `[]`             | The buttons on the gamepad.
`connected`      | boolean          | `false`          | Whether the gamepad is connected.
`index`          | number (integer) | `0`              | The id number of the controller.
`layout`         | reference to Layout widget | reference to new instance | 
`mapping`        | string           | `''`             | The name of the control mapping.
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`name`           | string           | `''`             | The name of the controller.
`timestamp`      | number (float)   | `0.0`            | The last time the data from this gamepad was updated.

### DatePickerModel (@jupyter-widgets/controls, 3.0.0); DatePickerView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'DatePickerModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'DatePickerView'` | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | `null` or Date   | `null`           | 

### DescriptionStyleModel (@jupyter-widgets/controls, 3.0.0); StyleView (@jupyter-widgets/base, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'DescriptionStyleModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/base'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'StyleView'`    | 
`description_width` | string           | `''`             | Width of the description to the side of the control.
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.

### DirectionalLinkModel (@jupyter-widgets/controls, 3.0.0); None (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'DirectionalLinkModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | `null` or string | `null`           | Name of the view.
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`source`         | array            | `[]`             | The source (widget, 'trait_name') pair
`target`         | array            | `[]`             | The target (widget, 'trait_name') pair

### DropdownModel (@jupyter-widgets/controls, 3.0.0); DropdownView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'DropdownModel'` | 
`_options_labels` | array            | `[]`             | The labels for the options.
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'DropdownView'` | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`index`          | `null` or number (integer) | `null`           | Selected index
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations

### FloatProgressModel (@jupyter-widgets/controls, 3.0.0); ProgressView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'FloatProgressModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ProgressView'` | 
`bar_style`      | `null` or string (one of `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the progess bar.
`description`    | string           | `''`             | Description of the control.
`layout`         | reference to Layout widget | reference to new instance | 
`max`            | number (float)   | `100.0`          | Max value
`min`            | number (float)   | `0.0`            | Min value
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`orientation`    | string (one of `'horizontal'`, `'vertical'`) | `'horizontal'`   | Vertical or horizontal.
`style`          | reference to ProgressStyle widget | reference to new instance | 
`value`          | number (float)   | `0.0`            | Float value

### FloatRangeSliderModel (@jupyter-widgets/controls, 3.0.0); FloatRangeSliderView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'FloatRangeSliderModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'FloatRangeSliderView'` | 
`continuous_update` | boolean          | `true`           | Update the value of the widget as the user is sliding the slider.
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`max`            | number (float)   | `100.0`          | Max value
`min`            | number (float)   | `0.0`            | Min value
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`orientation`    | string (one of `'horizontal'`, `'vertical'`) | `'horizontal'`   | Vertical or horizontal.
`readout`        | boolean          | `true`           | Display the current value of the slider next to it.
`readout_format` | string           | `'.2f'`          | Format for the readout
`step`           | number (float)   | `0.1`            | Minimum step to increment the value
`style`          | reference to SliderStyle widget | reference to new instance | 
`value`          | array            | `[0.0, 1.0]`     | Tuple of (lower, upper) bounds

### FloatSliderModel (@jupyter-widgets/controls, 3.0.0); FloatSliderView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'FloatSliderModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'FloatSliderView'` | 
`continuous_update` | boolean          | `true`           | Update the value of the widget as the user is holding the slider.
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`max`            | number (float)   | `100.0`          | Max value
`min`            | number (float)   | `0.0`            | Min value
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`orientation`    | string (one of `'horizontal'`, `'vertical'`) | `'horizontal'`   | Vertical or horizontal.
`readout`        | boolean          | `true`           | Display the current value of the slider next to it.
`readout_format` | string           | `'.2f'`          | Format for the readout
`step`           | number (float)   | `0.1`            | Minimum step to increment the value
`style`          | reference to SliderStyle widget | reference to new instance | 
`value`          | number (float)   | `0.0`            | Float value

### FloatTextModel (@jupyter-widgets/controls, 3.0.0); FloatTextView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'FloatTextModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'FloatTextView'` | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | number (float)   | `0.0`            | Float value

### HBoxModel (@jupyter-widgets/controls, 3.0.0); HBoxView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'HBoxModel'`    | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'HBoxView'`     | 
`box_style`      | string (one of `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the box.
`children`       | array            | `[]`             | List of widget children
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.

### HTMLMathModel (@jupyter-widgets/controls, 3.0.0); HTMLMathView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'HTMLMathModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'HTMLMathView'` | 
`description`    | string           | `''`             | Description of the control.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`placeholder`    | string           | `'\u200b'`       | Placeholder text to display when nothing has been typed
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | string           | `''`             | String value

### HTMLModel (@jupyter-widgets/controls, 3.0.0); HTMLView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'HTMLModel'`    | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'HTMLView'`     | 
`description`    | string           | `''`             | Description of the control.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`placeholder`    | string           | `'\u200b'`       | Placeholder text to display when nothing has been typed
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | string           | `''`             | String value

### ImageModel (@jupyter-widgets/controls, 3.0.0); ImageView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_b64value`      | string           | `''`             | The base64 encoded image data.
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ImageModel'`   | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ImageView'`    | 
`format`         | string           | `'png'`          | The format of the image.
`height`         | string           | `''`             | Height of the image in pixels.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`width`          | string           | `''`             | Width of the image in pixels.

### IntProgressModel (@jupyter-widgets/controls, 3.0.0); ProgressView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'IntProgressModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ProgressView'` | 
`bar_style`      | string (one of `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the progess bar.
`description`    | string           | `''`             | Description of the control.
`layout`         | reference to Layout widget | reference to new instance | 
`max`            | number (integer) | `100`            | Max value
`min`            | number (integer) | `0`              | Min value
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`orientation`    | string (one of `'horizontal'`, `'vertical'`) | `'horizontal'`   | Vertical or horizontal.
`style`          | reference to ProgressStyle widget | reference to new instance | 
`value`          | number (integer) | `0`              | Int value

### IntRangeSliderModel (@jupyter-widgets/controls, 3.0.0); IntRangeSliderView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'IntRangeSliderModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'IntRangeSliderView'` | 
`continuous_update` | boolean          | `true`           | Update the value of the widget as the user is sliding the slider.
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`max`            | number (integer) | `100`            | Max value
`min`            | number (integer) | `0`              | Min value
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`orientation`    | string (one of `'horizontal'`, `'vertical'`) | `'horizontal'`   | Vertical or horizontal.
`readout`        | boolean          | `true`           | Display the current value of the slider next to it.
`readout_format` | string           | `'d'`            | Format for the readout
`step`           | number (integer) | `1`              | Minimum step that the value can take
`style`          | reference to SliderStyle widget | reference to new instance | Slider style customizations.
`value`          | array            | `[0, 1]`         | Tuple of (lower, upper) bounds

### IntSliderModel (@jupyter-widgets/controls, 3.0.0); IntSliderView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'IntSliderModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'IntSliderView'` | 
`continuous_update` | boolean          | `true`           | Update the value of the widget as the user is holding the slider.
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`max`            | number (integer) | `100`            | Max value
`min`            | number (integer) | `0`              | Min value
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`orientation`    | string (one of `'horizontal'`, `'vertical'`) | `'horizontal'`   | Vertical or horizontal.
`readout`        | boolean          | `true`           | Display the current value of the slider next to it.
`readout_format` | string           | `'d'`            | Format for the readout
`step`           | number (integer) | `1`              | Minimum step to increment the value
`style`          | reference to SliderStyle widget | reference to new instance | 
`value`          | number (integer) | `0`              | Int value

### IntTextModel (@jupyter-widgets/controls, 3.0.0); IntTextView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'IntTextModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'IntTextView'`  | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | number (integer) | `0`              | Int value

### LabelModel (@jupyter-widgets/controls, 3.0.0); LabelView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'LabelModel'`   | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'LabelView'`    | 
`description`    | string           | `''`             | Description of the control.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`placeholder`    | string           | `'\u200b'`       | Placeholder text to display when nothing has been typed
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | string           | `''`             | String value

### LinkModel (@jupyter-widgets/controls, 3.0.0); None (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'LinkModel'`    | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | `null` or string | `null`           | Name of the view.
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`source`         | array            | `[]`             | The source (widget, 'trait_name') pair
`target`         | array            | `[]`             | The target (widget, 'trait_name') pair

### PasswordModel (@jupyter-widgets/controls, 3.0.0); PasswordView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'PasswordModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'PasswordView'` | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`placeholder`    | string           | `'\u200b'`       | Placeholder text to display when nothing has been typed
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | string           | `''`             | String value

### PlayModel (@jupyter-widgets/controls, 3.0.0); PlayView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'PlayModel'`    | 
`_playing`       | boolean          | `false`          | Whether the control is currently playing.
`_repeat`        | boolean          | `false`          | Whether the control will repeat in a continous loop.
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'PlayView'`     | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`interval`       | number (integer) | `100`            | The maximum value for the play control.
`layout`         | reference to Layout widget | reference to new instance | 
`max`            | number (integer) | `100`            | Max value
`min`            | number (integer) | `0`              | Min value
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`show_repeat`    | boolean          | `true`           | Show the repeat toggle button in the widget.
`step`           | number (integer) | `1`              | Increment step
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | number (integer) | `0`              | Int value

### ProgressStyleModel (@jupyter-widgets/controls, 3.0.0); StyleView (@jupyter-widgets/base, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ProgressStyleModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/base'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'StyleView'`    | 
`bar_color`      | `null` or string | `null`           | Color of the progress bar.
`description_width` | string           | `''`             | Width of the description to the side of the control.
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.

### RadioButtonsModel (@jupyter-widgets/controls, 3.0.0); RadioButtonsView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'RadioButtonsModel'` | 
`_options_labels` | array            | `[]`             | The labels for the options.
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'RadioButtonsView'` | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`index`          | `null` or number (integer) | `null`           | Selected index
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations

### SelectModel (@jupyter-widgets/controls, 3.0.0); SelectView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'SelectModel'`  | 
`_options_labels` | array            | `[]`             | The labels for the options.
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'SelectView'`   | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`index`          | `null` or number (integer) | `null`           | Selected index
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`rows`           | number (integer) | `5`              | The number of rows to display.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations

### SelectMultipleModel (@jupyter-widgets/controls, 3.0.0); SelectMultipleView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'SelectMultipleModel'` | 
`_options_labels` | array            | `[]`             | The labels for the options.
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'SelectMultipleView'` | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`index`          | array            | `[]`             | Selected indices
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`rows`           | number (integer) | `5`              | The number of rows to display.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations

### SelectionRangeSliderModel (@jupyter-widgets/controls, 3.0.0); SelectionRangeSliderView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'SelectionRangeSliderModel'` | 
`_options_labels` | array            | `[]`             | The labels for the options.
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'SelectionRangeSliderView'` | 
`continuous_update` | boolean          | `true`           | Update the value of the widget as the user is holding the slider.
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`index`          | array            | `[0, 0]`         | Min and max selected indices
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`orientation`    | string (one of `'horizontal'`, `'vertical'`) | `'horizontal'`   | Vertical or horizontal.
`readout`        | boolean          | `true`           | Display the current selected label next to the slider
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations

### SelectionSliderModel (@jupyter-widgets/controls, 3.0.0); SelectionSliderView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'SelectionSliderModel'` | 
`_options_labels` | array            | `[]`             | The labels for the options.
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'SelectionSliderView'` | 
`continuous_update` | boolean          | `true`           | Update the value of the widget as the user is holding the slider.
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`index`          | number (integer) | `0`              | Selected index
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`orientation`    | string (one of `'horizontal'`, `'vertical'`) | `'horizontal'`   | Vertical or horizontal.
`readout`        | boolean          | `true`           | Display the current selected label next to the slider
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations

### SliderStyleModel (@jupyter-widgets/controls, 3.0.0); StyleView (@jupyter-widgets/base, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'SliderStyleModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/base'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'StyleView'`    | 
`description_width` | string           | `''`             | Width of the description to the side of the control.
`handle_color`   | `null` or string | `null`           | Color of the slider handle.
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.

### TabModel (@jupyter-widgets/controls, 3.0.0); TabView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'TabModel'`     | 
`_titles`        | object           | `{}`             | Titles of the pages
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'TabView'`      | 
`box_style`      | string (one of `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the box.
`children`       | array            | `[]`             | List of widget children
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`selected_index` | `null` or number (integer) | `0`              | The index of the selected page. This is either an integer selecting a particular sub-widget, or None to have no widgets selected.

### TextModel (@jupyter-widgets/controls, 3.0.0); TextView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'TextModel'`    | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'TextView'`     | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`placeholder`    | string           | `'\u200b'`       | Placeholder text to display when nothing has been typed
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | string           | `''`             | String value

### TextareaModel (@jupyter-widgets/controls, 3.0.0); TextareaView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'TextareaModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'TextareaView'` | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`placeholder`    | string           | `'\u200b'`       | Placeholder text to display when nothing has been typed
`rows`           | `null` or number (integer) | `null`           | The number of rows to display.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | string           | `''`             | String value

### ToggleButtonModel (@jupyter-widgets/controls, 3.0.0); ToggleButtonView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ToggleButtonModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ToggleButtonView'` | 
`button_style`   | string (one of `'primary'`, `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the button.
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes.
`icon`           | string           | `''`             | Font-awesome icon.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`tooltip`        | string           | `''`             | Tooltip caption of the toggle button.
`value`          | boolean          | `false`          | Bool value

### ToggleButtonsModel (@jupyter-widgets/controls, 3.0.0); ToggleButtonsView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ToggleButtonsModel'` | 
`_options_labels` | array            | `[]`             | The labels for the options.
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ToggleButtonsView'` | 
`button_style`   | `null` or string (one of `'primary'`, `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the buttons.
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes
`icons`          | array            | `[]`             | Icons names for each button (FontAwesome names without the fa- prefix).
`index`          | `null` or number (integer) | `null`           | Selected index
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`style`          | reference to ToggleButtonsStyle widget | reference to new instance | 
`tooltips`       | array            | `[]`             | Tooltips for each button.

### ToggleButtonsStyleModel (@jupyter-widgets/controls, 3.0.0); StyleView (@jupyter-widgets/base, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ToggleButtonsStyleModel'` | 
`_view_module`   | string           | `'@jupyter-widgets/base'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'StyleView'`    | 
`button_width`   | string           | `''`             | The width of each button.
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.

### VBoxModel (@jupyter-widgets/controls, 3.0.0); VBoxView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'VBoxModel'`    | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'VBoxView'`     | 
`box_style`      | string (one of `'success'`, `'info'`, `'warning'`, `'danger'`, `''`) | `''`             | Use a predefined styling for the box.
`children`       | array            | `[]`             | List of widget children
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.

### ValidModel (@jupyter-widgets/controls, 3.0.0); ValidView (@jupyter-widgets/controls, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/controls'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'ValidModel'`   | 
`_view_module`   | string           | `'@jupyter-widgets/controls'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'ValidView'`    | 
`description`    | string           | `''`             | Description of the control.
`disabled`       | boolean          | `false`          | Enable or disable user changes.
`layout`         | reference to Layout widget | reference to new instance | 
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`readout`        | string           | `'Invalid'`      | Message displayed when the value is False
`style`          | reference to DescriptionStyle widget | reference to new instance | Styling customizations
`value`          | boolean          | `false`          | Bool value

### OutputModel (@jupyter-widgets/output, 3.0.0); OutputView (@jupyter-widgets/output, 3.0.0)

Attribute        | Type             | Default          | Help
-----------------|------------------|------------------|----
`_dom_classes`   | array            | `[]`             | CSS classes applied to widget DOM element
`_model_module`  | string           | `'@jupyter-widgets/output'` | 
`_model_module_version` | string           | `'3.0.0'`        | 
`_model_name`    | string           | `'OutputModel'`  | 
`_view_module`   | string           | `'@jupyter-widgets/output'` | 
`_view_module_version` | string           | `'3.0.0'`        | 
`_view_name`     | string           | `'OutputView'`   | 
`layout`         | reference to Layout widget | reference to new instance | 
`msg_id`         | string           | `''`             | Parent message id of messages to capture
`msg_throttle`   | number (integer) | `1`              | Maximum number of sync msgs the front-end can send before receiving an idle msg from the back-end.
`outputs`        | array            | `[]`             | The output messages synced from the frontend.


## Automated documentation

The code to generate the model attribute listing is below.

```python
import ipywidgets as widgets
from ipywidgets.widgets.widget_link import Link


from traitlets import CaselessStrEnum, Unicode, Tuple, List, Bool, CFloat, Float, CInt, Int, Instance, Undefined, Dict, Any
from ipywidgets import Color

widgets_to_document = sorted(widgets.Widget.widget_types.items())

def typing(x):
    s = ''
    if isinstance(x, CaselessStrEnum):
        s = 'string (one of %s)'%(', '.join('`%r`'%i for i in x.values))
    elif isinstance(x, Unicode):
        s = 'string'
    elif isinstance(x, (Tuple, List)):
        s = 'array'
    elif isinstance(x, Bool):
        s = 'boolean'
    elif isinstance(x, (CFloat, Float)):
        s = 'number (float)'
    elif isinstance(x, (CInt, Int)):
        s = 'number (integer)'
    elif isinstance(x, Color):
        s = 'string (valid color)'
    elif isinstance(x, Dict):
        s = 'object'
    elif isinstance(x, Instance) and issubclass(x.klass, widgets.Widget):
        s = 'reference to %s widget'%(x.klass.__name__)
        # ADD the widget to this documenting list
        if x.klass not in [i[1] for i in widgets_to_document]:
            widgets_to_document.append((x.klass.__name__, x.klass))
    elif isinstance(x, Any):
        # In our case, these all happen to be values that are converted to strings
        s = 'string (valid option label)'
    else:
        s = x.__class__.__name__
    if x.allow_none:
        s = "`null` or "+s
    return s

def jsdefault(t):
    x = t.default_value
    if isinstance(t, Instance):
        x = t.make_dynamic_default()
        if issubclass(t.klass, widgets.Widget):
            return 'reference to new instance'
    if x is True:
        return '`true`'
    elif x is False:
        return '`false`'
    elif x is None:
        return '`null`'
    elif isinstance(x, tuple):
        return '`{0}`'.format(list(x))
    else:
        return '`%s`'%t.default_value_repr()

def format_widget(n, w):
    out = []
    name = dict(zip(['m_module', 'm_version', 'model', 'v_module', 'v_version', 'view'], n))

    out.append('### %(model)s (%(m_module)s, %(m_version)s); %(view)s (%(v_module)s, %(v_version)s)'%name)
    out.append('')
    out.append('{name: <16} | {typing: <16} | {default: <16} | {help}'.format(name='Attribute', typing='Type', 
                                                                             allownone='Nullable', default='Default', help='Help'))
    out.append('{0:-<16}-|-{0:-<16}-|-{0:-<16}-|----'.format('-'))
    for name, t in sorted(w.traits(sync=True).items()):
        if name in ('_model_module', '_view_module', '_model_module_version', '_view_module_version', 
                    'msg_throttle', '_dom_classes', 'layout'):
            # document these separately, since they apply to all classes
            pass
        if name in ('_view_count'):
            # don't document this since it is totally experimental at this point
            continue

        s = '{name: <16} | {typing: <16} | {default: <16} | {help}'.format(name='`%s`'%name, typing=typing(t), 
                                                            allownone='*' if t.allow_none else '', 
                                                                                               default=jsdefault(t),
                                                                                              help=t.help if t.help else '')
        out.append(s)
    out.append('')
    return '\n'.join(out)

out = ''
for n,w in widgets_to_document:
    if issubclass(w, Link):
        out += '\n'+format_widget(n, w((widgets.IntSlider(), 'value'), (widgets.IntSlider(), 'value')))
    elif issubclass(w, widgets.SelectionRangeSlider) or issubclass(w, widgets.SelectionSlider):
        out += '\n'+format_widget(n,w(options=[1]))
    else:
        out += '\n'+format_widget(n,w())
print(out)
```