# Function: <code>fwnode_find_reference</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e17e0)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff816e17e0-ffffffff816e1858: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705990)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81705990-ffffffff81705a08: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0b40)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff817c0b40-ffffffff817c0bb8: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d65d1)
Location: drivers/base/property.c:498
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff817d59e0-ffffffff817d5a58: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817ba0b9)
Location: drivers/base/property.c:498
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff817b93f0-ffffffff817b9466: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843d82)
Location: drivers/base/property.c:498
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81843050-ffffffff818430c6: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986f96)
Location: drivers/base/property.c:545
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
```
**Symbols:**

```
ffffffff819866d0-ffffffff81986742: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af57d6)
Location: drivers/base/property.c:553
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
```
**Symbols:**

```
ffffffff81af4d80-ffffffff81af4df2: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43a06)
Location: drivers/base/property.c:560
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
```
**Symbols:**

```
ffffffff81b42f90-ffffffff81b43002: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9ba56)
Location: drivers/base/property.c:596
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
```
**Symbols:**

```
ffffffff81b9ae60-ffffffff81b9aed2: fwnode_find_reference (STB_GLOBAL)
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
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2388)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffff8000108f2388-ffff8000108f2434: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09defd4)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c09defd4-c09df074: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098bc80)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c00000000098bc80-c00000000098bd50: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000583f8e)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffe000583f8e-ffffffe000583ff4: fwnode_find_reference (STB_GLOBAL)
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
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb0e0)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816cb0e0-ffffffff816cb158: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6410)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816a6410-ffffffff816a6488: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9650)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816f9650-ffffffff816f96c8: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *fwnode_find_reference(const struct fwnode_handle *fwnode, const char *name, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81713ef0)
Location: drivers/base/property.c:498
Inline: False
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81713ef0-ffffffff81713f68: fwnode_find_reference (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
