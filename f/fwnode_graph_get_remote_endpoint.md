# Function: <code>fwnode_graph_get_remote_endpoint</code>

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
struct fwnode_handle *fwnode_graph_get_remote_endpoint(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e60d6)
Location: drivers/base/property.c:1232
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff815e6110-ffffffff815e6137: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d436)
Location: drivers/base/property.c:1282
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff8164d470-ffffffff8164d49a: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688da5)
Location: drivers/base/property.c:1419
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff81688de0-ffffffff81688e0a: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8aa5)
Location: drivers/base/property.c:942
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816a8ae0-ffffffff816a8b0b: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1b45)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816e1b80-ffffffff816e1bab: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705cf5)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff81705d30-ffffffff81705d5b: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c1345)
Location: drivers/base/property.c:1045
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff817c0350-ffffffff817c037b: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d64db)
Location: drivers/base/property.c:1097
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff817d5210-ffffffff817d523b: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9fdd)
Location: drivers/base/property.c:1103
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff817b8c50-ffffffff817b8c7b: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843bd1)
Location: drivers/base/property.c:1119
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff818428b0-ffffffff818428db: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987baa)
Location: drivers/base/property.c:1075
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff81986a90-ffffffff81986ad9: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af650a)
Location: drivers/base/property.c:1089
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff81af51f0-ffffffff81af5239: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b4479a)
Location: drivers/base/property.c:1150
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff81b43420-ffffffff81b43469: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9c7ea)
Location: drivers/base/property.c:1214
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff81b9b2f0-ffffffff81b9b339: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
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
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2850)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffff8000108f28a0-ffff8000108f28f0: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df524)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
c09df558-c09df59c: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c520)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
c00000000098c580-c00000000098c5ec: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe0005843ec)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffe000584426-ffffffe000584460: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
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
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb445)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816cb480-ffffffff816cb4ab: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6775)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816a67b0-ffffffff816a67db: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f99b5)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff816f99f0-ffffffff816f9a1b: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_graph_get_remote_endpoint(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714255)
Location: drivers/base/property.c:966
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
```
**Symbols:**

```
ffffffff81714290-ffffffff817142bb: fwnode_graph_get_remote_endpoint (STB_GLOBAL)
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
