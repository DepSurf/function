# Function: <code>fwnode_graph_devcon_matches</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int fwnode_graph_devcon_matches(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match, void **matches, unsigned int matches_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987b50)
Location: drivers/base/property.c:1209
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_matches
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81987b50-ffffffff81987d16: fwnode_graph_devcon_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int fwnode_graph_devcon_matches(const struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match, void **matches, unsigned int matches_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af64b0)
Location: drivers/base/property.c:1223
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_matches
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81af64b0-ffffffff81af6676: fwnode_graph_devcon_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int fwnode_graph_devcon_matches(const struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match, void **matches, unsigned int matches_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b44740)
Location: drivers/base/property.c:1284
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_matches
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81b44740-ffffffff81b44930: fwnode_graph_devcon_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int fwnode_graph_devcon_matches(const struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match, void **matches, unsigned int matches_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9c790)
Location: drivers/base/property.c:1348
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_matches
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81b9c790-ffffffff81b9c980: fwnode_graph_devcon_matches (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
