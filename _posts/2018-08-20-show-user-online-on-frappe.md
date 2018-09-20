---
layout: post
author: wellart
tags : Frappe
---
```python
<!-- TO print current logged in user email id -->
<div class="row">
    <div class="col-xs-5 text-right"><big><b>Print By(email id)</b>  </big></div>
    <div class="col-xs-7 "><big>{{ frappe.user }} </big> </div>
</div>

<!-- TO print current logged in user fist name -->
  { % set u = frappe.get_doc("User", frappe.user) %}
<div class="row">
    <div class="col-xs-5 text-right"><big><b>Print By(user name)</b>  </big></div>
    <div class="col-xs-7 "><big>{{ u.first_name }} </big> </div>
</div>
```
