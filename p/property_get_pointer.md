# Function: <code>property_get_pointer</code>

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
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81689170)
Location: drivers/base/property.c:59
Inline: True
Direct callers:
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entry_free_data
  - drivers/base/property.c:pset_prop_find
```
**Symbols:**

```
ffffffff81689170-ffffffff816891a5: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa0a0)
Location: drivers/base/swnode.c:106
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entries_dup
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816aa0a0-ffffffff816aa0dc: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e3aa0)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816e3aa0-ffffffff816e3ad3: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81707c90)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff81707c90-ffffffff81707cc3: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c2ae5)
Location: drivers/base/swnode.c:106
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d78f5)
Location: drivers/base/swnode.c:106
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bbd84)
Location: drivers/base/swnode.c:120
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff818463b4)
Location: drivers/base/swnode.c:122
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198a4f7)
Location: drivers/base/swnode.c:122
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af91e5)
Location: drivers/base/swnode.c:122
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b47755)
Location: drivers/base/swnode.c:122
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b9fae5)
Location: drivers/base/swnode.c:122
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_copy_data
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_read_string_array
  - drivers/base/swnode.c:property_entry_read_int_array
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
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f5670)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffff8000108f5670-ffff8000108f56d8: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e1ac4)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
c09e1ac4-c09e1b20: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c000000000990120)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
c000000000990120-c0000000009901a0: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe0005868f4)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffe0005868f4-ffffffe000586942: property_get_pointer (STB_LOCAL)
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
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd3e0)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816cd3e0-ffffffff816cd413: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a8710)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816a8710-ffffffff816a8743: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fb950)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff816fb950-ffffffff816fb983: property_get_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const void *property_get_pointer(const struct property_entry *prop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817162d0)
Location: drivers/base/swnode.c:145
Inline: True
Direct callers:
  - drivers/base/swnode.c:property_entry_free_data
  - drivers/base/swnode.c:property_entry_find
```
**Symbols:**

```
ffffffff817162d0-ffffffff81716303: property_get_pointer (STB_LOCAL)
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
