# Function: <code>fwnode_device_is_available</code>

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
bool fwnode_device_is_available(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6a50)
Location: drivers/base/property.c:1028
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff815e6a50-ffffffff815e6a78: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164de80)
Location: drivers/base/property.c:1077
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff8164de80-ffffffff8164deab: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81689580)
Location: drivers/base/property.c:1163
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff81689580-ffffffff816895aa: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8e40)
Location: drivers/base/property.c:686
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff816a8e40-ffffffff816a8e6a: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e2270)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff816e2270-ffffffff816e229a: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81706420)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81706420-ffffffff8170644a: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0a00)
Location: drivers/base/property.c:789
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff817c0a00-ffffffff817c0a2a: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d58a0)
Location: drivers/base/property.c:841
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff817d58a0-ffffffff817d58ca: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817ba035)
Location: drivers/base/property.c:844
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
```
**Symbols:**

```
ffffffff817b8bf0-ffffffff817b8c1d: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843c28)
Location: drivers/base/property.c:839
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff81842880-ffffffff818428ad: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987c14)
Location: drivers/base/property.c:839
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_get_next_available_child_node
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff819868e0-ffffffff8198692b: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af6574)
Location: drivers/base/property.c:847
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_get_next_available_child_node
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff81af4ff0-ffffffff81af503b: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b44804)
Location: drivers/base/property.c:885
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_get_next_available_child_node
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff81b43200-ffffffff81b4324b: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9c854)
Location: drivers/base/property.c:949
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_get_next_available_child_node
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff81b9b0d0-ffffffff81b9b11b: fwnode_device_is_available (STB_GLOBAL)
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
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f33c0)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffff8000108f33c0-ffff8000108f340c: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09dfcb4)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c09dfcb4-c09dfcf8: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098cfd0)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c00000000098cfd0-c00000000098d03c: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584be6)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffe000584be6-ffffffe000584c18: fwnode_device_is_available (STB_GLOBAL)
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
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cbb70)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816cbb70-ffffffff816cbb9a: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6ea0)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816a6ea0-ffffffff816a6eca: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816fa0e0)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816fa0e0-ffffffff816fa10a: fwnode_device_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_device_is_available(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714980)
Location: drivers/base/property.c:710
Inline: True
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81714980-ffffffff817149aa: fwnode_device_is_available (STB_GLOBAL)
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
