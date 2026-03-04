---
permalink: /debug/
---

<h1>Site configuration</h1>
<code>
{{ site | debug }}
{{ site.meta | debug }}
{{ site.defaults | debug }}
</code>

<h1>Page configuration</h1>
<code>
{{ page | debug }}
{{ page.defaults | debug }}
{{ page.description | debug }}
</code>