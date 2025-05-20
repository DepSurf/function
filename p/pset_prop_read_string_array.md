# Function: <code>pset_prop_read_string_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pset_prop_read_string_array(struct property_set *pset, const char *propname, const char **strings, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81550fd0)
Location: drivers/base/property.c:140
Inline: False
Direct callers:
  - drivers/base/property.c:__fwnode_property_read_string_array
```
**Symbols:**

```
ffffffff81550fd0-ffffffff8155100c: pset_prop_read_string_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a2ee0)
Location: drivers/base/property.c:145
Inline: True
Inline callers:
  - drivers/base/property.c:__fwnode_property_read_string_array
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d15f0)
Location: drivers/base/property.c:145
Inline: True
Inline callers:
  - drivers/base/property.c:__fwnode_property_read_string_array
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6828)
Location: drivers/base/property.c:146
Inline: True
Inline callers:
  - drivers/base/property.c:pset_fwnode_property_read_string_array
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164dba6)
Location: drivers/base/property.c:153
Inline: True
Inline callers:
  - drivers/base/property.c:pset_fwnode_property_read_string_array
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816894f6)
Location: drivers/base/property.c:214
Inline: True
Inline callers:
  - drivers/base/property.c:pset_fwnode_property_read_string_array
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
</ul>
