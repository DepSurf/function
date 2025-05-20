# Function: <code>__fwnode_property_read_string_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __fwnode_property_read_string_array(struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551140)
Location: drivers/base/property.c:536
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
```
**Symbols:**

```
ffffffff81551140-ffffffff815511a2: __fwnode_property_read_string_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __fwnode_property_read_string_array(struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a2ea0)
Location: drivers/base/property.c:543
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
```
**Symbols:**

```
ffffffff815a2ea0-ffffffff815a2f45: __fwnode_property_read_string_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __fwnode_property_read_string_array(struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d15b0)
Location: drivers/base/property.c:543
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
```
**Symbols:**

```
ffffffff815d15b0-ffffffff815d1655: __fwnode_property_read_string_array (STB_LOCAL)
```
</details>
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
</ul>
