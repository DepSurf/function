# Function: <code>irq_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8143b560)
Location: drivers/pci/pci-sysfs.c:55
Inline: False
```
**Symbols:**

```
ffffffff8143b560-ffffffff8143b585: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814873e0)
Location: drivers/pci/pci-sysfs.c:55
Inline: False
```
**Symbols:**

```
ffffffff814873e0-ffffffff81487405: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814a8b90)
Location: drivers/pci/pci-sysfs.c:56
Inline: False
```
**Symbols:**

```
ffffffff814a8b90-ffffffff814a8bb5: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814b3150)
Location: drivers/pci/pci-sysfs.c:55
Inline: False
```
**Symbols:**

```
ffffffff814b3150-ffffffff814b3175: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814f2860)
Location: drivers/pci/pci-sysfs.c:56
Inline: False
```
**Symbols:**

```
ffffffff814f2860-ffffffff814f2885: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81522b70)
Location: drivers/pci/pci-sysfs.c:53
Inline: False
```
**Symbols:**

```
ffffffff81522b70-ffffffff81522b95: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff815389b0)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
ffffffff815389b0-ffffffff815389d5: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff815683a0)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
ffffffff815683a0-ffffffff815683c6: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81589680)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
ffffffff81589680-ffffffff815896a6: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81630570)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757620)
Location: drivers/tty/serial/serial_core.c:2663
Inline: False
```
**Symbols:**

```
ffffffff81630570-ffffffff81630596: irq_show (STB_LOCAL)
ffffffff81757620-ffffffff81757681: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81655bf0)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff81772720)
Location: drivers/tty/serial/serial_core.c:2670
Inline: False
```
**Symbols:**

```
ffffffff81655bf0-ffffffff81655c16: irq_show (STB_LOCAL)
ffffffff81772720-ffffffff8177277c: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816388b0)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff817561b0)
Location: drivers/tty/serial/serial_core.c:2667
Inline: False
```
**Symbols:**

```
ffffffff816388b0-ffffffff816388d6: irq_show (STB_LOCAL)
ffffffff817561b0-ffffffff8175620c: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816a8be0)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff817d98e0)
Location: drivers/tty/serial/serial_core.c:2682
Inline: False
```
**Symbols:**

```
ffffffff816a8be0-ffffffff816a8c06: irq_show (STB_LOCAL)
ffffffff817d98e0-ffffffff817d993c: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff817cc1f0)
Location: drivers/pci/pci-sysfs.c:54
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81918270)
Location: drivers/tty/serial/serial_core.c:2729
Inline: False
```
**Symbols:**

```
ffffffff817cc1f0-ffffffff817cc25e: irq_show (STB_LOCAL)
ffffffff81918270-ffffffff819182e8: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff818ea3d0)
Location: drivers/pci/pci-sysfs.c:55
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a73c40)
Location: drivers/tty/serial/serial_core.c:2863
Inline: False
```
**Symbols:**

```
ffffffff818ea3d0-ffffffff818ea43e: irq_show (STB_LOCAL)
ffffffff81a73c40-ffffffff81a73cb8: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8192d9e0)
Location: drivers/pci/pci-sysfs.c:55
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abe2d0)
Location: drivers/tty/serial/serial_core.c:2895
Inline: False
```
**Symbols:**

```
ffffffff8192d9e0-ffffffff8192da4e: irq_show (STB_LOCAL)
ffffffff81abe2d0-ffffffff81abe348: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81976360)
Location: drivers/pci/pci-sysfs.c:55
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b110b0)
Location: drivers/tty/serial/serial_core.c:2931
Inline: False
```
**Symbols:**

```
ffffffff81976360-ffffffff819763ce: irq_show (STB_LOCAL)
ffffffff81b110b0-ffffffff81b11115: irq_show (STB_LOCAL)
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
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffff8000106ede88)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
ffff8000106ede88-ffff8000106edec8: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c0888f9c)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
c0888f9c-c0888fcc: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c00000000086a500)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
c00000000086a500-c00000000086a548: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffe0004c2998)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
ffffffe0004c2998-ffffffe0004c29d4: irq_show (STB_LOCAL)
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
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157d510)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
ffffffff8157d510-ffffffff8157d536: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8156c2e0)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
ffffffff8156c2e0-ffffffff8156c306: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157d3d0)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
ffffffff8157d3d0-ffffffff8157d3f6: irq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t irq_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81597880)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
**Symbols:**

```
ffffffff81597880-ffffffff815978a6: irq_show (STB_LOCAL)
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
