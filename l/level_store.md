# Function: <code>level_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81618f40)
Location: drivers/usb/core/sysfs.c:419
Inline: False
```
```
In drivers/md/md.c (ffffffff81696640)
Location: drivers/md/md.c:3424
Inline: False
```
**Symbols:**

```
ffffffff81618f40-ffffffff81619039: level_store (STB_LOCAL)
ffffffff81696640-ffffffff81696d6e: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff816790e0)
Location: drivers/usb/core/sysfs.c:433
Inline: False
```
```
In drivers/md/md.c (ffffffff816f7600)
Location: drivers/md/md.c:3430
Inline: False
```
**Symbols:**

```
ffffffff816790e0-ffffffff816791eb: level_store (STB_LOCAL)
ffffffff816f7600-ffffffff816f7d2b: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff816a6dc0)
Location: drivers/usb/core/sysfs.c:447
Inline: False
```
```
In drivers/md/md.c (ffffffff81729330)
Location: drivers/md/md.c:3465
Inline: False
```
**Symbols:**

```
ffffffff816a6dc0-ffffffff816a6ecb: level_store (STB_LOCAL)
ffffffff81729330-ffffffff81729a64: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff816bc120)
Location: drivers/usb/core/sysfs.c:447
Inline: False
```
```
In drivers/md/md.c (ffffffff81741af0)
Location: drivers/md/md.c:3601
Inline: False
```
**Symbols:**

```
ffffffff816bc120-ffffffff816bc233: level_store (STB_LOCAL)
ffffffff81741af0-ffffffff81742227: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81727ae0)
Location: drivers/usb/core/sysfs.c:447
Inline: False
```
```
In drivers/md/md.c (ffffffff817b3c10)
Location: drivers/md/md.c:3656
Inline: False
```
**Symbols:**

```
ffffffff81727ae0-ffffffff81727bf3: level_store (STB_LOCAL)
ffffffff817b3c10-ffffffff817b4356: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:467
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3672
Inline: False
```
**Symbols:**

```
ffffffff81766940-ffffffff81766a35: level_store (STB_LOCAL)
ffffffff81766c8b-ffffffff81766ca6: level_store.cold.7 (STB_LOCAL)
ffffffff817fa7f0-ffffffff817fade3: level_store (STB_LOCAL)
ffffffff81800a6a-ffffffff81800b46: level_store.cold.86 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:467
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3663
Inline: False
```
**Symbols:**

```
ffffffff8178aec0-ffffffff8178afb5: level_store (STB_LOCAL)
ffffffff8178b20b-ffffffff8178b226: level_store.cold.7 (STB_LOCAL)
ffffffff81826860-ffffffff81826e53: level_store (STB_LOCAL)
ffffffff8182cc6d-ffffffff8182cd49: level_store.cold.85 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3730
Inline: False
```
**Symbols:**

```
ffffffff817c9470-ffffffff817c9559: level_store (STB_LOCAL)
ffffffff817c980b-ffffffff817c9826: level_store.cold (STB_LOCAL)
ffffffff81868ca0-ffffffff818692e5: level_store (STB_LOCAL)
ffffffff8186f212-ffffffff8186f2ff: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3788
Inline: False
```
**Symbols:**

```
ffffffff817f9fb0-ffffffff817fa099: level_store (STB_LOCAL)
ffffffff817fa34b-ffffffff817fa366: level_store.cold (STB_LOCAL)
ffffffff8189aa40-ffffffff8189b085: level_store (STB_LOCAL)
ffffffff818a0fd5-ffffffff818a10c2: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3913
Inline: False
```
**Symbols:**

```
ffffffff818ca1a0-ffffffff818ca289: level_store (STB_LOCAL)
ffffffff818ca56e-ffffffff818ca589: level_store.cold (STB_LOCAL)
ffffffff8196b480-ffffffff8196bb31: level_store (STB_LOCAL)
ffffffff81970e37-ffffffff81970f16: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3934
Inline: False
```
**Symbols:**

```
ffffffff818d52f0-ffffffff818d53d9: level_store (STB_LOCAL)
ffffffff81c1df89-ffffffff81c1dfa4: level_store.cold (STB_LOCAL)
ffffffff81972010-ffffffff81972800: level_store (STB_LOCAL)
ffffffff81c26f20-ffffffff81c26ffc: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:471
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3898
Inline: False
```
**Symbols:**

```
ffffffff818b88b0-ffffffff818b8999: level_store (STB_LOCAL)
ffffffff81c0fe6e-ffffffff81c0fe89: level_store.cold (STB_LOCAL)
ffffffff81956100-ffffffff819568e8: level_store (STB_LOCAL)
ffffffff81c190d1-ffffffff81c191ad: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:448
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3917
Inline: False
```
**Symbols:**

```
ffffffff8194e380-ffffffff8194e469: level_store (STB_LOCAL)
ffffffff81d16f34-ffffffff81d16f4f: level_store.cold (STB_LOCAL)
ffffffff819fb730-ffffffff819fbf90: level_store (STB_LOCAL)
ffffffff81d286ed-ffffffff81d287d3: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:448
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3907
Inline: False
```
**Symbols:**

```
ffffffff81aa7310-ffffffff81aa740a: level_store (STB_LOCAL)
ffffffff81ee1e63-ffffffff81ee1e7e: level_store.cold (STB_LOCAL)
ffffffff81b62dc0-ffffffff81b635d4: level_store (STB_LOCAL)
ffffffff81ef475a-ffffffff81ef483f: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81c2e140)
Location: drivers/usb/core/sysfs.c:449
Inline: False
```
```
In drivers/md/md.c (ffffffff81cfd0e0)
Location: drivers/md/md.c:3869
Inline: False
```
**Symbols:**

```
ffffffff81c2e140-ffffffff81c2e255: level_store (STB_LOCAL)
ffffffff81cfd0e0-ffffffff81cfd99d: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81c95330)
Location: drivers/usb/core/sysfs.c:449
Inline: False
```
```
In drivers/md/md.c (ffffffff81d684b0)
Location: drivers/md/md.c:3855
Inline: False
```
**Symbols:**

```
ffffffff81c95330-ffffffff81c95445: level_store (STB_LOCAL)
ffffffff81d684b0-ffffffff81d68d74: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81d49df0)
Location: drivers/usb/core/sysfs.c:446
Inline: False
```
```
In drivers/md/md.c (ffffffff81e22330)
Location: drivers/md/md.c:3983
Inline: False
```
**Symbols:**

```
ffffffff81d49df0-ffffffff81d49f05: level_store (STB_LOCAL)
ffffffff81e22330-ffffffff81e22bc6: level_store (STB_LOCAL)
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
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffff800010a2b348)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (ffff800010aeee20)
Location: drivers/md/md.c:3788
Inline: False
```
**Symbols:**

```
ffff800010a2b348-ffff800010a2b460: level_store (STB_LOCAL)
ffff800010aeee20-ffff800010aef43c: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (c0b00e90)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (c0bd02d8)
Location: drivers/md/md.c:3788
Inline: False
```
**Symbols:**

```
c0b00e90-c0b00f88: level_store (STB_LOCAL)
c0bd02d8-c0bd0998: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (c000000000ae81b0)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (c000000000bda3c0)
Location: drivers/md/md.c:3788
Inline: False
```
**Symbols:**

```
c000000000ae81b0-c000000000ae8398: level_store (STB_LOCAL)
c000000000bda3c0-c000000000bdacd4: level_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffe00064c904)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (ffffffe0006e3214)
Location: drivers/md/md.c:3788
Inline: False
```
**Symbols:**

```
ffffffe0006e3214-ffffffe0006e382c: level_store (STB_LOCAL)
ffffffe00064c904-ffffffe00064c9fa: level_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3788
Inline: False
```
**Symbols:**

```
ffffffff817b2390-ffffffff817b2479: level_store (STB_LOCAL)
ffffffff817b272b-ffffffff817b2746: level_store.cold (STB_LOCAL)
ffffffff818408c0-ffffffff81840f05: level_store (STB_LOCAL)
ffffffff81846e55-ffffffff81846f42: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3788
Inline: False
```
**Symbols:**

```
ffffffff817a3dc0-ffffffff817a3ea9: level_store (STB_LOCAL)
ffffffff817a415b-ffffffff817a4176: level_store.cold (STB_LOCAL)
ffffffff81807f20-ffffffff81808565: level_store (STB_LOCAL)
ffffffff8180e4b5-ffffffff8180e5a2: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3788
Inline: False
```
**Symbols:**

```
ffffffff817eee30-ffffffff817eef19: level_store (STB_LOCAL)
ffffffff817ef1cb-ffffffff817ef1e6: level_store.cold (STB_LOCAL)
ffffffff8188fef0-ffffffff81890535: level_store (STB_LOCAL)
ffffffff81896485-ffffffff81896572: level_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:468
Inline: False
```
```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3788
Inline: False
```
**Symbols:**

```
ffffffff81809070-ffffffff81809159: level_store (STB_LOCAL)
ffffffff8180940b-ffffffff81809426: level_store.cold (STB_LOCAL)
ffffffff818abae0-ffffffff818ac121: level_store (STB_LOCAL)
ffffffff818b2465-ffffffff818b2552: level_store.cold (STB_LOCAL)
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
