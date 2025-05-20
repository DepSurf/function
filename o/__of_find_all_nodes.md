# Function: <code>__of_find_all_nodes</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device_node *__of_find_all_nodes(struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/base.c (ffff800010b6a0b8)
Location: drivers/of/base.c:287
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
Direct callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
ffff800010b68ac0-ffff800010b68af8: __of_find_all_nodes.part.0 (STB_LOCAL)
ffff800010b6a970-ffff800010b6a9c8: __of_find_all_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device_node *__of_find_all_nodes(struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/base.c (c0c4d048)
Location: drivers/of/base.c:287
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
Direct callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
c0c4cd70-c0c4cda8: __of_find_all_nodes.part.0 (STB_LOCAL)
c0c4df34-c0c4df88: __of_find_all_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device_node *__of_find_all_nodes(struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/base.c (c000000000c42844)
Location: drivers/of/base.c:287
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
Direct callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
c000000000c421e0-c000000000c42230: __of_find_all_nodes.part.0 (STB_LOCAL)
c000000000c441e0-c000000000c44230: __of_find_all_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device_node *__of_find_all_nodes(struct device_node *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/of/base.c (ffffffe00071f2bc)
Location: drivers/of/base.c:287
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
Direct callers:
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_core_init
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
ffffffe00071f010-ffffffe00071f03c: __of_find_all_nodes.part.0 (STB_LOCAL)
ffffffe0007200d2-ffffffe00072011e: __of_find_all_nodes (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
