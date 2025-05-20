# Function: <code>fwnode_property_read_u16_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fwnode_property_read_u16_array(struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551be0)
Location: drivers/base/property.c:476
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff81551be0-ffffffff81551d32: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fwnode_property_read_u16_array(struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a3760)
Location: drivers/base/property.c:483
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff815a3760-ffffffff815a38cd: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fwnode_property_read_u16_array(struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1e70)
Location: drivers/base/property.c:483
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff815d1e70-ffffffff815d1fdd: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6276)
Location: drivers/base/property.c:496
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff815e6250-ffffffff815e626b: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d5e6)
Location: drivers/base/property.c:505
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff8164d5c0-ffffffff8164d5db: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688805)
Location: drivers/base/property.c:566
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff816888b0-ffffffff816888cb: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a84f5)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff816a85a0-ffffffff816a85bb: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1d75)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff816e1d50-ffffffff816e1d6b: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705f25)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff81705f00-ffffffff81705f1b: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0595)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff817c0570-ffffffff817c058b: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5460)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff817d5430-ffffffff817d544b: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8ea0)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff817b8e70-ffffffff817b8e8b: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842b00)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff81842ad0-ffffffff81842aeb: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986370)
Location: drivers/base/property.c:314
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff81986330-ffffffff8198635a: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4980)
Location: drivers/base/property.c:321
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff81af4930-ffffffff81af495a: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42b90)
Location: drivers/base/property.c:325
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff81b42b40-ffffffff81b42b6a: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9aa60)
Location: drivers/base/property.c:325
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff81b9aa10-ffffffff81b9aa3a: fwnode_property_read_u16_array (STB_GLOBAL)
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
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2bf4)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffff8000108f2b70-ffff8000108f2bc0: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df804)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
c09df7a8-c09df7dc: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c898)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
c00000000098c840-c00000000098c864: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe00058462e)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffe0005845be-ffffffe000584602: fwnode_property_read_u16_array (STB_GLOBAL)
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
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb675)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff816cb650-ffffffff816cb66b: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a69a5)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff816a6980-ffffffff816a699b: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9be5)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff816f9bc0-ffffffff816f9bdb: fwnode_property_read_u16_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u16_array(const struct fwnode_handle *fwnode, const char *propname, u16 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714485)
Location: drivers/base/property.c:291
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff81714460-ffffffff8171447b: fwnode_property_read_u16_array (STB_GLOBAL)
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
