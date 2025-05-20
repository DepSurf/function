# Function: <code>fwnode_get_next_available_child_node</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81689680)
Location: drivers/base/property.c:1066
Inline: True
```
**Symbols:**

```
ffffffff81689680-ffffffff816896d8: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8f40)
Location: drivers/base/property.c:589
Inline: True
```
**Symbols:**

```
ffffffff816a8f40-ffffffff816a8f98: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e2510)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
ffffffff816e2510-ffffffff816e2567: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817066c0)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
ffffffff817066c0-ffffffff81706717: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0bc0)
Location: drivers/base/property.c:683
Inline: True
```
**Symbols:**

```
ffffffff817c0bc0-ffffffff817c0c1c: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5a60)
Location: drivers/base/property.c:735
Inline: True
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_parse_fwtree
```
**Symbols:**

```
ffffffff817d5a60-ffffffff817d5abc: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9470)
Location: drivers/base/property.c:735
Inline: True
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff817b9470-ffffffff817b94dd: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818430d0)
Location: drivers/base/property.c:736
Inline: True
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff818430d0-ffffffff8184313d: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986e80)
Location: drivers/base/property.c:736
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff81986e80-ffffffff81986f17: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af56b0)
Location: drivers/base/property.c:744
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
```
**Symbols:**

```
ffffffff81af56b0-ffffffff81af5747: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b438e0)
Location: drivers/base/property.c:767
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
```
**Symbols:**

```
ffffffff81b438e0-ffffffff81b43977: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9b850)
Location: drivers/base/property.c:831
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:fw_devlink_parse_fwtree
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
```
**Symbols:**

```
ffffffff81b9b850-ffffffff81b9b8e7: fwnode_get_next_available_child_node (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3690)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
ffff8000108f3690-ffff8000108f36f8: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09dff98)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
c09dff98-c09e0000: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098d400)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
c00000000098d400-c00000000098d4ac: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584dac)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
ffffffe000584dac-ffffffe000584dfa: fwnode_get_next_available_child_node (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cbe10)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
ffffffff816cbe10-ffffffff816cbe67: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a7140)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
ffffffff816a7140-ffffffff816a7197: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816fa380)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
ffffffff816fa380-ffffffff816fa3d7: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_available_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714c20)
Location: drivers/base/property.c:613
Inline: True
```
**Symbols:**

```
ffffffff81714c20-ffffffff81714c77: fwnode_get_next_available_child_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
