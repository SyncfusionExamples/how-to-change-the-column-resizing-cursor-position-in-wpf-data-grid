# How to change the column resizing cursor position in WPF DataGrid(SfDataGrid)?

## About the sample

This example illustrates how to change the column resizing cursor position in WPF DataGrid

By default, resizing cursor in SfDataGrid is west to east. If you change the flow direction of SfDataGrid, you need to change the resizing cursor by using SfDataGrid.ColumnResizingController.ResizingCursor.

```c#
this.dataGrid.ColumnResizingController.ResizingCursor = Cursors.SizeNS;
```

## Requirements to run the demo
Visual Studio 2015 and above versions
