<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128578693/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2131)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Pivot Grid for WPF - How to Group Date-Time Values

This example shows how to group date-time values.

![Pivot Grid](./images/pivotgrid.png)

Multiple Pivot Grid fields are bound to the same data field - OrderDate. The [DataSourceColumnBindingBase.GroupInterval](https://docs.devexpress.com/CoreLibraries/DevExpress.PivotGrid.DataBinding.DataSourceColumnBindingBase.GroupInterval) property is used to create a Year → Quarter → Month hierarchy.  

## Files to Review:

* [MainWindow.xaml](./CS/HowToGroupDateTime/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/HowToGroupDateTime/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/HowToGroupDateTime/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/HowToGroupDateTime/MainWindow.xaml.vb))

## Documentation

[Grouping](https://docs.devexpress.com/WPF/8061/controls-and-libraries/pivot-grid/data-shaping/grouping)

## More Examples

[Pivot Grid for WPF - Custom Group Intervals](https://github.com/DevExpress-Examples/how-to-implement-custom-group-intervals-e2132)




