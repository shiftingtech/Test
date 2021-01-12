# Test Table

## Future filtering tools

## the list

| Category | Item | Source 1 | Source 2 | V0 | V1 | V2 | SW | VL |
|:---|:---|:----|:---|:---|:---|:---|:---|:---|
| Electronics | foo | this should be a link | another link | X | X | X | | |
| Electronics | foo2 | this should be a link | another link |   |   | X | | |
| Motion | stuff | this is a lame link | | | | X | | |


<div id="text"></div>
 
<script>
document.getElementById("text").innerHTML = "Text added by JavaScript code";
</script>

## Data file test v2

<table>
<tr>
 <th>category</th>
 <th>item</th>
 <th>source</th>
</tr>
 
{% for entry in site.data.sourcing %}
<tr>
 {{ entry }}
 <td> {{ entry.category }}</td>
 <td> {{ entry.item }} </td>
 <td> {{ entry.source1 }}</td>
</tr>
 {% endfor %}
 </table>


