# Function: <code>property_entry_find</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa1b0)
Location: drivers/base/swnode.c:134
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff816aa1b0-ffffffff816aa214: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e3bb0)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff816e3bb0-ffffffff816e3c0d: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81707da0)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff81707da0-ffffffff81707dfd: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c31e0)
Location: drivers/base/swnode.c:114
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
**Symbols:**

```
ffffffff817c31e0-ffffffff817c3282: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d8100)
Location: drivers/base/swnode.c:114
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:property_entry_read_int_array
```
**Symbols:**

```
ffffffff817d8100-ffffffff817d81a2: property_entry_find (STB_LOCAL)
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
In drivers/base/swnode.c (ffffffff817bbd60)
Location: drivers/base/swnode.c:128
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff81846390)
Location: drivers/base/swnode.c:130
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff8198a4d4)
Location: drivers/base/swnode.c:130
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff81af98b2)
Location: drivers/base/swnode.c:130
Inline: True
Inline callers:
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
In drivers/base/swnode.c (ffffffff81b47e62)
Location: drivers/base/swnode.c:130
Inline: True
Inline callers:
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
In drivers/base/swnode.c (ffffffff81ba01f2)
Location: drivers/base/swnode.c:130
Inline: True
Inline callers:
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
<summary>In <code>arm64</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f57e8)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffff8000108f57e8-ffff8000108f5874: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e1c24)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
c09e1c24-c09e1c7c: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c0000000009904e0)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
c0000000009904e0-c0000000009905b8: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe000586a20)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffe000586a20-ffffffe000586aa2: property_entry_find (STB_LOCAL)
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
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd4f0)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff816cd4f0-ffffffff816cd54d: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a8820)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff816a8820-ffffffff816a887d: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fba60)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff816fba60-ffffffff816fbabd: property_entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const void *property_entry_find(const struct property_entry *props, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817163e0)
Location: drivers/base/swnode.c:173
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff817163e0-ffffffff8171643d: property_entry_find (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
