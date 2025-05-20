# Function: <code>fwnode_get_next_child_node</code>

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
struct fwnode_handle *fwnode_get_next_child_node(struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e649e)
Location: drivers/base/property.c:949
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff815e5eb0-ffffffff815e5ed7: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164dc68)
Location: drivers/base/property.c:992
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff8164d1f0-ffffffff8164d21a: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688f38)
Location: drivers/base/property.c:1052
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
```
**Symbols:**

```
ffffffff81688b10-ffffffff81688b3a: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8c08)
Location: drivers/base/property.c:575
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff816a8810-ffffffff816a883b: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e2027)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff816e1900-ffffffff816e192b: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817061d7)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff81705ab0-ffffffff81705adb: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0f58)
Location: drivers/base/property.c:669
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff817c0260-ffffffff817c028b: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5cc8)
Location: drivers/base/property.c:721
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff817d5120-ffffffff817d514b: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b96e8)
Location: drivers/base/property.c:721
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff817b8b30-ffffffff817b8b5b: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818433c1)
Location: drivers/base/property.c:722
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff818427c0-ffffffff818427eb: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987174)
Location: drivers/base/property.c:722
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:fwnode_get_next_available_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
**Symbols:**

```
ffffffff819867f0-ffffffff8198683c: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af59d4)
Location: drivers/base/property.c:730
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:fwnode_get_next_available_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81af4ed0-ffffffff81af4f1c: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43c34)
Location: drivers/base/property.c:750
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:fwnode_get_next_available_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81b430e0-ffffffff81b4312c: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9bc84)
Location: drivers/base/property.c:814
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:fwnode_get_next_available_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81b9afb0-ffffffff81b9affc: fwnode_get_next_child_node (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3098)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffff8000108f2508-ffff8000108f2560: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df308)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
c09df12c-c09df170: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c1a4)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
c00000000098beb0-c00000000098bf1c: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe00058424a)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffe00058408c-ffffffe0005840d0: fwnode_get_next_child_node (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb927)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff816cb200-ffffffff816cb22b: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6c57)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff816a6530-ffffffff816a655b: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9e97)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff816f9770-ffffffff816f979b: fwnode_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_child_node(const struct fwnode_handle *fwnode, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714737)
Location: drivers/base/property.c:599
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
Direct callers:
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff81714010-ffffffff8171403b: fwnode_get_next_child_node (STB_GLOBAL)
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
