# Function: <code>fwnode_connection_find_match</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff817074c0)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff817074c0-ffffffff81707601: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff817c21e0)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff817c21e0-ffffffff817c2326: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d6460)
Location: drivers/base/property.c:1296
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff817d6460-ffffffff817d66a2: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9ef0)
Location: drivers/base/property.c:1309
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff817b9ef0-ffffffff817ba163: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843b70)
Location: drivers/base/property.c:1320
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff81843b70-ffffffff81843dd0: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987d20)
Location: drivers/base/property.c:1285
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff81987d20-ffffffff81987dce: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *fwnode_connection_find_match(const struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af6690)
Location: drivers/base/property.c:1299
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff81af6690-ffffffff81af673e: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *fwnode_connection_find_match(const struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b44940)
Location: drivers/base/property.c:1360
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff81b44940-ffffffff81b449ee: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *fwnode_connection_find_match(const struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9c990)
Location: drivers/base/property.c:1424
Inline: False
Direct callers:
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
**Symbols:**

```
ffffffff81b9c990-ffffffff81b9ca3e: fwnode_connection_find_match (STB_GLOBAL)
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
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffff8000108f4d88)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffff8000108f4d88-ffff8000108f4edc: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (c09e1144)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
c09e1144-c09e12a8: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (c00000000098ee50)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
c00000000098ee50-c00000000098f094: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffe000586118)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffe000586118-ffffffe00058622e: fwnode_connection_find_match (STB_GLOBAL)
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
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816ccc10)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff816ccc10-ffffffff816ccd51: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816a7f40)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff816a7f40-ffffffff816a8081: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816fb180)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff816fb180-ffffffff816fb2c1: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *fwnode_connection_find_match(struct fwnode_handle *fwnode, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff81715a20)
Location: drivers/base/devcon.c:71
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff81715a20-ffffffff81715b61: fwnode_connection_find_match (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
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
