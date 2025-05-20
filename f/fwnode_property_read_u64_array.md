# Function: <code>fwnode_property_read_u64_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fwnode_property_read_u64_array(struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551010)
Location: drivers/base/property.c:528
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff81551010-ffffffff81551119: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fwnode_property_read_u64_array(struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a3a90)
Location: drivers/base/property.c:535
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff815a3a90-ffffffff815a3c08: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fwnode_property_read_u64_array(struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d21a0)
Location: drivers/base/property.c:535
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff815d21a0-ffffffff815d2318: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6316)
Location: drivers/base/property.c:548
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff815e62f0-ffffffff815e630b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d686)
Location: drivers/base/property.c:557
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff8164d660-ffffffff8164d67b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688865)
Location: drivers/base/property.c:618
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff816888f0-ffffffff8168890b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8555)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff816a85e0-ffffffff816a85fb: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1e15)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff816e1df0-ffffffff816e1e0b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705fc5)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff81705fa0-ffffffff81705fbb: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0635)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff817c0610-ffffffff817c062b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5500)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff817d54d0-ffffffff817d54eb: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8f40)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff817b8f10-ffffffff817b8f2b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842ba0)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff81842b70-ffffffff81842b8b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986450)
Location: drivers/base/property.c:372
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff81986410-ffffffff8198643a: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4aa0)
Location: drivers/base/property.c:379
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff81af4a50-ffffffff81af4a7a: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42cb0)
Location: drivers/base/property.c:383
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff81b42c60-ffffffff81b42c8a: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9ab80)
Location: drivers/base/property.c:383
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
Direct callers:
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
```
**Symbols:**

```
ffffffff81b9ab30-ffffffff81b9ab5a: fwnode_property_read_u64_array (STB_GLOBAL)
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
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2d54)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffff8000108f2cd0-ffff8000108f2d20: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df8ec)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
c09df890-c09df8c4: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c978)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
c00000000098c920-c00000000098c944: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe00058475a)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffe0005846ea-ffffffe00058472e: fwnode_property_read_u64_array (STB_GLOBAL)
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
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb715)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff816cb6f0-ffffffff816cb70b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6a45)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff816a6a20-ffffffff816a6a3b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9c85)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff816f9c60-ffffffff816f9c7b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u64_array(const struct fwnode_handle *fwnode, const char *propname, u64 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714525)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u64_array
```
**Symbols:**

```
ffffffff81714500-ffffffff8171451b: fwnode_property_read_u64_array (STB_GLOBAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
