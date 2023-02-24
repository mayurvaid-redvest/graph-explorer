# graph-explorer Change Log

## Upcoming


## Release 1.1.0

This release includes the following feature enhancements and bug fixes:

**Features**

* Support for blank nodes when visualizing graphs using the RDF data model (https://github.com/aws/graph-explorer/pull/48)
* Enable Caching feature in the Connections UI which allows you to temporarily store data in the browser between sessions (https://github.com/aws/graph-explorer/pull/48)
* Simplify the setup by consolidating the build and serving the graph-explorer through port (https://github.com/aws/graph-explorer/pull/52)

**Bug fixes**

* Fix an issue where the Graph Explorer is stuck in a loading state indefinitely due to expired credentials by refreshing credentials and retrying requests automatically (https://github.com/aws/graph-explorer/pull/49)


## Release 1.0.0

The first release of Graph Explorer, an Apache 2.0 React-based web application that enables users to visualize both property graph and RDF data and explore connections between data without having to write graph queries. Major features include:

* Ability to connect to graph databases like Amazon Neptune, or open-source endpoints like Gremlin Server or Blazegraph
* Search and preview starting nodes once connected to a graph database
* Visualize results in the Graph View & expand to view neighbors
* Customize the Graph View with preferred layouts, colors, icons, labels, and more
* Use Expand filters to customize the result set by filter text or count of results when expanding
* Scroll through the Table View to view the data in the Graph View in tabular format
* Use Table View filters when you need to highlight a subset of the data
* Download a CSV or JSON of the nodes and edges in visualization, or download as a PNG file