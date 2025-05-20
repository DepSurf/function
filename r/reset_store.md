# Function: <code>reset_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8143c1f0)
Location: drivers/pci/pci-sysfs.c:1308
Inline: False
```
**Symbols:**

```
ffffffff8143c1f0-ffffffff8143c26b: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81488010)
Location: drivers/pci/pci-sysfs.c:1309
Inline: False
```
**Symbols:**

```
ffffffff81488010-ffffffff8148808a: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814a97f0)
Location: drivers/pci/pci-sysfs.c:1311
Inline: False
```
**Symbols:**

```
ffffffff814a97f0-ffffffff814a986a: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814b3390)
Location: drivers/pci/pci-sysfs.c:1463
Inline: False
```
**Symbols:**

```
ffffffff814b3390-ffffffff814b340a: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814f2b30)
Location: drivers/pci/pci-sysfs.c:1498
Inline: False
```
**Symbols:**

```
ffffffff814f2b30-ffffffff814f2baa: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81522e30)
Location: drivers/pci/pci-sysfs.c:1448
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817ea330)
Location: drivers/thermal/thermal_sysfs.c:820
Inline: False
```
**Symbols:**

```
ffffffff81522e30-ffffffff81522eac: reset_store (STB_LOCAL)
ffffffff817ea330-ffffffff817ea3b1: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81538c70)
Location: drivers/pci/pci-sysfs.c:1447
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff818160e0)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffffffff81538c70-ffffffff81538d10: reset_store (STB_LOCAL)
ffffffff818160e0-ffffffff81816161: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81568650)
Location: drivers/pci/pci-sysfs.c:1448
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81858310)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffffffff81568650-ffffffff815686ef: reset_store (STB_LOCAL)
ffffffff81858310-ffffffff81858398: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81589890)
Location: drivers/pci/pci-sysfs.c:1304
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81889dc0)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffffffff81589890-ffffffff8158992f: reset_store (STB_LOCAL)
ffffffff81889dc0-ffffffff81889e48: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81630790)
Location: drivers/pci/pci-sysfs.c:1289
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81958940)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffffffff81630790-ffffffff8163082f: reset_store (STB_LOCAL)
ffffffff81958940-ffffffff819589c8: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81655e30)
Location: drivers/pci/pci-sysfs.c:1300
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195dfe0)
Location: drivers/thermal/thermal_sysfs.c:810
Inline: False
```
**Symbols:**

```
ffffffff81655e30-ffffffff81655ecf: reset_store (STB_LOCAL)
ffffffff8195dfe0-ffffffff8195e068: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81638080)
Location: drivers/pci/pci-sysfs.c:1337
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81941440)
Location: drivers/thermal/thermal_sysfs.c:730
Inline: False
```
**Symbols:**

```
ffffffff81638080-ffffffff8163811f: reset_store (STB_LOCAL)
ffffffff81941440-ffffffff819414c8: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816a8380)
Location: drivers/pci/pci-sysfs.c:1337
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819e5e20)
Location: drivers/thermal/thermal_sysfs.c:730
Inline: False
```
**Symbols:**

```
ffffffff816a8380-ffffffff816a841f: reset_store (STB_LOCAL)
ffffffff819e5e20-ffffffff819e5ea8: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff817caf50)
Location: drivers/pci/pci-sysfs.c:1332
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4aea0)
Location: drivers/thermal/thermal_sysfs.c:730
Inline: False
```
**Symbols:**

```
ffffffff817caf50-ffffffff817cb003: reset_store (STB_LOCAL)
ffffffff81b4aea0-ffffffff81b4af2b: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff818e9380)
Location: drivers/pci/pci-sysfs.c:1345
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce29a0)
Location: drivers/thermal/thermal_sysfs.c:788
Inline: False
```
**Symbols:**

```
ffffffff818e9380-ffffffff818e9433: reset_store (STB_LOCAL)
ffffffff81ce29a0-ffffffff81ce2a3a: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8192c990)
Location: drivers/pci/pci-sysfs.c:1345
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81d4ab20)
Location: drivers/thermal/thermal_sysfs.c:762
Inline: False
```
**Symbols:**

```
ffffffff8192c990-ffffffff8192ca43: reset_store (STB_LOCAL)
ffffffff81d4ab20-ffffffff81d4abdd: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81975220)
Location: drivers/pci/pci-sysfs.c:1369
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e01840)
Location: drivers/thermal/thermal_sysfs.c:731
Inline: False
```
**Symbols:**

```
ffffffff81975220-ffffffff819752d3: reset_store (STB_LOCAL)
ffffffff81e01840-ffffffff81e018fd: reset_store (STB_LOCAL)
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
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffff8000106ee1e0)
Location: drivers/pci/pci-sysfs.c:1304
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad7758)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffff8000106ee1e0-ffff8000106ee298: reset_store (STB_LOCAL)
ffff800010ad7758-ffff800010ad7830: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c088928c)
Location: drivers/pci/pci-sysfs.c:1304
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (c0bb7d40)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
c088928c-c0889340: reset_store (STB_LOCAL)
c0bb7d40-c0bb7de0: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c00000000086a850)
Location: drivers/pci/pci-sysfs.c:1304
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbe310)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
c00000000086a850-c00000000086a940: reset_store (STB_LOCAL)
c000000000bbe310-c000000000bbe454: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffe0004c2632)
Location: drivers/pci/pci-sysfs.c:1304
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d23dc)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffffffe0004c2632-ffffffe0004c26b0: reset_store (STB_LOCAL)
ffffffe0006d23dc-ffffffe0006d249a: reset_store (STB_LOCAL)
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
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157d720)
Location: drivers/pci/pci-sysfs.c:1304
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8182fc40)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffffffff8157d720-ffffffff8157d7bf: reset_store (STB_LOCAL)
ffffffff8182fc40-ffffffff8182fcc8: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8156c4f0)
Location: drivers/pci/pci-sysfs.c:1304
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817f72d0)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffffffff8156c4f0-ffffffff8156c58f: reset_store (STB_LOCAL)
ffffffff817f72d0-ffffffff817f7358: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157d5e0)
Location: drivers/pci/pci-sysfs.c:1304
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8187f270)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffffffff8157d5e0-ffffffff8157d67f: reset_store (STB_LOCAL)
ffffffff8187f270-ffffffff8187f2f8: reset_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t reset_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81597a90)
Location: drivers/pci/pci-sysfs.c:1304
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8189ada0)
Location: drivers/thermal/thermal_sysfs.c:823
Inline: False
```
**Symbols:**

```
ffffffff81597a90-ffffffff81597b2f: reset_store (STB_LOCAL)
ffffffff8189ada0-ffffffff8189ae26: reset_store (STB_LOCAL)
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
