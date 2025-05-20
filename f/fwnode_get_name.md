# Function: <code>fwnode_get_name</code>

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
const char *fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0200)
Location: drivers/base/property.c:565
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff817c0200-ffffffff817c022b: fwnode_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d50c0)
Location: drivers/base/property.c:565
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff817d50c0-ffffffff817d50eb: fwnode_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8ad0)
Location: drivers/base/property.c:565
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff817b8ad0-ffffffff817b8afb: fwnode_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842760)
Location: drivers/base/property.c:565
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81842760-ffffffff8184278b: fwnode_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986750)
Location: drivers/base/property.c:564
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81986750-ffffffff81986796: fwnode_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4e10)
Location: drivers/base/property.c:572
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81af4e10-ffffffff81af4e56: fwnode_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43020)
Location: drivers/base/property.c:579
Inline: False
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81b43020-ffffffff81b43066: fwnode_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9b905)
Location: drivers/base/property.c:615
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_name_eq
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81b9aef0-ffffffff81b9af36: fwnode_get_name (STB_GLOBAL)
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
