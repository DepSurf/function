# Function: <code>device_connection_find_match</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, void * (*match)(struct device_connection *, int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff8168a7e0)
Location: drivers/base/devcon.c:25
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffff8168a7e0-ffffffff8168a8c1: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, void * (*match)(struct device_connection *, int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816a9cf0)
Location: drivers/base/devcon.c:25
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffff816a9cf0-ffffffff816a9dd1: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816e33d0)
Location: drivers/base/devcon.c:74
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffff816e33d0-ffffffff816e35ce: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff81707610)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffff81707610-ffffffff81707716: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff817c2330)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffff817c2330-ffffffff817c2436: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8192bb1d)
Location: include/linux/property.h:444
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8190f08d)
Location: include/linux/property.h:447
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff819afefd)
Location: include/linux/property.h:447
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81b0e786)
Location: include/linux/property.h:447
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81c9e9c6)
Location: include/linux/property.h:453
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81d05d06)
Location: include/linux/property.h:464
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81dbb7e1)
Location: include/linux/property.h:504
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_get
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
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffff8000108f4ee0)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffff8000108f4ee0-ffff8000108f502c: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (c09e12a8)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
c09e12a8-c09e13b8: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (c00000000098f0a0)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
c00000000098f0a0-c00000000098f438: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffe00058622e)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffe00058622e-ffffffe000586322: device_connection_find_match (STB_GLOBAL)
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
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816ccd60)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffff816ccd60-ffffffff816cce66: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816a8090)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffff816a8090-ffffffff816a8196: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816fb2d0)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffff816fb2d0-ffffffff816fb3d6: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *device_connection_find_match(struct device *dev, const char *con_id, void *data, devcon_match_fn_t match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff81715b70)
Location: drivers/base/devcon.c:99
Inline: False
Direct callers:
  - drivers/base/devcon.c:device_connection_find
```
**Symbols:**

```
ffffffff81715b70-ffffffff81715c76: device_connection_find_match (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * (*match)(struct device_connection *, int, void *)</code> ➡️ <code>devcon_match_fn_t match</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
