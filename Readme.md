<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128574787/13.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2929)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# WinForms - How to Highlight Pivot Grid Cells that Correspond to a Series Point on Hover

This example shows how to indicate the source data value in the Pivot Grid when a Chart's series point is located under the mouse cursor. The actual coordinates are extracted from the [SeriesPoint.Tag](https://documentation.devexpress.com/#CoreLibraries/DevExpressXtraChartsSeriesPoint_Tagtopic) property. The [PivotGridControl.CustomAppearance](https://docs.devexpress.com/WindowsForms/DevExpress.XtraPivotGrid.PivotGridControl.CustomAppearance) event applies the style for the corresponding Pivot Grid cell.

![Chart](./images/chart.png)

## Files to Review

* [Form1.cs](./CS/WindowsApplication53/Form1.cs) (VB: [Form1.vb](./VB/WindowsApplication53/Form1.vb))
* [Program.cs](./CS/WindowsApplication53/Program.cs) (VB: [Program.vb](./VB/WindowsApplication53/Program.vb))

## Documentation 

* [Integrate the Pivot Grid with the Chart Control](https://docs.devexpress.com/WindowsForms/8748/controls-and-libraries/pivot-grid/data-analysis/integration-with-the-chart-control)