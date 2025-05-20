# Function: <code>fwnode_get_named_child_node</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e5f1c)
Location: drivers/base/property.c:981
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff815e5ee0-ffffffff815e5f07: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d25c)
Location: drivers/base/property.c:1025
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff8164d220-ffffffff8164d24a: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688b7c)
Location: drivers/base/property.c:1111
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff81688b40-ffffffff81688b6a: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a887c)
Location: drivers/base/property.c:634
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff816a8840-ffffffff816a886b: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e196c)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff816e1930-ffffffff816e195b: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705b1c)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff81705ae0-ffffffff81705b0b: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0b0c)
Location: drivers/base/property.c:737
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff817c0290-ffffffff817c02bb: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d59ac)
Location: drivers/base/property.c:789
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff817d5150-ffffffff817d517b: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b93bc)
Location: drivers/base/property.c:789
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff817b8b60-ffffffff817b8b8b: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8184301c)
Location: drivers/base/property.c:784
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff818427f0-ffffffff8184281b: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986e2c)
Location: drivers/base/property.c:784
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff81986840-ffffffff8198688c: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af564c)
Location: drivers/base/property.c:792
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff81af4f30-ffffffff81af4f7c: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b4387c)
Location: drivers/base/property.c:822
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff81b43140-ffffffff81b4318c: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9b7ec)
Location: drivers/base/property.c:886
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
Direct callers:
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
```
**Symbols:**

```
ffffffff81b9b010-ffffffff81b9b05c: fwnode_get_named_child_node (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f25e0)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffff8000108f2560-ffff8000108f25b8: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df234)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
c09df1cc-c09df210: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c030)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
c00000000098bfa0-c00000000098c00c: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584186)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffe00058411e-ffffffe000584162: fwnode_get_named_child_node (STB_GLOBAL)
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
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb26c)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff816cb230-ffffffff816cb25b: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a659c)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff816a6560-ffffffff816a658b: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f97dc)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff816f97a0-ffffffff816f97cb: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *fwnode_get_named_child_node(const struct fwnode_handle *fwnode, const char *childname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8171407c)
Location: drivers/base/property.c:658
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff81714040-ffffffff8171406b: fwnode_get_named_child_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
