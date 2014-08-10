redis Cookbook
==============
Simple redis cookbook.
It is intended to create an application environment of their own primarily.

Attributes
----------
#### redis::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['redis']['version']</tt></td>
    <td>String</td>
    <td>Install redis version</td>
    <td><tt>2.8.13</tt></td>
  </tr>
  <tr>
    <td><tt>['redis']['port']</tt></td>
    <td>Integer</td>
    <td>redis port</td>
    <td><tt>6739</tt></td>
  </tr>
</table>

Usage
-----
#### redis::default
```json
{
  "name":"my_node",
  "run_list": [
    "recipe[redis]"
  ]
}
```

Contributing
------------
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Hirokazu Miyaji
