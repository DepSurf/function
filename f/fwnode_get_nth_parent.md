# Function: <code>fwnode_get_nth_parent</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_nth_parent(struct fwnode_handle *fwnode, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0c20)
Location: drivers/base/property.c:649
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff817c0c20-ffffffff817c0d02: fwnode_get_nth_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_nth_parent(struct fwnode_handle *fwnode, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5ba0)
Location: drivers/base/property.c:674
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff817d5ba0-ffffffff817d5c82: fwnode_get_nth_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_nth_parent(struct fwnode_handle *fwnode, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b95c0)
Location: drivers/base/property.c:674
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff817b95c0-ffffffff817b96a2: fwnode_get_nth_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_get_nth_parent(struct fwnode_handle *fwnode, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843220)
Location: drivers/base/property.c:675
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81843220-ffffffff81843302: fwnode_get_nth_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_nth_parent(struct fwnode_handle *fwnode, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987a30)
Location: drivers/base/property.c:672
Inline: True
Direct callers:
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81987a30-ffffffff81987b41: fwnode_get_nth_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_nth_parent(struct fwnode_handle *fwnode, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af6380)
Location: drivers/base/property.c:680
Inline: True
Direct callers:
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81af6380-ffffffff81af6491: fwnode_get_nth_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_nth_parent(struct fwnode_handle *fwnode, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b44610)
Location: drivers/base/property.c:696
Inline: True
Direct callers:
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81b44610-ffffffff81b44721: fwnode_get_nth_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_nth_parent(struct fwnode_handle *fwnode, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9c660)
Location: drivers/base/property.c:760
Inline: True
Direct callers:
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81b9c660-ffffffff81b9c771: fwnode_get_nth_parent (STB_GLOBAL)
```
</details>
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
