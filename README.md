# Unofficial Tutorial Of Iced Library

[Iced](https://iced.rs/) is a cross-platform GUI library for [Rust](https://www.rust-lang.org/).
This tutorial serves as a quick start for the library.

## How to use this tutorial

We try to keep each part of the tutorial as simple as possible.
The examples usually explain diverse ways of accomplishing the same task.
Each markdown file contains a complete example that is also available in the `examples` directory.
To run the examples, you can use the following command:

```bash
cargo run --example <example_name>
```

This tutorial is for the latest Iced version (`v0.13.1`)
For older Iced versions, please refer to the following branches:

- [0.12.1](https://github.com/fogarecious/iced_tutorial/tree/0.12.x).
- [0.10.0](https://github.com/fogarecious/iced_tutorial/tree/0.10.x).

## Contents

- [Setting Up](./tutorial/setting_up.md)
- [First App - Hello World!](./tutorial/first_app.md)
- [Explanation of Sandbox Trait](./tutorial/explanation_of_sandbox_trait.md)
- [Adding Widgets](./tutorial/adding_widgets.md)
- [Changing Displaying Content](./tutorial/changing_displaying_content.md)
- [Widgets](./tutorial/widgets.md)
  - [Text](./tutorial/text.md)
  - [Button](./tutorial/button.md)
  - [TextInput](./tutorial/text_input.md)
  - [Checkbox](./tutorial/checkbox.md)
  - [Toggler](./tutorial/toggler.md)
  - [Radio](./tutorial/radio.md)
  - [PickList](./tutorial/picklist.md)
  - [ComboBox](./tutorial/combobox.md)
  - [Slider And VerticalSlider](./tutorial/slider.md)
  - [ProgressBar](./tutorial/progressbar.md)
  - [Tooltip](./tutorial/tooltip.md)
  - [Rule](./tutorial/rule.md)
  - [Image](./tutorial/image.md)
  - [Svg](./tutorial/svg.md)
  <!-- * PaneGrid -->
- [Layouts](./tutorial/layouts.md)
  - [Width And Height](./tutorial/width_and_height.md)
  - [Column](./tutorial/column.md)
  - [Row](./tutorial/row.md)
  - [Space](./tutorial/space.md)
  - [Container](./tutorial/container.md)
  - [Scrollable](./tutorial/scrollable.md)
  <!-- * Responsive -->
- [Styles](./tutorial/styles.md)
  - [Changing Themes](./tutorial/changing_themes.md)
  - [Changing Styles](./tutorial/changing_styles.md)
- [Multipage Apps](./tutorial/multipage_apps.md)
  - [More Than One Page](./tutorial/more_than_one_page.md)
  - [Memoryless Pages](./tutorial/memoryless_pages.md)
  - [Passing Parameters Across Pages](./tutorial/passing_parameters_across_pages.md)
  - [Navigation History](./tutorial/navigation_history.md)
- [Tasks](./tutorial/tasks.md)
  - [Controlling Widgets behavior](./tutorial/controlling_widgets_behavior.md)
  - [Dispatching Tasks at Startup](./tutorial/dispatching_tasks_at_startup.md)
  - [Batch Tasks](./tutorial/batch_tasks.md)
  - [Executing Custom Tasks](./tutorial/executing_custom_tasks.md)
- [Windows](./tutorial/windows.md)
  - [Customizing The Window On Launch](./tutorial/customizing_the_window_on_launch.md)
  - [Changing The Window Dynamically](./tutorial/changing_the_window_dynamically.md)
  - [Closing The Window On Demand](./tutorial/closing_the_window_on_demand.md)
- [Events](./tutorial/events.md)
  - [On Pressed/Released Of Some Widgets](./tutorial/on_pressed_released_of_some_widgets.md)
  - [Producing Messages By Mouse Events](./tutorial/producing_messages_by_mouse_events.md)
  - [Producing Messages By Keyboard Events](./tutorial/producing_messages_by_keyboard_events.md)
  - [Producing Messages By Timers](./tutorial/producing_messages_by_timers.md)
  - [Batch Subscriptions](./tutorial/batch_subscriptions.md)
- [Canvas](./tutorial/canvas.md)
  - [Drawing Shapes](./tutorial/drawing_shapes.md)
  - [Drawing With Caches](./tutorial/drawing_with_caches.md)
- [Custom Widgets](./tutorial/custom_widgets.md)
  - [Drawing Widgets](./tutorial/drawing_widgets.md)
  - [Updating Widgets From Outside](./tutorial/updating_widgets_from_outside.md)
  - [Updating Widgets From Events](./tutorial/updating_widgets_from_events.md)
  - [Producing Widget Messages](./tutorial/producing_widget_messages.md)
  - [Mouse Pointer Over Widgets](./tutorial/mouse_pointer_over_widgets.md)
  - [Texts In Widgets](./tutorial/texts_in_widgets.md)
  - [Custom Background](./tutorial/custom_background.md)
  - [Widgets With Children](./tutorial/widgets_with_children.md)
  - [Taking Any Children](./tutorial/taking_any_children.md)
- Others
  - [Loading Images Asynchronously](./tutorial/loading_images_asynchronously.md)

<!-- examples/component -->

## See Also

- [Iced](https://github.com/iced-rs/iced) - the Iced library.
- [awesome-iced](https://github.com/iced-rs/awesome-iced) - a list of projects depending on Iced.

## Contributions

Pull requests for typos, incorrect information, or other ideas are welcome!

## License

All code in the tutorial is provided under the MIT License.
