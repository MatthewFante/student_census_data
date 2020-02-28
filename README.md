<h1><i>Detailed Description of Each Interim Project</i></h1>

<ol>
    <li>
        <h2>Import a data source</h2>
        <h3>In Python:</h3>
        <ul>       
            <li>Import any datasource or use the data source that we will provide (a csv file)</li>
            <li>Print output the data source</li>
            <li>Display the datasource, within reason, for visual confirmation. </li>
            <li>This may require iterating through a dataset, or a custom pandas call.</li>
        </ul>
    </li>
    <li>
        <h2>Write to DB; Read from DB</h2>
        <h3>In Python:</h3>
        <ul>       
            <li>Perform #1 above</li>
            <li>create a Sqlite database</li>
            <li>Create staging table in sqlite DB (if your Python write method does not create a table as part of its method)</li>
            <li>write the Python datasource object data to the SQLite staging table</li>
            <li>Query the table and display the results in Python</li>
            <li>Close DB conn.</li>
        </ul>
    </li>
    <li>
        <h2>Transform the data</h2>
        <h3>In Python:</h3>
        <ul>       
            <li>Perform 1 & 2 above</li>
            <li>In Python or SQL: -- query the data from the SQLite staging table -- in the query, transform the data and store into a 2nd database table or python object. -- transform must include at least 1 aggregation, and 1 value manipulation or datatype redefinition</li> 
            <li>Display the new dataset.</li>          
        </ul>
    </li>
</ol>









