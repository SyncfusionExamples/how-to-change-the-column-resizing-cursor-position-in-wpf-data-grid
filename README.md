# How to Change the Column Resizing Cursor Position in WPF DataGrid?

This example illustrates how to change the column resizing cursor position in [WPF DataGrid](https://www.syncfusion.com/wpf-controls/datagrid) (SfDataGrid).

The default position for the resizing cursor is west to east in `DataGrid`. If you want to change the flow direction of SfDataGrid, you need to change the resizing cursor by using [SfDataGrid.ColumnResizingController.ResizingCursor](https://help.syncfusion.com/cr/wpf/Syncfusion.UI.Xaml.Grid.GridColumnResizingController.html#Syncfusion_UI_Xaml_Grid_GridColumnResizingController_ResizingCursor).

```c#
this.dataGrid.ColumnResizingController.ResizingCursor = Cursors.SizeNS;
```

![DataGrid with modified column resizing cursor](DataGridWithColumnResizingCursor.png)

Take a moment to peruse the [WPF DataGrid - Getting Started](https://help.syncfusion.com/wpf/datagrid/getting-started) documentation, where you can find about `DataGrid` with code examples.

## Requirements to run the demo

Visual Studio 2015 and above versions
