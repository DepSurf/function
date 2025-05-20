# Function: <code>property_list_free</code>

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
void property_list_free(struct property *prop_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffff800010b705f8)
Location: drivers/of/dynamic.c:308
Inline: False
Direct callers:
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
```
**Symbols:**

```
ffff800010b705f8-ffff800010b70648: property_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void property_list_free(struct property *prop_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c0c52f18)
Location: drivers/of/dynamic.c:308
Inline: False
Direct callers:
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
```
**Symbols:**

```
c0c52f18-c0c52f60: property_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void property_list_free(struct property *prop_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (c000000000c4c000)
Location: drivers/of/dynamic.c:308
Inline: False
Direct callers:
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
```
**Symbols:**

```
c000000000c4c000-c000000000c4c07c: property_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void property_list_free(struct property *prop_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/dynamic.c (ffffffe000724852)
Location: drivers/of/dynamic.c:308
Inline: False
Direct callers:
  - drivers/of/dynamic.c:of_node_release
  - drivers/of/dynamic.c:of_node_release
```
**Symbols:**

```
ffffffe000724852-ffffffe00072489e: property_list_free (STB_LOCAL)
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
