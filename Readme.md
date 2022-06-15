<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2131)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Pivot Grid for WPF - How to Group Date-Time Values

This example shows how to group date-time values.

![Pivot Grid for WPF - Group Date-Time Values](images/pivot-grid-wpf-group-date-time.png)

In the example, the [PivotGridControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.PivotGrid.PivotGridControl) contains three [PivotGridField](https://docs.devexpress.com/WPF/DevExpress.Xpf.PivotGrid.PivotGridField) fields (*fieldYear*, *fieldQuarter* and *fieldMonth*) in the Row Area. Each of the field is bound to the "OrderDate" data field. The *fieldYear* pivot grid field's values are grouped by years, the *fieldQuarter* field's values are grouped by quarters, and the *fieldMonth* pivot grid field's values are grouped by months. To specify the field's group interval, use the binding’s [DataSourceColumnBindingBase.GroupInterval](https://docs.devexpress.com/WPF/DevExpress.Xpf.PivotGrid.DataSourceColumnBinding.GroupInterval) property.



## Files to Look At

- [MainWindow.xaml](./CS/HowToGroupDateTime/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/HowToGroupDateTime/MainWindow.xaml))
- [MainWindow.xaml.cs](./CS/HowToGroupDateTime/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/HowToGroupDateTime/MainWindow.xaml.vb))

## Documentation

- [Grouping in Pivot Grid](https://docs.devexpress.com/WPF/8061/controls-and-libraries/pivot-grid/data-shaping/grouping)


## More Examples

- [Pivot Grid for Web Forms - How to Group Date-Time Values](https://github.com/DevExpress-Examples/how-to-group-date-time-values-e1875)


