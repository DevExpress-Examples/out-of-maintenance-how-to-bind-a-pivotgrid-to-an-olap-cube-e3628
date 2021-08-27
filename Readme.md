<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128578025/12.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3628)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/DXPivotGrid_BindingToOlapCube/MainPage.xaml) (VB: [MainPage.xaml](./VB/DXPivotGrid_BindingToOlapCube/MainPage.xaml))
<!-- default file list end -->
# How to: Bind a PivotGrid to an OLAP Cube


<p>The following example demonstrates how to bind a <strong>PivotGridControl</strong> to an OLAP cube via the XMLA data access standard.</p>


<h3>Description</h3>

<p>In this example, OLAP connection parameters are specified in a connection string passed to the PivotGridControl.OlapConnectionString property. The following parameters are provided:</p><p><strong>Data Source</strong> - a path to a data pump that was previously configured on an IIS server and will be used as a middle-ware component to access the datasource.</p><p><strong>Initial Catalog</strong> - a data catalog that contains cubes. </p><p><strong>Cube Name</strong> - the name of the cube that provides OLAP data.</p><br />


<br/>


