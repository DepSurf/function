# Function: <code>location_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t location_show(struct mddev *mddev, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169bd90)
Location: drivers/md/bitmap.c:2107
Inline: False
```
**Symbols:**

```
ffffffff8169bd90-ffffffff8169be15: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t location_show(struct mddev *mddev, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fcec0)
Location: drivers/md/bitmap.c:2170
Inline: False
```
**Symbols:**

```
ffffffff816fcec0-ffffffff816fcf45: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t location_show(struct mddev *mddev, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172ea90)
Location: drivers/md/bitmap.c:2198
Inline: False
```
**Symbols:**

```
ffffffff8172ea90-ffffffff8172eb15: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t location_show(struct mddev *mddev, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff817479e0)
Location: drivers/md/bitmap.c:2241
Inline: False
```
**Symbols:**

```
ffffffff817479e0-ffffffff81747a65: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t location_show(struct mddev *mddev, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817b9c70)
Location: drivers/md/md-bitmap.c:2260
Inline: False
```
**Symbols:**

```
ffffffff817b9c70-ffffffff817b9cf5: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t location_show(struct mddev *mddev, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81801cf0)
Location: drivers/md/md-bitmap.c:2260
Inline: False
```
**Symbols:**

```
ffffffff81801cf0-ffffffff81801d72: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81791b90)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff8182df00)
Location: drivers/md/md-bitmap.c:2251
Inline: False
```
**Symbols:**

```
ffffffff81791b90-ffffffff81791bb8: location_show (STB_LOCAL)
ffffffff8182df00-ffffffff8182df82: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff817d0360)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff81870580)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffffffff817d0360-ffffffff817d0389: location_show (STB_LOCAL)
ffffffff81870580-ffffffff81870602: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81801230)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff818a2370)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffffffff81801230-ffffffff81801259: location_show (STB_LOCAL)
ffffffff818a2370-ffffffff818a23f2: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff818d1980)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff81971dd0)
Location: drivers/md/md-bitmap.c:2253
Inline: False
```
**Symbols:**

```
ffffffff818d1980-ffffffff818d19a9: location_show (STB_LOCAL)
ffffffff81971dd0-ffffffff81971e39: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff818dbd60)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff81976ce0)
Location: drivers/md/md-bitmap.c:2256
Inline: False
```
**Symbols:**

```
ffffffff818dbd60-ffffffff818dbd89: location_show (STB_LOCAL)
ffffffff81976ce0-ffffffff81976d49: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff818bf120)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff8195af20)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffffffff818bf120-ffffffff818bf149: location_show (STB_LOCAL)
ffffffff8195af20-ffffffff8195af89: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81955780)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff81a00710)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffffffff81955780-ffffffff819557a9: location_show (STB_LOCAL)
ffffffff81a00710-ffffffff81a00779: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81aaf3e0)
Location: drivers/usb/core/port.c:20
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff81b68000)
Location: drivers/md/md-bitmap.c:2259
Inline: False
```
**Symbols:**

```
ffffffff81aaf3e0-ffffffff81aaf412: location_show (STB_LOCAL)
ffffffff81b68000-ffffffff81b6806e: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81c37110)
Location: drivers/usb/core/port.c:129
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff81d03a40)
Location: drivers/md/md-bitmap.c:2263
Inline: False
```
**Symbols:**

```
ffffffff81c37110-ffffffff81c37142: location_show (STB_LOCAL)
ffffffff81d03a40-ffffffff81d03aae: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81c9e400)
Location: drivers/usb/core/port.c:129
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff81d6c8f0)
Location: drivers/md/md-bitmap.c:2329
Inline: False
```
**Symbols:**

```
ffffffff81c9e400-ffffffff81c9e432: location_show (STB_LOCAL)
ffffffff81d6c8f0-ffffffff81d6c95e: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81d53000)
Location: drivers/usb/core/port.c:129
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff81e23b20)
Location: drivers/md/md-bitmap.c:2333
Inline: False
```
**Symbols:**

```
ffffffff81d53000-ffffffff81d53032: location_show (STB_LOCAL)
ffffffff81e23b20-ffffffff81e23b8e: location_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffff800010a35508)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffff800010af6318)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffff800010a35508-ffff800010a35548: location_show (STB_LOCAL)
ffff800010af6318-ffff800010af63b0: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (c0b08d00)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (c0bd7dc8)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
c0b08d00-c0b08d34: location_show (STB_LOCAL)
c0bd7dc8-c0bd7e54: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (c000000000af34e0)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (c000000000be3820)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
c000000000af34e0-c000000000af352c: location_show (STB_LOCAL)
c000000000be3820-c000000000be3904: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffe000652de8)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffe0006e8fea)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffffffe000652de8-ffffffe000652e26: location_show (STB_LOCAL)
ffffffe0006e8fea-ffffffe0006e907a: location_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff817b9610)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff818481f0)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffffffff817b9610-ffffffff817b9639: location_show (STB_LOCAL)
ffffffff818481f0-ffffffff81848272: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff817ab040)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff8180f850)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffffffff817ab040-ffffffff817ab069: location_show (STB_LOCAL)
ffffffff8180f850-ffffffff8180f8d2: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff817f60b0)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff81897820)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffffffff817f60b0-ffffffff817f60d9: location_show (STB_LOCAL)
ffffffff81897820-ffffffff818978a2: location_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t location_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff818102f0)
Location: drivers/usb/core/port.c:19
Inline: False
```
```
In drivers/md/md-bitmap.c (ffffffff818b3a00)
Location: drivers/md/md-bitmap.c:2258
Inline: False
```
**Symbols:**

```
ffffffff818102f0-ffffffff81810319: location_show (STB_LOCAL)
ffffffff818b3a00-ffffffff818b3a82: location_show (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>struct device_attribute *attr</code>
</li>
<li>
<b>Param added. </b>
<code>char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mddev *mddev</code>
</li>
<li>
<b>Param removed. </b>
<code>char *page</code>
</li>
</ul>
</details>
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
