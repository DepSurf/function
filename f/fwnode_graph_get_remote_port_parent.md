# Function: <code>fwnode_graph_get_remote_port_parent</code>

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
struct fwnode_handle *fwnode_graph_get_remote_port_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6060)
Location: drivers/base/property.c:1200
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff815e6060-ffffffff815e60cb: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d3b0)
Location: drivers/base/property.c:1249
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff8164d3b0-ffffffff8164d421: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688d20)
Location: drivers/base/property.c:1386
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff81688d20-ffffffff81688d91: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8a20)
Location: drivers/base/property.c:909
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff816a8a20-ffffffff816a8a91: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1ac0)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff816e1ac0-ffffffff816e1b33: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705c70)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81705c70-ffffffff81705ce3: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c1345)
Location: drivers/base/property.c:1012
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff817c1140-ffffffff817c11b3: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d64db)
Location: drivers/base/property.c:1064
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff817d60c0-ffffffff817d6133: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9fdd)
Location: drivers/base/property.c:1070
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff817b9ae0-ffffffff817b9b53: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843bd1)
Location: drivers/base/property.c:1086
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff81843760-ffffffff818437d3: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987baa)
Location: drivers/base/property.c:1042
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
```
**Symbols:**

```
ffffffff819874e0-ffffffff81987574: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af650a)
Location: drivers/base/property.c:1056
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
```
**Symbols:**

```
ffffffff81af5df0-ffffffff81af5e84: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b4479a)
Location: drivers/base/property.c:1111
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
```
**Symbols:**

```
ffffffff81b44050-ffffffff81b440e4: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9c7ea)
Location: drivers/base/property.c:1175
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
```
**Symbols:**

```
ffffffff81b9c0a0-ffffffff81b9c134: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
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
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f27b0)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffff8000108f27b0-ffff8000108f2838: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df488)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c09df488-c09df510: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c450)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c00000000098c450-c00000000098c508: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe00058436a)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffe00058436a-ffffffe0005843d6: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
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
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb3c0)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816cb3c0-ffffffff816cb433: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a66f0)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816a66f0-ffffffff816a6763: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9930)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816f9930-ffffffff816f99a3: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_port_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817141d0)
Location: drivers/base/property.c:933
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff817141d0-ffffffff81714243: fwnode_graph_get_remote_port_parent (STB_GLOBAL)
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
