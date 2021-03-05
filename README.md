# How to change the column resizing cursor position in WPF DataGrid(SfDataGrid)?

## About the sample

This example illustrates how to change the column resizing cursor position in [WPF DataGrid](https://www.syncfusion.com/wpf-ui-controls/datagrid) (SfDataGrid).

The default position for the resizing cursor is west to east in [WPF DataGrid](https://www.syncfusion.com/wpf-ui-controls/datagrid) (SfDataGrid). If you want to change the flow direction of SfDataGrid, you need to change the resizing cursor by using [SfDataGrid.ColumnResizingController.ResizingCursor](https://help.syncfusion.com/cr/cref_files/windowsforms/Syncfusion.SfDataGrid.WinForms~Syncfusion.WinForms.DataGrid.Interactivity.ColumnResizingController~ResizingCursor.html).

```c#
this.dataGrid.ColumnResizingController.ResizingCursor = Cursors.SizeNS;
```

## Requirements to run the demo
Visual Studio 2015 and above versions
