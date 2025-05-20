# Function: <code>level_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81552160)
Location: drivers/base/cacheinfo.c:236
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81619040)
Location: drivers/usb/core/sysfs.c:407
Inline: False
```
```
In drivers/md/md.c (ffffffff8168ca10)
Location: drivers/md/md.c:3405
Inline: False
```
**Symbols:**

```
ffffffff81552160-ffffffff81552189: level_show (STB_LOCAL)
ffffffff81619040-ffffffff816190a9: level_show (STB_LOCAL)
ffffffff8168ca10-ffffffff8168cab3: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815a4100)
Location: drivers/base/cacheinfo.c:236
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff816791f0)
Location: drivers/usb/core/sysfs.c:421
Inline: False
```
```
In drivers/md/md.c (ffffffff816ee0d0)
Location: drivers/md/md.c:3411
Inline: False
```
**Symbols:**

```
ffffffff815a4100-ffffffff815a4129: level_show (STB_LOCAL)
ffffffff816791f0-ffffffff81679259: level_show (STB_LOCAL)
ffffffff816ee0d0-ffffffff816ee173: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815d2790)
Location: drivers/base/cacheinfo.c:367
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff816a6ed0)
Location: drivers/usb/core/sysfs.c:435
Inline: False
```
```
In drivers/md/md.c (ffffffff8171f570)
Location: drivers/md/md.c:3446
Inline: False
```
**Symbols:**

```
ffffffff815d2790-ffffffff815d27b9: level_show (STB_LOCAL)
ffffffff816a6ed0-ffffffff816a6f39: level_show (STB_LOCAL)
ffffffff8171f570-ffffffff8171f613: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff815e7320)
Location: drivers/base/cacheinfo.c:367
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff816bc240)
Location: drivers/usb/core/sysfs.c:435
Inline: False
```
```
In drivers/md/md.c (ffffffff81737450)
Location: drivers/md/md.c:3582
Inline: False
```
**Symbols:**

```
ffffffff815e7320-ffffffff815e7349: level_show (STB_LOCAL)
ffffffff816bc240-ffffffff816bc2a9: level_show (STB_LOCAL)
ffffffff81737450-ffffffff817374f3: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff8164e6f0)
Location: drivers/base/cacheinfo.c:380
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81727c00)
Location: drivers/usb/core/sysfs.c:435
Inline: False
```
```
In drivers/md/md.c (ffffffff817a9490)
Location: drivers/md/md.c:3637
Inline: False
```
**Symbols:**

```
ffffffff8164e6f0-ffffffff8164e719: level_show (STB_LOCAL)
ffffffff81727c00-ffffffff81727c69: level_show (STB_LOCAL)
ffffffff817a9490-ffffffff817a9533: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81689f70)
Location: drivers/base/cacheinfo.c:370
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:455
Inline: False
```
```
In drivers/md/md.c (ffffffff817f6620)
Location: drivers/md/md.c:3653
Inline: False
```
**Symbols:**

```
ffffffff81689f70-ffffffff81689f99: level_show (STB_LOCAL)
ffffffff81766a40-ffffffff81766a98: level_show (STB_LOCAL)
ffffffff81766ca6-ffffffff81766cc1: level_show.cold.8 (STB_LOCAL)
ffffffff817f6620-ffffffff817f66c3: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816a9470)
Location: drivers/base/cacheinfo.c:364
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:455
Inline: False
```
```
In drivers/md/md.c (ffffffff818227a0)
Location: drivers/md/md.c:3644
Inline: False
```
**Symbols:**

```
ffffffff816a9470-ffffffff816a9499: level_show (STB_LOCAL)
ffffffff8178afc0-ffffffff8178b018: level_show (STB_LOCAL)
ffffffff8178b226-ffffffff8178b241: level_show.cold.8 (STB_LOCAL)
ffffffff818227a0-ffffffff81822843: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816e2a50)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffffffff81864c90)
Location: drivers/md/md.c:3711
Inline: False
```
**Symbols:**

```
ffffffff816e2a50-ffffffff816e2a76: level_show (STB_LOCAL)
ffffffff817c9560-ffffffff817c95b8: level_show (STB_LOCAL)
ffffffff817c9826-ffffffff817c9841: level_show.cold (STB_LOCAL)
ffffffff81864c90-ffffffff81864d2e: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81706c00)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffffffff818969d0)
Location: drivers/md/md.c:3769
Inline: False
```
**Symbols:**

```
ffffffff81706c00-ffffffff81706c26: level_show (STB_LOCAL)
ffffffff817fa0a0-ffffffff817fa0f8: level_show (STB_LOCAL)
ffffffff817fa366-ffffffff817fa381: level_show.cold (STB_LOCAL)
ffffffff818969d0-ffffffff81896a6e: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817c18f0)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffffffff81963c10)
Location: drivers/md/md.c:3894
Inline: False
```
**Symbols:**

```
ffffffff817c18f0-ffffffff817c1916: level_show (STB_LOCAL)
ffffffff818ca290-ffffffff818ca2e8: level_show (STB_LOCAL)
ffffffff818ca589-ffffffff818ca5a4: level_show.cold (STB_LOCAL)
ffffffff81963c10-ffffffff81963cae: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817d6b90)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffffffff8196a500)
Location: drivers/md/md.c:3915
Inline: False
```
**Symbols:**

```
ffffffff817d6b90-ffffffff817d6bb6: level_show (STB_LOCAL)
ffffffff818d53e0-ffffffff818d5438: level_show (STB_LOCAL)
ffffffff81c1dfa4-ffffffff81c1dfbf: level_show.cold (STB_LOCAL)
ffffffff8196a500-ffffffff8196a59e: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff817ba650)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:459
Inline: False
```
```
In drivers/md/md.c (ffffffff8194f280)
Location: drivers/md/md.c:3879
Inline: False
```
**Symbols:**

```
ffffffff817ba650-ffffffff817ba676: level_show (STB_LOCAL)
ffffffff818b89a0-ffffffff818b89f8: level_show (STB_LOCAL)
ffffffff81c0fe89-ffffffff81c0fea4: level_show.cold (STB_LOCAL)
ffffffff8194f280-ffffffff8194f31e: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff818443e0)
Location: drivers/base/cacheinfo.c:370
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:436
Inline: False
```
```
In drivers/md/md.c (ffffffff819f4700)
Location: drivers/md/md.c:3898
Inline: False
```
**Symbols:**

```
ffffffff818443e0-ffffffff81844406: level_show (STB_LOCAL)
ffffffff8194e470-ffffffff8194e4c8: level_show (STB_LOCAL)
ffffffff81d16f4f-ffffffff81d16f6a: level_show.cold (STB_LOCAL)
ffffffff819f4700-ffffffff819f479e: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81988720)
Location: drivers/base/cacheinfo.c:370
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:436
Inline: False
```
```
In drivers/md/md.c (ffffffff81b56620)
Location: drivers/md/md.c:3888
Inline: False
```
**Symbols:**

```
ffffffff81988720-ffffffff81988750: level_show (STB_LOCAL)
ffffffff81aa7410-ffffffff81aa7472: level_show (STB_LOCAL)
ffffffff81ee1e7e-ffffffff81ee1e99: level_show.cold (STB_LOCAL)
ffffffff81b56620-ffffffff81b566c5: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81af6ff0)
Location: drivers/base/cacheinfo.c:422
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81c2e270)
Location: drivers/usb/core/sysfs.c:437
Inline: False
```
```
In drivers/md/md.c (ffffffff81cefad0)
Location: drivers/md/md.c:3850
Inline: False
```
**Symbols:**

```
ffffffff81af6ff0-ffffffff81af7020: level_show (STB_LOCAL)
ffffffff81c2e270-ffffffff81c2e2e6: level_show (STB_LOCAL)
ffffffff81cefad0-ffffffff81cefb75: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b452a0)
Location: drivers/base/cacheinfo.c:624
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81c95460)
Location: drivers/usb/core/sysfs.c:437
Inline: False
```
```
In drivers/md/md.c (ffffffff81d588a0)
Location: drivers/md/md.c:3836
Inline: False
```
**Symbols:**

```
ffffffff81b452a0-ffffffff81b452d0: level_show (STB_LOCAL)
ffffffff81c95460-ffffffff81c954d6: level_show (STB_LOCAL)
ffffffff81d588a0-ffffffff81d58945: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b9d320)
Location: drivers/base/cacheinfo.c:631
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81d49f20)
Location: drivers/usb/core/sysfs.c:434
Inline: False
```
```
In drivers/md/md.c (ffffffff81e0f710)
Location: drivers/md/md.c:3964
Inline: False
```
**Symbols:**

```
ffffffff81b9d320-ffffffff81b9d350: level_show (STB_LOCAL)
ffffffff81d49f20-ffffffff81d49f96: level_show (STB_LOCAL)
ffffffff81e0f710-ffffffff81e0f7b5: level_show (STB_LOCAL)
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
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffff8000108f4040)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffff800010a2b460)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffff800010aeab48)
Location: drivers/md/md.c:3769
Inline: False
```
**Symbols:**

```
ffff8000108f4040-ffff8000108f4084: level_show (STB_LOCAL)
ffff800010a2b460-ffff800010a2b518: level_show (STB_LOCAL)
ffff800010aeab48-ffff800010aeac6c: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (c09e053c)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (c0b00f88)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (c0bc451c)
Location: drivers/md/md.c:3769
Inline: False
```
**Symbols:**

```
c09e053c-c09e056c: level_show (STB_LOCAL)
c0b00f88-c0b01010: level_show (STB_LOCAL)
c0bc451c-c0bc45cc: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct kobject *k, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/cacheinfo.c (c00000000002a1b0)
Location: arch/powerpc/kernel/cacheinfo.c:613
Inline: False
```
```
In drivers/base/cacheinfo.c (c00000000098df40)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (c000000000ae83a0)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (c000000000bcaf60)
Location: drivers/md/md.c:3769
Inline: False
```
**Symbols:**

```
c00000000002a1b0-c00000000002a1f8: level_show (STB_LOCAL)
c00000000098df40-c00000000098df88: level_show (STB_LOCAL)
c000000000ae83a0-c000000000ae8450: level_show (STB_LOCAL)
c000000000bcaf60-c000000000bcb0ac: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffe000585618)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffe00064c9fa)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffffffe0006ded7e)
Location: drivers/md/md.c:3769
Inline: False
```
**Symbols:**

```
ffffffe000585618-ffffffe000585656: level_show (STB_LOCAL)
ffffffe0006ded7e-ffffffe0006dee4c: level_show (STB_LOCAL)
ffffffe00064c9fa-ffffffe00064ca78: level_show (STB_LOCAL)
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
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816cc350)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffffffff8183c850)
Location: drivers/md/md.c:3769
Inline: False
```
**Symbols:**

```
ffffffff816cc350-ffffffff816cc376: level_show (STB_LOCAL)
ffffffff817b2480-ffffffff817b24d8: level_show (STB_LOCAL)
ffffffff817b2746-ffffffff817b2761: level_show.cold (STB_LOCAL)
ffffffff8183c850-ffffffff8183c8ee: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816a7680)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffffffff81803eb0)
Location: drivers/md/md.c:3769
Inline: False
```
**Symbols:**

```
ffffffff816a7680-ffffffff816a76a6: level_show (STB_LOCAL)
ffffffff817a3eb0-ffffffff817a3f08: level_show (STB_LOCAL)
ffffffff817a4176-ffffffff817a4191: level_show.cold (STB_LOCAL)
ffffffff81803eb0-ffffffff81803f4e: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff816fa8c0)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffffffff8188be80)
Location: drivers/md/md.c:3769
Inline: False
```
**Symbols:**

```
ffffffff816fa8c0-ffffffff816fa8e6: level_show (STB_LOCAL)
ffffffff817eef20-ffffffff817eef78: level_show (STB_LOCAL)
ffffffff817ef1e6-ffffffff817ef201: level_show.cold (STB_LOCAL)
ffffffff8188be80-ffffffff8188bf1e: level_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t level_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81715160)
Location: drivers/base/cacheinfo.c:369
Inline: False
```
```
In drivers/usb/core/sysfs.c (0)
Location: drivers/usb/core/sysfs.c:456
Inline: False
```
```
In drivers/md/md.c (ffffffff818a1ea0)
Location: drivers/md/md.c:3769
Inline: False
```
**Symbols:**

```
ffffffff81715160-ffffffff81715186: level_show (STB_LOCAL)
ffffffff81809160-ffffffff818091b8: level_show (STB_LOCAL)
ffffffff81809426-ffffffff81809441: level_show.cold (STB_LOCAL)
ffffffff818a1ea0-ffffffff818a1f40: level_show (STB_LOCAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject *k</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute *attr</code> ➡️ <code>struct kobj_attribute *attr</code>
</li>
</ul>
</details>
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
