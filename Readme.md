<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* [Program.cs](./CS/Program.cs) (VB: [Program.vb](./VB/Program.vb))
<!-- default file list end -->

# How to Customize the Popup Menu to Hide or Show the Totals

This example demonstrates how to add an item to the [Header Area](https://docs.devexpress.com/WindowsForms/1803) popup menu.

Handle the [PivotGridControl.PopupMenuShowing](https://docs.devexpress.com/WindowsForms/DevExpress.XtraPivotGrid.PivotGridControl.PopupMenuShowing) event, create a new menu item and add it to the [e.Menu.Items](https://docs.devexpress.com/WindowsForms/DevExpress.Utils.Menu.DXSubMenuItem.Items) collection.

![screenshot](https://github.com/DevExpress-Examples/how-to-toggle-totals-visibility-at-runtime-e923/blob/18.2.3%2B/images/screenshot.png)