# Function: <code>fwnode_property_read_int_array</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int fwnode_property_read_int_array(struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6140)
Location: drivers/base/property.c:434
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff815e6140-ffffffff815e61ff: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d4a0)
Location: drivers/base/property.c:443
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
```
**Symbols:**

```
ffffffff8164d4a0-ffffffff8164d564: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688700)
Location: drivers/base/property.c:504
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff81688700-ffffffff816887c4: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a83f0)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816a83f0-ffffffff816a84b4: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1bf0)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816e1bf0-ffffffff816e1caa: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705da0)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff81705da0-ffffffff81705e5a: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0460)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff817c0460-ffffffff817c051a: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5320)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff817d5320-ffffffff817d53da: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8d60)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff817b8d60-ffffffff817b8e1a: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818429c0)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff818429c0-ffffffff81842a7a: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff819861c0)
Location: drivers/base/property.c:245
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff819861c0-ffffffff819862b4: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4790)
Location: drivers/base/property.c:252
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff81af4790-ffffffff81af4884: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b429a0)
Location: drivers/base/property.c:256
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff81b429a0-ffffffff81b42a94: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9a870)
Location: drivers/base/property.c:256
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff81b9a870-ffffffff81b9a964: fwnode_property_read_int_array (STB_LOCAL)
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
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2958)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffff8000108f2958-ffff8000108f2a40: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df5f4)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
c09df5f4-c09df6bc: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c680)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
c00000000098c680-c00000000098c7c8: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe0005844aa)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffe0005844aa-ffffffe000584528: fwnode_property_read_int_array (STB_LOCAL)
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
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb4f0)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816cb4f0-ffffffff816cb5aa: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6820)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816a6820-ffffffff816a68da: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9a60)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff816f9a60-ffffffff816f9b1a: fwnode_property_read_int_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fwnode_property_read_int_array(const struct fwnode_handle *fwnode, const char *propname, unsigned int elem_size, void *val, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714300)
Location: drivers/base/property.c:229
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_mac_addr
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
```
**Symbols:**

```
ffffffff81714300-ffffffff817143ba: fwnode_property_read_int_array (STB_LOCAL)
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
