<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/DXPivotGrid_BindingToOlapCube/MainPage.xaml) (VB: [MainPage.xaml](./VB/DXPivotGrid_BindingToOlapCube/MainPage.xaml))
<!-- default file list end -->
# How to: Bind a PivotGrid to an OLAP Cube


<p>The following example demonstrates how to bind a <strong>PivotGridControl</strong> to an OLAP cube via the XMLA data access standard.</p>


<h3>Description</h3>

<p>In this example, a PivotGridXmlaDataSource object is created and assigned to the PivotGridControl.DataSource property in the markup. OLAP connection parameters are specified in a connection string passed to the PivotGridXmlaDataSource.ConnectionString property. The following parameters are provided:<br />
<strong>Data Source</strong> - a path to a data pump. <br />
<strong>Initial Catalog</strong> - a data catalog that contains cubes. <br />
<strong>Cube Name</strong> - the name of the cube that provides OLAP data. </p>

<br/>


