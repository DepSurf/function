# Function: <code>device_release_driver_internal</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815cc2c0)
Location: drivers/base/dd.c:845
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff815cc2c0-ffffffff815cc4c1: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815e0e70)
Location: drivers/base/dd.c:854
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff815e0e70-ffffffff815e1072: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81647f80)
Location: drivers/base/dd.c:894
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff81647f80-ffffffff8164819c: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81683460)
Location: drivers/base/dd.c:915
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff81683460-ffffffff816836ba: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a3160)
Location: drivers/base/dd.c:999
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff816a3160-ffffffff816a33b5: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dc040)
Location: drivers/base/dd.c:1151
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff816dc040-ffffffff816dc1f8: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81700070)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff81700070-ffffffff81700234: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817ba1f7)
Location: drivers/base/dd.c:1142
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
```
**Symbols:**

```
ffffffff817ba020-ffffffff817ba0b9: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817cf047)
Location: drivers/base/dd.c:1190
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
```
**Symbols:**

```
ffffffff817cee70-ffffffff817cef09: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b2a57)
Location: drivers/base/dd.c:1205
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
```
**Symbols:**

```
ffffffff817b2880-ffffffff817b2919: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff8183bee6)
Location: drivers/base/dd.c:1234
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
```
**Symbols:**

```
ffffffff81d0309e-ffffffff81d030c7: device_release_driver_internal.cold (STB_LOCAL)
ffffffff8183bcb0-ffffffff8183bd65: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1244
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff81ecb789-ffffffff81ecb7e8: device_release_driver_internal.cold (STB_LOCAL)
ffffffff8197e390-ffffffff8197e62a: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1272
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff820985d3-ffffffff82098632: device_release_driver_internal.cold (STB_LOCAL)
ffffffff81aeb900-ffffffff81aebb9a: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1288
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff82119605-ffffffff82119664: device_release_driver_internal.cold (STB_LOCAL)
ffffffff81b39b70-ffffffff81b39ddc: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:1288
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff821f75c8-ffffffff821f7627: device_release_driver_internal.cold (STB_LOCAL)
ffffffff81b91630-ffffffff81b9189c: device_release_driver_internal (STB_GLOBAL)
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
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108eb390)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffff8000108eb390-ffff8000108eb550: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d9488)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
c09d9488-c09d9648: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000982980)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
c000000000982980-c000000000982be0: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057f000)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffe00057f000-ffffffe00057f160: device_release_driver_internal (STB_GLOBAL)
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
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c5860)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff816c5860-ffffffff816c5a24: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a0ae0)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff816a0ae0-ffffffff816a0ca4: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f3d30)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff816f3d30-ffffffff816f3ef4: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_release_driver_internal(struct device *dev, struct device_driver *drv, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170e560)
Location: drivers/base/dd.c:1168
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
```
**Symbols:**

```
ffffffff8170e560-ffffffff8170e724: device_release_driver_internal (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
