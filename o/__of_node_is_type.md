# Function: <code>__of_node_is_type</code>

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
bool __of_node_is_type(const struct device_node *np, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b68858)
Location: drivers/of/base.c:82
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:__of_device_is_compatible
```
**Symbols:**

```
ffff800010b68858-ffff800010b688d8: __of_node_is_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __of_node_is_type(const struct device_node *np, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4c928)
Location: drivers/of/base.c:82
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:__of_device_is_compatible
```
**Symbols:**

```
c0c4c928-c0c4c99c: __of_node_is_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __of_node_is_type(const struct device_node *np, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c419d0)
Location: drivers/of/base.c:82
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:__of_device_is_compatible
```
**Symbols:**

```
c000000000c419d0-c000000000c41bb4: __of_node_is_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __of_node_is_type(const struct device_node *np, const char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071ec8a)
Location: drivers/of/base.c:82
Inline: False
Direct callers:
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:__of_device_is_compatible
```
**Symbols:**

```
ffffffe00071ec8a-ffffffe00071ece4: __of_node_is_type (STB_LOCAL)
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
