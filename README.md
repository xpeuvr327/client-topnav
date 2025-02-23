# client-topnav
Create a top navigation bar entirely in the browser

# demo
[synthetic demo](https://xpeuvr327.github.io/client-topnav/demo/nested1/)   
[real world usage](http://lesitedela104.webredirect.org/104/le-roman-de-renart/) (page in french)
## try it yourself
```cmd
  git clone https://github.com/xpeuvr327/client-topnav.git  
  cd client-topnav/demo
  python -m http.server
```
then go to [http://localhost:8000/](http://localhost:8000/)  
or open demo folder in your browser

# usage
modify navigations items and paste
``<script src="header.js"></script>`` in your html page (anywhere).

# todos
- remove 404.js (or move to separate script) - it replaces all a (link) elements and redirects to a 404, even on a serverless environment
- remove insert_next_prev_bottom_nav.js (or move to separate script) - adds a button to the next chapter after div#content
- support for paths (currently only works for files in same dir)
