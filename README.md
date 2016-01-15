# mysql-slow-query-log-visualizer
Automatically exported from code.google.com/p/mysql-slow-query-log-visualizer
<p>I found this useful and want to keep it available. -TNG</p>

<p>Check out original on Gooogle Code for screen shot.  https://code.google.com/p/mysql-slow-query-log-visualizer/</p>

<hr/>

<p>This is a simple HTML5-based application that loads, parses and analyzes a MySQL slow query log and provides the ability to browse it visually. </p>




<p>There are two main components: The chart and the list.  </p>
<p>The chart uses <a href="https://github.com/filamentgroup/jQuery-Visualize" rel="nofollow">jQuery Visualize</a> to display a weekly (averaged) graph of the number of slow queries per hour. This will help you to see what times of the day, and what days of the week your database is under the most strain. </p><p>The list uses <a href="https://github.com/javve/list" rel="nofollow">list.js</a> to display the parsed results from your query log. Using list.js functionality, you can sort by a particular column by clicking on a heading. You can also search and filter your results by entering text in the search box above the list. The chart will update interactively as you search. This way, you can visualize only a particular slice of data. </p><p><strong>Requirements</strong> An HTML5-capable browser. If you are using Google Chrome, the app must be hosted and accessed via a local (or remote) web server in order to parse the log. Firefox 8 works. This currently does not work in Safari 5, and this has not been tested this in IE9. </p><p>Many thanks to: </p><p>List.js author Jonny Strömberg (www.jonnystromberg.se, www.listjs.com) <a href="https://github.com/javve/list" rel="nofollow">https://github.com/javve/list</a> </p><p>jQuery Visualize author Scott Jehl, Filament Group scott@filamentgroup.com <a href="https://github.com/filamentgroup/jQuery-Visualize" rel="nofollow">https://github.com/filamentgroup/jQuery-Visualize</a> </p>
