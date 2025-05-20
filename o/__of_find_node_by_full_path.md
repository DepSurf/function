# Function: <code>__of_find_node_by_full_path</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct device_node *__of_find_node_by_full_path(struct device_node *node, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6acf0)
Location: drivers/of/base.c:903
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
ffff800010b6acf0-ffff800010b6ad8c: __of_find_node_by_full_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *__of_find_node_by_full_path(struct device_node *node, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4e21c)
Location: drivers/of/base.c:903
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
c0c4e21c-c0c4e2a0: __of_find_node_by_full_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *__of_find_node_by_full_path(struct device_node *node, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c446c0)
Location: drivers/of/base.c:903
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
c000000000c446c0-c000000000c44814: __of_find_node_by_full_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *__of_find_node_by_full_path(struct device_node *node, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe0007203a0)
Location: drivers/of/base.c:903
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
ffffffe0007203a0-ffffffe000720448: __of_find_node_by_full_path (STB_GLOBAL)
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
