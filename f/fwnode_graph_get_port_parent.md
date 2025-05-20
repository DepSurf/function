# Function: <code>fwnode_graph_get_port_parent</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e5fe0)
Location: drivers/base/property.c:1180
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff815e5fe0-ffffffff815e605c: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d320)
Location: drivers/base/property.c:1229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff8164d320-ffffffff8164d3a5: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688c90)
Location: drivers/base/property.c:1366
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff81688c90-ffffffff81688d15: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8990)
Location: drivers/base/property.c:889
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816a8990-ffffffff816a8a15: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1a30)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816e1a30-ffffffff816e1ab3: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705be0)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff81705be0-ffffffff81705c63: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c10b0)
Location: drivers/base/property.c:992
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff817c10b0-ffffffff817c1133: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d6030)
Location: drivers/base/property.c:1044
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff817d6030-ffffffff817d60b3: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9a50)
Location: drivers/base/property.c:1050
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff817b9a50-ffffffff817b9ad3: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818436d0)
Location: drivers/base/property.c:1066
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff818436d0-ffffffff81843753: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff819873a0)
Location: drivers/base/property.c:1022
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff819873a0-ffffffff8198745b: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af5c30)
Location: drivers/base/property.c:1036
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81af5c30-ffffffff81af5ceb: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43e90)
Location: drivers/base/property.c:1088
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81b43e90-ffffffff81b43f4b: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9bee0)
Location: drivers/base/property.c:1152
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81b9bee0-ffffffff81b9bf9b: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2718)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffff8000108f2718-ffff8000108f27b0: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df3f4)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
c09df3f4-c09df488: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c330)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
c00000000098c330-c00000000098c448: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584306)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffe000584306-ffffffe00058436a: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb330)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816cb330-ffffffff816cb3b3: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6660)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816a6660-ffffffff816a66e3: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f98a0)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816f98a0-ffffffff816f9923: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_port_parent(const struct fwnode_handle *endpoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714140)
Location: drivers/base/property.c:913
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff81714140-ffffffff817141c3: fwnode_graph_get_port_parent (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *endpoint</code> ➡️ <code>const struct fwnode_handle *endpoint</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
