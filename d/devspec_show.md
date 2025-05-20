# Function: <code>devspec_show</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t devspec_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffff8000106edc30)
Location: drivers/pci/pci-sysfs.c:538
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffff800010a29780)
Location: drivers/usb/core/sysfs.c:112
Inline: False
```
**Symbols:**

```
ffff8000106edc30-ffff8000106edc90: devspec_show (STB_LOCAL)
ffff800010a29780-ffff800010a297c0: devspec_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t devspec_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c0888e2c)
Location: drivers/pci/pci-sysfs.c:538
Inline: False
```
```
In drivers/usb/core/sysfs.c (c0aff694)
Location: drivers/usb/core/sysfs.c:112
Inline: False
```
**Symbols:**

```
c0888e2c-c0888e7c: devspec_show (STB_LOCAL)
c0aff694-c0aff6c4: devspec_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t devspec_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/pseries/vio.c (c0000000000ffe00)
Location: arch/powerpc/platforms/pseries/vio.c:1533
Inline: False
```
```
In drivers/pci/pci-sysfs.c (c00000000086a200)
Location: drivers/pci/pci-sysfs.c:538
Inline: False
```
```
In drivers/usb/core/sysfs.c (c000000000ae5cf0)
Location: drivers/usb/core/sysfs.c:112
Inline: False
```
**Symbols:**

```
c0000000000ffe00-c0000000000ffe48: devspec_show (STB_LOCAL)
c00000000086a200-c00000000086a268: devspec_show (STB_LOCAL)
c000000000ae5cf0-c000000000ae5d38: devspec_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t devspec_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffe0004c2700)
Location: drivers/pci/pci-sysfs.c:538
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffe00064b176)
Location: drivers/usb/core/sysfs.c:112
Inline: False
```
**Symbols:**

```
ffffffe0004c2700-ffffffe0004c2754: devspec_show (STB_LOCAL)
ffffffe00064b176-ffffffe00064b1b2: devspec_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
