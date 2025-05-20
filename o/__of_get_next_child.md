# Function: <code>__of_get_next_child</code>

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
struct device_node *__of_get_next_child(const struct device_node *node, struct device_node *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b68608)
Location: drivers/of/base.c:728
Inline: False
Direct callers:
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:of_get_next_child
```
**Symbols:**

```
ffff800010b68608-ffff800010b68678: __of_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *__of_get_next_child(const struct device_node *node, struct device_node *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4c5f4)
Location: drivers/of/base.c:728
Inline: False
Direct callers:
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:of_get_next_child
```
**Symbols:**

```
c0c4c5f4-c0c4c654: __of_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *__of_get_next_child(const struct device_node *node, struct device_node *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c40f80)
Location: drivers/of/base.c:728
Inline: False
Direct callers:
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:of_get_next_child
```
**Symbols:**

```
c000000000c40f80-c000000000c41020: __of_get_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *__of_get_next_child(const struct device_node *node, struct device_node *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071e94e)
Location: drivers/of/base.c:728
Inline: False
Direct callers:
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:of_get_next_child
```
**Symbols:**

```
ffffffe00071e94e-ffffffe00071e9a6: __of_get_next_child (STB_LOCAL)
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
