# Function: <code>device_property_read_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551690)
Location: drivers/base/property.c:367
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
Direct callers:
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/common/common.c:usb_get_dr_mode
```
**Symbols:**

```
ffffffff81551690-ffffffff815516a7: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a3326)
Location: drivers/base/property.c:373
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff815a3100-ffffffff815a3117: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1a36)
Location: drivers/base/property.c:373
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff815d1810-ffffffff815d1827: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6936)
Location: drivers/base/property.c:405
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
Direct callers:
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff815e6440-ffffffff815e6466: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164dd56)
Location: drivers/base/property.c:414
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
Direct callers:
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff8164d7b0-ffffffff8164d7d6: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816889f0)
Location: drivers/base/property.c:475
Inline: False
Direct callers:
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff816889f0-ffffffff81688a16: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a86e0)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff816a86e0-ffffffff816a8706: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1f30)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffff816e1f30-ffffffff816e1f56: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817060e0)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffff817060e0-ffffffff81706106: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0750)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffff817c0750-ffffffff817c0776: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5610)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffff817d5610-ffffffff817d5636: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9050)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffff817b9050-ffffffff817b9073: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842cb0)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffff81842cb0-ffffffff81842cd3: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff819865c0)
Location: drivers/base/property.c:216
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff819865c0-ffffffff819865ef: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4c50)
Location: drivers/base/property.c:223
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81af4c50-ffffffff81af4c7f: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_property_read_string(const struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42e60)
Location: drivers/base/property.c:227
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81b42e60-ffffffff81b42e8f: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_property_read_string(const struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9ad30)
Location: drivers/base/property.c:227
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_role_switch_default_mode
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_ssp_rate
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81b9ad30-ffffffff81b9ad5f: device_property_read_string (STB_GLOBAL)
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
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2f18)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffff8000108f2f18-ffff8000108f2f78: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df9f8)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
c09df9f8-c09dfa2c: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098cb60)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
c00000000098cb60-c00000000098cbc8: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe0005848a8)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffe0005848a8-ffffffe0005848fe: device_property_read_string (STB_GLOBAL)
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
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb830)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffff816cb830-ffffffff816cb856: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6b60)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
```
**Symbols:**

```
ffffffff816a6b60-ffffffff816a6b86: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9da0)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffff816f9da0-ffffffff816f9dc6: device_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_property_read_string(struct device *dev, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714640)
Location: drivers/base/property.c:200
Inline: False
Direct callers:
  - drivers/usb/common/common.c:usb_get_dr_mode
  - drivers/usb/common/common.c:usb_get_maximum_speed
  - drivers/usb/dwc2/debugfs.c:dr_mode_show
```
**Symbols:**

```
ffffffff81714640-ffffffff81714666: device_property_read_string (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
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
