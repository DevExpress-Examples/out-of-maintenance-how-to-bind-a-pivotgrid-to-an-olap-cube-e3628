<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/DXPivotGrid_BindingToOlapCube/MainPage.xaml) (VB: [MainPage.xaml](./VB/DXPivotGrid_BindingToOlapCube/MainPage.xaml))
<!-- default file list end -->
# How to: Bind a PivotGrid to an OLAP Cube


<p>The following example demonstrates how to bind a <strong>PivotGridControl</strong> to an OLAP cube via the XMLA data access standard.</p>


<h3>Description</h3>

<p>In this example, OLAP connection parameters are specified in a connection string passed to the PivotGridControl.OlapConnectionString property. The following parameters are provided:</p><p><strong>Data Source</strong> - a path to a data pump that was previously configured on an IIS server and will be used as a middle-ware component to access the datasource.</p><p><strong>Initial Catalog</strong> - a data catalog that contains cubes. </p><p><strong>Cube Name</strong> - the name of the cube that provides OLAP data.</p><br />


<br/>


