# Function: <code>quirks_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81617c30)
Location: drivers/usb/core/sysfs.c:206
Inline: False
```
**Symbols:**

```
ffffffff81617c30-ffffffff81617c55: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81677d00)
Location: drivers/usb/core/sysfs.c:216
Inline: False
```
**Symbols:**

```
ffffffff81677d00-ffffffff81677d25: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff816a59e0)
Location: drivers/usb/core/sysfs.c:230
Inline: False
```
**Symbols:**

```
ffffffff816a59e0-ffffffff816a5a05: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff816bad80)
Location: drivers/usb/core/sysfs.c:230
Inline: False
```
**Symbols:**

```
ffffffff816bad80-ffffffff816bada5: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81726740)
Location: drivers/usb/core/sysfs.c:230
Inline: False
```
**Symbols:**

```
ffffffff81726740-ffffffff81726765: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81765540)
Location: drivers/usb/core/sysfs.c:250
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff8176d510)
Location: drivers/usb/core/port.c:53
Inline: False
```
**Symbols:**

```
ffffffff81765540-ffffffff81765565: quirks_show (STB_LOCAL)
ffffffff8176d510-ffffffff8176d538: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81789a70)
Location: drivers/usb/core/sysfs.c:250
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff81791b60)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff81789a70-ffffffff81789a95: quirks_show (STB_LOCAL)
ffffffff81791b60-ffffffff81791b88: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff817c7e90)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff817d0330)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff817c7e90-ffffffff817c7eb6: quirks_show (STB_LOCAL)
ffffffff817d0330-ffffffff817d0359: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff817f89d0)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff81801200)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff817f89d0-ffffffff817f89f6: quirks_show (STB_LOCAL)
ffffffff81801200-ffffffff81801229: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff818c8b50)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff818d1950)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff818c8b50-ffffffff818c8b76: quirks_show (STB_LOCAL)
ffffffff818d1950-ffffffff818d1979: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff818d3ca0)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff818dbd30)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff818d3ca0-ffffffff818d3cc6: quirks_show (STB_LOCAL)
ffffffff818dbd30-ffffffff818dbd59: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff818b7200)
Location: drivers/usb/core/sysfs.c:254
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff818bf0f0)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff818b7200-ffffffff818b7226: quirks_show (STB_LOCAL)
ffffffff818bf0f0-ffffffff818bf119: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff8194cc90)
Location: drivers/usb/core/sysfs.c:254
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff81955750)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff8194cc90-ffffffff8194ccb6: quirks_show (STB_LOCAL)
ffffffff81955750-ffffffff81955779: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81aa58f0)
Location: drivers/usb/core/sysfs.c:254
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff81aaf3a0)
Location: drivers/usb/core/port.c:63
Inline: False
```
**Symbols:**

```
ffffffff81aa58f0-ffffffff81aa591f: quirks_show (STB_LOCAL)
ffffffff81aaf3a0-ffffffff81aaf3d2: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81c2c3f0)
Location: drivers/usb/core/sysfs.c:255
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff81c370c0)
Location: drivers/usb/core/port.c:172
Inline: False
```
**Symbols:**

```
ffffffff81c2c3f0-ffffffff81c2c41f: quirks_show (STB_LOCAL)
ffffffff81c370c0-ffffffff81c370f2: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81c93570)
Location: drivers/usb/core/sysfs.c:255
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff81c9e3b0)
Location: drivers/usb/core/port.c:182
Inline: False
```
**Symbols:**

```
ffffffff81c93570-ffffffff81c9359f: quirks_show (STB_LOCAL)
ffffffff81c9e3b0-ffffffff81c9e3e2: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81d48020)
Location: drivers/usb/core/sysfs.c:252
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff81d52fb0)
Location: drivers/usb/core/port.c:182
Inline: False
```
**Symbols:**

```
ffffffff81d48020-ffffffff81d4804f: quirks_show (STB_LOCAL)
ffffffff81d52fb0-ffffffff81d52fe2: quirks_show (STB_LOCAL)
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
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffff800010a29890)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffff800010a354c8)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffff800010a29890-ffff800010a298d0: quirks_show (STB_LOCAL)
ffff800010a354c8-ffff800010a35508: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (c0aff754)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (c0b08ccc)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
c0aff754-c0aff784: quirks_show (STB_LOCAL)
c0b08ccc-c0b08d00: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (c000000000ae5e30)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (c000000000af3490)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
c000000000ae5e30-c000000000ae5e78: quirks_show (STB_LOCAL)
c000000000af3490-c000000000af34dc: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffe00064b256)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffffffe000652daa)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffe00064b256-ffffffe00064b292: quirks_show (STB_LOCAL)
ffffffe000652daa-ffffffe000652de8: quirks_show (STB_LOCAL)
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
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff817b0db0)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff817b95e0)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff817b0db0-ffffffff817b0dd6: quirks_show (STB_LOCAL)
ffffffff817b95e0-ffffffff817b9609: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff817a27e0)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff817ab010)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff817a27e0-ffffffff817a2806: quirks_show (STB_LOCAL)
ffffffff817ab010-ffffffff817ab039: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff817ed850)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff817f6080)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff817ed850-ffffffff817ed876: quirks_show (STB_LOCAL)
ffffffff817f6080-ffffffff817f60a9: quirks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t quirks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/sysfs.c (ffffffff81807a90)
Location: drivers/usb/core/sysfs.c:251
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff818102c0)
Location: drivers/usb/core/port.c:62
Inline: False
```
**Symbols:**

```
ffffffff81807a90-ffffffff81807ab6: quirks_show (STB_LOCAL)
ffffffff818102c0-ffffffff818102e9: quirks_show (STB_LOCAL)
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
