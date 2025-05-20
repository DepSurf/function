# Function: <code>pset_prop_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *pset_prop_find(struct property_set *pset, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81550f80)
Location: drivers/base/property.c:48
Inline: False
Direct callers:
  - drivers/base/property.c:pset_prop_read_string_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
```
**Symbols:**

```
ffffffff81550f80-ffffffff81550fcf: pset_prop_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *pset_prop_find(struct property_set *pset, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a2e50)
Location: drivers/base/property.c:53
Inline: False
Direct callers:
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
```
**Symbols:**

```
ffffffff815a2e50-ffffffff815a2e9f: pset_prop_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *pset_prop_find(struct property_set *pset, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1560)
Location: drivers/base/property.c:53
Inline: False
Direct callers:
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
```
**Symbols:**

```
ffffffff815d1560-ffffffff815d15af: pset_prop_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const void *pset_prop_find(struct property_set *pset, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6620)
Location: drivers/base/property.c:54
Inline: False
Direct callers:
  - drivers/base/property.c:pset_fwnode_property_read_string_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_read_int_array
```
**Symbols:**

```
ffffffff815e6620-ffffffff815e6673: pset_prop_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const void *pset_prop_find(const struct property_set *pset, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d990)
Location: drivers/base/property.c:61
Inline: False
Direct callers:
  - drivers/base/property.c:pset_fwnode_property_read_string_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_read_int_array
```
**Symbols:**

```
ffffffff8164d990-ffffffff8164d9e3: pset_prop_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const void *pset_prop_find(const struct property_set *pset, const char *propname, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81689320)
Location: drivers/base/property.c:125
Inline: False
Direct callers:
  - drivers/base/property.c:pset_fwnode_property_read_string_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_read_int_array
```
**Symbols:**

```
ffffffff81689320-ffffffff81689370: pset_prop_find (STB_LOCAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>const void *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct property_set *pset</code> ➡️ <code>const struct property_set *pset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
