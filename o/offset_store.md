# Function: <code>offset_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *devattr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81683c90)
Location: drivers/thermal/thermal_core.c:988
Inline: False
```
```
In drivers/md/md.c (ffffffff8168ce90)
Location: drivers/md/md.c:2837
Inline: False
```
**Symbols:**

```
ffffffff81683c90-ffffffff81683d14: offset_store (STB_LOCAL)
ffffffff8168ce90-ffffffff8168cf35: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-sysfs.c (ffffffff816d6a00)
Location: drivers/rtc/rtc-sysfs.c:235
Inline: False
```
```
In drivers/thermal/thermal_core.c (ffffffff816e52f0)
Location: drivers/thermal/thermal_core.c:992
Inline: False
```
```
In drivers/md/md.c (ffffffff816ee570)
Location: drivers/md/md.c:2845
Inline: False
```
**Symbols:**

```
ffffffff816d6a00-ffffffff816d6a71: offset_store (STB_LOCAL)
ffffffff816e52f0-ffffffff816e5374: offset_store (STB_LOCAL)
ffffffff816ee570-ffffffff816ee615: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-sysfs.c (ffffffff817066e0)
Location: drivers/rtc/rtc-sysfs.c:235
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81718e30)
Location: drivers/thermal/thermal_sysfs.c:391
Inline: False
```
```
In drivers/md/md.c (ffffffff8171fcf0)
Location: drivers/md/md.c:2890
Inline: False
```
**Symbols:**

```
ffffffff817066e0-ffffffff81706751: offset_store (STB_LOCAL)
ffffffff81718e30-ffffffff81718eb4: offset_store (STB_LOCAL)
ffffffff8171fcf0-ffffffff8171fd95: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-sysfs.c (ffffffff8171c2c0)
Location: drivers/rtc/rtc-sysfs.c:236
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817310d0)
Location: drivers/thermal/thermal_sysfs.c:391
Inline: False
```
```
In drivers/md/md.c (ffffffff817379f0)
Location: drivers/md/md.c:2952
Inline: False
```
**Symbols:**

```
ffffffff8171c2c0-ffffffff8171c331: offset_store (STB_LOCAL)
ffffffff817310d0-ffffffff81731154: offset_store (STB_LOCAL)
ffffffff817379f0-ffffffff81737a8e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-sysfs.c (ffffffff8178d540)
Location: drivers/rtc/rtc-sysfs.c:237
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817a2160)
Location: drivers/thermal/thermal_sysfs.c:391
Inline: False
```
```
In drivers/md/md.c (ffffffff817a9a40)
Location: drivers/md/md.c:3007
Inline: False
```
**Symbols:**

```
ffffffff8178d540-ffffffff8178d5b1: offset_store (STB_LOCAL)
ffffffff817a2160-ffffffff817a21e4: offset_store (STB_LOCAL)
ffffffff817a9a40-ffffffff817a9ade: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-sysfs.c (ffffffff817cfb70)
Location: drivers/rtc/rtc-sysfs.c:237
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817e97c0)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffff817f16f0)
Location: drivers/md/md.c:3023
Inline: False
```
**Symbols:**

```
ffffffff817cfb70-ffffffff817cfbe1: offset_store (STB_LOCAL)
ffffffff817e97c0-ffffffff817e9844: offset_store (STB_LOCAL)
ffffffff817f16f0-ffffffff817f178e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff817f6b30)
Location: drivers/rtc/sysfs.c:233
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81815670)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffff8181d5f0)
Location: drivers/md/md.c:3014
Inline: False
```
**Symbols:**

```
ffffffff817f6b30-ffffffff817f6ba1: offset_store (STB_LOCAL)
ffffffff81815670-ffffffff818156f4: offset_store (STB_LOCAL)
ffffffff8181d5f0-ffffffff8181d68e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff81837820)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81857890)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffff8185f810)
Location: drivers/md/md.c:3081
Inline: False
```
**Symbols:**

```
ffffffff81837820-ffffffff81837891: offset_store (STB_LOCAL)
ffffffff81857890-ffffffff81857913: offset_store (STB_LOCAL)
ffffffff8185f810-ffffffff8185f8ae: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff81869190)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81889340)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffff818913f0)
Location: drivers/md/md.c:3135
Inline: False
```
**Symbols:**

```
ffffffff81869190-ffffffff81869201: offset_store (STB_LOCAL)
ffffffff81889340-ffffffff818893c3: offset_store (STB_LOCAL)
ffffffff818913f0-ffffffff8189148e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff8193ce20)
Location: drivers/rtc/sysfs.c:231
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81957d40)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffff819600f0)
Location: drivers/md/md.c:3260
Inline: False
```
**Symbols:**

```
ffffffff8193ce20-ffffffff8193ce91: offset_store (STB_LOCAL)
ffffffff81957d40-ffffffff81957dc3: offset_store (STB_LOCAL)
ffffffff819600f0-ffffffff8196018e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff81942e30)
Location: drivers/rtc/sysfs.c:231
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195d3a0)
Location: drivers/thermal/thermal_sysfs.c:390
Inline: False
```
```
In drivers/md/md.c (ffffffff819669e0)
Location: drivers/md/md.c:3281
Inline: False
```
**Symbols:**

```
ffffffff81942e30-ffffffff81942ea1: offset_store (STB_LOCAL)
ffffffff8195d3a0-ffffffff8195d423: offset_store (STB_LOCAL)
ffffffff819669e0-ffffffff81966a7e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff81926650)
Location: drivers/rtc/sysfs.c:231
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819405f0)
Location: drivers/thermal/thermal_sysfs.c:347
Inline: False
```
```
In drivers/md/md.c (ffffffff8194ab40)
Location: drivers/md/md.c:3245
Inline: False
```
**Symbols:**

```
ffffffff81926650-ffffffff819266c1: offset_store (STB_LOCAL)
ffffffff819405f0-ffffffff81940673: offset_store (STB_LOCAL)
ffffffff8194ab40-ffffffff8194abde: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff819c9590)
Location: drivers/rtc/sysfs.c:231
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819e4f10)
Location: drivers/thermal/thermal_sysfs.c:347
Inline: False
```
```
In drivers/md/md.c (ffffffff819efbf0)
Location: drivers/md/md.c:3264
Inline: False
```
**Symbols:**

```
ffffffff819c9590-ffffffff819c9601: offset_store (STB_LOCAL)
ffffffff819e4f10-ffffffff819e4f93: offset_store (STB_LOCAL)
ffffffff819efbf0-ffffffff819efc8e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff81b2a8a0)
Location: drivers/rtc/sysfs.c:231
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4a220)
Location: drivers/thermal/thermal_sysfs.c:347
Inline: False
```
```
In drivers/md/md.c (ffffffff81b57240)
Location: drivers/md/md.c:3255
Inline: False
```
**Symbols:**

```
ffffffff81b2a8a0-ffffffff81b2a925: offset_store (STB_LOCAL)
ffffffff81b4a220-ffffffff81b4a2b6: offset_store (STB_LOCAL)
ffffffff81b57240-ffffffff81b572f0: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff81cbe4f0)
Location: drivers/rtc/sysfs.c:232
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce1a90)
Location: drivers/thermal/thermal_sysfs.c:407
Inline: False
```
```
In drivers/md/md.c (ffffffff81cf00d0)
Location: drivers/md/md.c:3213
Inline: False
```
**Symbols:**

```
ffffffff81cbe4f0-ffffffff81cbe575: offset_store (STB_LOCAL)
ffffffff81ce1a90-ffffffff81ce1b26: offset_store (STB_LOCAL)
ffffffff81cf00d0-ffffffff81cf0180: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff81d25e00)
Location: drivers/rtc/sysfs.c:232
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81d49d30)
Location: drivers/thermal/thermal_sysfs.c:367
Inline: False
```
```
In drivers/md/md.c (ffffffff81d58eb0)
Location: drivers/md/md.c:3190
Inline: False
```
**Symbols:**

```
ffffffff81d25e00-ffffffff81d25e85: offset_store (STB_LOCAL)
ffffffff81d49d30-ffffffff81d49dc6: offset_store (STB_LOCAL)
ffffffff81d58eb0-ffffffff81d58f60: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff81ddbb70)
Location: drivers/rtc/sysfs.c:232
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e00b40)
Location: drivers/thermal/thermal_sysfs.c:336
Inline: False
```
```
In drivers/md/md.c (ffffffff81e0fd20)
Location: drivers/md/md.c:3312
Inline: False
```
**Symbols:**

```
ffffffff81ddbb70-ffffffff81ddbbf5: offset_store (STB_LOCAL)
ffffffff81e00b40-ffffffff81e00bd6: offset_store (STB_LOCAL)
ffffffff81e0fd20-ffffffff81e0fdd0: offset_store (STB_LOCAL)
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
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffff800010aab988)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad6bb8)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffff800010ae37f0)
Location: drivers/md/md.c:3135
Inline: False
```
**Symbols:**

```
ffff800010aab988-ffff800010aaba1c: offset_store (STB_LOCAL)
ffff800010ad6bb8-ffff800010ad6c54: offset_store (STB_LOCAL)
ffff800010ae37f0-ffff800010ae389c: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (c0b89f94)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (c0bb7244)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (c0bc4f8c)
Location: drivers/md/md.c:3135
Inline: False
```
**Symbols:**

```
c0b89f94-c0b8a01c: offset_store (STB_LOCAL)
c0bb7244-c0bb72e0: offset_store (STB_LOCAL)
c0bc4f8c-c0bc5050: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (c000000000b8da50)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbd130)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (c000000000bcc110)
Location: drivers/md/md.c:3135
Inline: False
```
**Symbols:**

```
c000000000b8da50-c000000000b8dafc: offset_store (STB_LOCAL)
c000000000bbd130-c000000000bbd200: offset_store (STB_LOCAL)
c000000000bcc110-c000000000bcc1f4: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffe0006b6470)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d1c68)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffe0006da004)
Location: drivers/md/md.c:3135
Inline: False
```
**Symbols:**

```
ffffffe0006da004-ffffffe0006da06e: offset_store (STB_LOCAL)
ffffffe0006b6470-ffffffe0006b64c4: offset_store (STB_LOCAL)
ffffffe0006d1c68-ffffffe0006d1cc0: offset_store (STB_LOCAL)
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
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff8181be40)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8182f1c0)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffff81837270)
Location: drivers/md/md.c:3135
Inline: False
```
**Symbols:**

```
ffffffff8181be40-ffffffff8181beb1: offset_store (STB_LOCAL)
ffffffff8182f1c0-ffffffff8182f243: offset_store (STB_LOCAL)
ffffffff81837270-ffffffff8183730e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff817e3530)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817f6850)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffff817fe8e0)
Location: drivers/md/md.c:3135
Inline: False
```
**Symbols:**

```
ffffffff817e3530-ffffffff817e35a1: offset_store (STB_LOCAL)
ffffffff817f6850-ffffffff817f68d3: offset_store (STB_LOCAL)
ffffffff817fe8e0-ffffffff817fe97e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff8185d320)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8187e7f0)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffff818868a0)
Location: drivers/md/md.c:3135
Inline: False
```
**Symbols:**

```
ffffffff8185d320-ffffffff8185d391: offset_store (STB_LOCAL)
ffffffff8187e7f0-ffffffff8187e873: offset_store (STB_LOCAL)
ffffffff818868a0-ffffffff8188693e: offset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t offset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t n);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/sysfs.c (ffffffff81878590)
Location: drivers/rtc/sysfs.c:228
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8189a270)
Location: drivers/thermal/thermal_sysfs.c:389
Inline: False
```
```
In drivers/md/md.c (ffffffff818a2a00)
Location: drivers/md/md.c:3135
Inline: False
```
**Symbols:**

```
ffffffff81878590-ffffffff81878601: offset_store (STB_LOCAL)
ffffffff8189a270-ffffffff8189a2f3: offset_store (STB_LOCAL)
ffffffff818a2a00-ffffffff818a2a9e: offset_store (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device_attribute *attr</code>
</li>
<li>
<b>Param added. </b>
<code>size_t n</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device_attribute *devattr</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
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
