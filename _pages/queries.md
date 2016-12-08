---
layout: page
title:  "Queries"
permalink: /queries/
---

<table class="table-code">
<thead>
<tr>
<th>Clause</th>
<th>What it does!</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>?per_page=</code></td>
<td>Select number of results per page. Example <a href="https://api.ed.gov/data/less-than-highschool_2015?api_key=DEMO_KEY1&per_page=30">here</a>.</td>
</tr>

<tr>
<td><code>?page=</code></td>
<td>Select results page. Example <a href="https://api.ed.gov/data/less-than-highschool_2015?api_key=DEMO_KEY1&page=2">here</a>.</td>
</tr>

<tr>
<td><code>?sort=Columnx</code> or <code>?sort=-Columnx</code></td>
<td>Sort by Columnx. Example <a href="https://api.ed.gov/data/less-than-highschool_2015?api_key=DEMO_KEY1&sort=Year">here</a>.</td>
</tr>

<tr>
<td><code>/_index_number_</code></td>
<td>Return a single record. Example <a href="https://api.ed.gov/data/less-than-highschool_2015/15?api_key=DEMO_KEY1">here</a>.</td>
</tr>

<tr>
<td><code>?Columnx=</code></td>
<td>Filter by Columnx. Example <a href="https://api.ed.gov/data/less-than-highschool_2015?Sex=Males&api_key=DEMO_KEY1">here</a>.</td>
</tr>

<tr>
<td><code>?Columnx=</code></td>
<td>Filter by Columnx and Columny. Example <a href="https://api.ed.gov/data/less-than-highschool_2015?Sex=Males&Year=2004&api_key=DEMO_KEY1">here</a>.</td>
</tr>

<tr>
<td><code>?Columnx=[]&ColumnX=</code></td>
<td>Filter by multiple values in Columnx. Example <a href="https://api.ed.gov/data/less-than-highschool_2015?Sex=Males&Sex=Females&api_key=DEMO_KEY1">here</a>.</td>
</tr>

</tbody>
</table>
