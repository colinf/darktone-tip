
# darktone-tip

  Darktone Tip theme.

  This is a theme for the [tip component](https://github.com/component/tip).

  ![](http://f.cl.ly/items/3A1n3M1D2v1U2w331N09/Screen%20Shot%202012-10-13%20at%2014.51.13.png)

  It's part of a series of Darktone theme components and you may also wish to use the following:

  * [darktone-calendar](https://github.com/colinf/darktone-calendar) - theme for component/calendar
  * [darktone-popover](https://github.com/colinf/darktone-popover) - theme for component/popover
  * [darktone](https://github.com/colinf/darktone) - a combined theme for tip, popover & calendar

## Installation

You can quickly install the component into your project using the following command from the project root.
```
$ component install colinf/darktone-tip
```
But the best way to use it is to amend your component.json file to add the theme as a dependency. You can then use the `component build` command to install the required components.

Make sure that you list **colinf/darktone-tip** after **component/tip** in your dependencies so that the styles from the theme override any styles in the tip component itself. Below is an example extract from a component.json which uses the darktone tip theme.

```json
"dependencies": {
  "component/tip": "*",
  "colinf/darktone-tip": "*"
}
```
# License

  MIT (see the file License.txt included in this distribution for further details)
