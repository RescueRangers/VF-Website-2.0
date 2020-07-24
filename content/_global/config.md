+++
fragment = "config"

[[config]]
  type = "css" # Acceptable values are icon, meta, link, css, js. Default is empty. Would not add anything on empty.
  block = true # If set to true, would inject the code to the <head> tag. Default is false
  html = "<link rel='stylesheet' href='/VF-Website-2.0/site.css'>" # HTML code injected directly to the page. Default is empty.

+++