# Function: <code>property_entry_read_int_array</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa328)
Location: drivers/base/swnode.c:224
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e3d26)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81707f16)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int property_entry_read_int_array(const struct property_entry *props, const char *name, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c3290)
Location: drivers/base/swnode.c:144
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff817c3290-ffffffff817c3337: property_entry_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int property_entry_read_int_array(const struct property_entry *props, const char *name, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d81b0)
Location: drivers/base/swnode.c:144
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff817d81b0-ffffffff817d8257: property_entry_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int property_entry_read_int_array(const struct property_entry *props, const char *name, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bbb50)
Location: drivers/base/swnode.c:158
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff817bbb50-ffffffff817bbc6a: property_entry_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int property_entry_read_int_array(const struct property_entry *props, const char *name, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:160
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff81845e20-ffffffff81845f4e: property_entry_read_int_array (STB_LOCAL)
ffffffff81d03477-ffffffff81d0348b: property_entry_read_int_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int property_entry_read_int_array(const struct property_entry *props, const char *name, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:160
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff8198a1d0-ffffffff8198a30f: property_entry_read_int_array (STB_LOCAL)
ffffffff81ecbbdd-ffffffff81ecbbf2: property_entry_read_int_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int property_entry_read_int_array(const struct property_entry *props, const char *name, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:160
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff81af95a0-ffffffff81af96df: property_entry_read_int_array (STB_LOCAL)
ffffffff82098845-ffffffff8209885a: property_entry_read_int_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int property_entry_read_int_array(const struct property_entry *props, const char *name, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:160
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff81b47b50-ffffffff81b47c8f: property_entry_read_int_array (STB_LOCAL)
ffffffff82119857-ffffffff8211986c: property_entry_read_int_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int property_entry_read_int_array(const struct property_entry *props, const char *name, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:160
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_read_int_array
```
**Symbols:**

```
ffffffff81b9fee0-ffffffff81ba001f: property_entry_read_int_array (STB_LOCAL)
ffffffff821f7819-ffffffff821f782e: property_entry_read_int_array.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f59bc)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e1da0)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c0000000009907bc)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe000586ba6)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd666)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a8996)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fbbd6)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716556)
Location: drivers/base/swnode.c:263
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_int_array
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
