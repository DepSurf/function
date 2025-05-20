# Function: <code>fwnode_get_next_parent</code>

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
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e5e20)
Location: drivers/base/property.c:921
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff815e5e20-ffffffff815e5e77: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d160)
Location: drivers/base/property.c:963
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff8164d160-ffffffff8164d1bd: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688a80)
Location: drivers/base/property.c:1023
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff81688a80-ffffffff81688add: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8770)
Location: drivers/base/property.c:546
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff816a8770-ffffffff816a87d1: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1860)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff816e1860-ffffffff816e18c7: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705a10)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff81705a10-ffffffff81705a77: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c104c)
Location: drivers/base/property.c:607
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name_prefix
```
**Symbols:**

```
ffffffff817c0eb0-ffffffff817c0f17: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5fcc)
Location: drivers/base/property.c:607
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name_prefix
```
**Symbols:**

```
ffffffff817d5f30-ffffffff817d5f97: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b99ec)
Location: drivers/base/property.c:607
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name_prefix
```
**Symbols:**

```
ffffffff817b9950-ffffffff817b99b7: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8184366c)
Location: drivers/base/property.c:607
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name_prefix
```
**Symbols:**

```
ffffffff818435d0-ffffffff81843637: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987325)
Location: drivers/base/property.c:606
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name_prefix
```
**Symbols:**

```
ffffffff81987260-ffffffff819872dc: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af5ba5)
Location: drivers/base/property.c:614
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/swnode.c:software_node_get_name_prefix
```
**Symbols:**

```
ffffffff81af5ad0-ffffffff81af5b4c: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43e05)
Location: drivers/base/property.c:628
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/swnode.c:software_node_get_name_prefix
```
**Symbols:**

```
ffffffff81b43d30-ffffffff81b43dac: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9be55)
Location: drivers/base/property.c:692
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/swnode.c:software_node_get_name_prefix
```
**Symbols:**

```
ffffffff81b9bd80-ffffffff81b9bdfc: fwnode_get_next_parent (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2438)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffff8000108f2438-ffff8000108f24b8: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df074)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
c09df074-c09df0e8: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098bd50)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
c00000000098bd50-c00000000098be3c: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000583ff4)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffe000583ff4-ffffffe000584052: fwnode_get_next_parent (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb160)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff816cb160-ffffffff816cb1c7: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6490)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff816a6490-ffffffff816a64f7: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f96d0)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff816f96d0-ffffffff816f9737: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_next_parent(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81713f70)
Location: drivers/base/property.c:570
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
```
**Symbols:**

```
ffffffff81713f70-ffffffff81713fd7: fwnode_get_next_parent (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
