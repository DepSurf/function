# Function: <code>fwnode_graph_get_next_endpoint</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6aa3)
Location: drivers/base/property.c:1166
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff815e5fb0-ffffffff815e5fd7: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164ded3)
Location: drivers/base/property.c:1215
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff8164d2f0-ffffffff8164d31a: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816895d3)
Location: drivers/base/property.c:1352
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff81688c60-ffffffff81688c8a: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8e93)
Location: drivers/base/property.c:875
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff816a8960-ffffffff816a898b: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e2392)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff816e1a00-ffffffff816e1a2b: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81706542)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81705bb0-ffffffff81705bdb: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c12cf)
Location: drivers/base/property.c:978
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff817c0320-ffffffff817c034b: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d616f)
Location: drivers/base/property.c:1030
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff817d51e0-ffffffff817d520b: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9b96)
Location: drivers/base/property.c:1036
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff817b8c20-ffffffff817b8c4b: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818437e0)
Location: drivers/base/property.c:1033
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff818437e0-ffffffff8184385d: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987460)
Location: drivers/base/property.c:989
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81987460-ffffffff819874d8: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af5d00)
Location: drivers/base/property.c:997
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81af5d00-ffffffff81af5dd9: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43f60)
Location: drivers/base/property.c:1046
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
ffffffff81b43f60-ffffffff81b44039: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9bfb0)
Location: drivers/base/property.c:1110
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
ffffffff81b9bfb0-ffffffff81b9c089: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3530)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffff8000108f26c0-ffff8000108f2718: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09dfe0c)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c09df3b0-c09df3f4: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098d1bc)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c00000000098c2c0-c00000000098c32c: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584cd4)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffe0005842c2-ffffffe000584306: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cbc92)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816cb300-ffffffff816cb32b: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6fc2)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816a6630-ffffffff816a665b: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816fa202)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816f9870-ffffffff816f989b: fwnode_graph_get_next_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_next_endpoint(const struct fwnode_handle *fwnode, struct fwnode_handle *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714aa2)
Location: drivers/base/property.c:899
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81714110-ffffffff8171413b: fwnode_graph_get_next_endpoint (STB_GLOBAL)
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
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
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
