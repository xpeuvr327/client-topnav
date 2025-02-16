# client-topnav
Create a top navigation bar entirely in the browser

# demo
[synthetic demo](/client-topnav/demo/nested1/)   
[real world usage](http://lesitedela104.webredirect.org/104/le-roman-de-renart/) (page in french)

# usage
modify navigations items and add
``<script src="header.js"></script>`` to your html page (anywhere).

# todos
- remove 404.js (or move to separate script) - it replaces all a (link) elements and redirects to a 404, even on a serverless environment
- remove insert_next_prev_bottom_nav.js (or move to separate script) - adds a button to the next chapter after div#content
