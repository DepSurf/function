# Function: <code>fwnode_get_parent</code>

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
struct fwnode_handle *fwnode_get_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e5fe5)
Location: drivers/base/property.c:938
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff815e5e80-ffffffff815e5ea7: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d325)
Location: drivers/base/property.c:980
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff8164d1c0-ffffffff8164d1ea: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688c95)
Location: drivers/base/property.c:1040
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81688ae0-ffffffff81688b0a: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8995)
Location: drivers/base/property.c:563
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff816a87e0-ffffffff816a880b: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1a35)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff816e18d0-ffffffff816e18fb: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705be5)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81705a80-ffffffff81705aab: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c104c)
Location: drivers/base/property.c:590
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_name_prefix
```
**Symbols:**

```
ffffffff817c0230-ffffffff817c025b: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5fcc)
Location: drivers/base/property.c:590
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
```
**Symbols:**

```
ffffffff817d50f0-ffffffff817d511b: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b99ec)
Location: drivers/base/property.c:590
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
```
**Symbols:**

```
ffffffff817b8b00-ffffffff817b8b2b: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8184366c)
Location: drivers/base/property.c:590
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
```
**Symbols:**

```
ffffffff81842790-ffffffff818427bb: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987325)
Location: drivers/base/property.c:589
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
```
**Symbols:**

```
ffffffff819867a0-ffffffff819867e6: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af5ba5)
Location: drivers/base/property.c:597
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
```
**Symbols:**

```
ffffffff81af4e70-ffffffff81af4eb6: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43e05)
Location: drivers/base/property.c:607
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
```
**Symbols:**

```
ffffffff81b43080-ffffffff81b430c6: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9be55)
Location: drivers/base/property.c:671
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
```
**Symbols:**

```
ffffffff81b9af50-ffffffff81b9af96: fwnode_get_parent (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2730)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
```
**Symbols:**

```
ffff8000108f24b8-ffff8000108f2508: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df408)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
```
**Symbols:**

```
c09df0e8-c09df12c: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c348)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
```
**Symbols:**

```
c00000000098be40-c00000000098beac: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe00058431e)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
```
**Symbols:**

```
ffffffe000584052-ffffffe00058408c: fwnode_get_parent (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb335)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff816cb1d0-ffffffff816cb1fb: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6665)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff816a6500-ffffffff816a652b: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f98a5)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff816f9740-ffffffff816f976b: fwnode_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_parent(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714145)
Location: drivers/base/property.c:587
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81713fe0-ffffffff8171400b: fwnode_get_parent (STB_GLOBAL)
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
