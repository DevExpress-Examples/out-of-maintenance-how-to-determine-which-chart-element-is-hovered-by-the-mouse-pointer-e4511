<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128569695/19.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4511)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/DetermineHoveredChartElement/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DetermineHoveredChartElement/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/DetermineHoveredChartElement/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/DetermineHoveredChartElement/MainWindow.xaml.vb))
<!-- default file list end -->
# How to determine which chart element is hovered by the mouse pointer


<p>This example demonstrates how to calculate the hit information for the chart element over which the mouse pointer is hovering. </p><p>To accomplish this, handle the <strong>ChartControl.MouseMove</strong> event, obtain the current chart element via the <a href="http://help.devexpress.com/#WPF/DevExpressXpfChartsChartControl_CalcHitInfotopic"><u>ChartControl.CalcHitInfo</u></a> method, and if the element is not <strong>null</strong> (<strong>Nothing </strong>in Visual Basic), display its information.</p><p><br />
</p>

<br/>


