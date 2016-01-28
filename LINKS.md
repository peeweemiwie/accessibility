##DHTML Style Guide Working Group

http://access.aol.com/dhtml-style-guide-working-group/

A dynamic menu system might include the following ARIA markup:

`role="menubar"` on the menubar's root element, typically a `<ul>`.

`role="menu"` on the root element for each of the dropdown menus, which typically are either coded as `<ul>` or `<div>`.

`role="menuitem"` on each actionable item in the menu system, including those on the menubar and those in drop-down menus and sub-menus

`aria-haspopup="true"` on any item that triggers the display of a dropdown menu. This is typically applied to all top-level menubar items, and to any menu items that have sub-menus.

`aria-hidden="true"` on each dropdown menu's container element, typically either a `<ul>` or `<div>`. When JavaScript is used to make the menu visible, it should also change this attribute to `aria-hidden="false"`.
