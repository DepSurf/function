# Function: <code>power_state_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8147c061)
Location: drivers/acpi/device_sysfs.c:357
Inline: False
```
**Symbols:**

```
ffffffff8147c061-ffffffff8147c090: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814ca72f)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff814ca72f-ffffffff814ca75e: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814ec64b)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff814ec64b-ffffffff814ec67a: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff814f8d70)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff814f8d70-ffffffff814f8d9f: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff8153a4a0)
Location: drivers/acpi/device_sysfs.c:362
Inline: False
```
**Symbols:**

```
ffffffff8153a4a0-ffffffff8153a4cf: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81570330)
Location: drivers/acpi/device_sysfs.c:362
Inline: False
```
**Symbols:**

```
ffffffff81570330-ffffffff8157035f: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff81587e30)
Location: drivers/acpi/device_sysfs.c:366
Inline: False
```
**Symbols:**

```
ffffffff81587e30-ffffffff81587e5f: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815b8aa0)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff815b8aa0-ffffffff815b8ad1: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815d9ce0)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff815d9ce0-ffffffff815d9d11: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff816840d0)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff816840d0-ffffffff81684103: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81655e00)
Location: drivers/pci/pci-sysfs.c:127
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff816a1e90)
Location: drivers/acpi/device_sysfs.c:350
Inline: False
```
**Symbols:**

```
ffffffff81655e00-ffffffff81655e30: power_state_show (STB_LOCAL)
ffffffff816a1e90-ffffffff816a1ec3: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81638a00)
Location: drivers/pci/pci-sysfs.c:127
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff81684c80)
Location: drivers/acpi/device_sysfs.c:351
Inline: False
```
**Symbols:**

```
ffffffff81638a00-ffffffff81638a30: power_state_show (STB_LOCAL)
ffffffff81684c80-ffffffff81684cb3: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816a8d30)
Location: drivers/pci/pci-sysfs.c:127
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff816f9f40)
Location: drivers/acpi/device_sysfs.c:356
Inline: False
```
**Symbols:**

```
ffffffff816a8d30-ffffffff816a8d60: power_state_show (STB_LOCAL)
ffffffff816f9f40-ffffffff816f9f73: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff817cba30)
Location: drivers/pci/pci-sysfs.c:148
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff818272c0)
Location: drivers/acpi/device_sysfs.c:357
Inline: False
```
**Symbols:**

```
ffffffff817cba30-ffffffff817cba69: power_state_show (STB_LOCAL)
ffffffff818272c0-ffffffff818272fc: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff818e92e0)
Location: drivers/pci/pci-sysfs.c:149
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff819591d0)
Location: drivers/acpi/device_sysfs.c:357
Inline: False
```
**Symbols:**

```
ffffffff818e92e0-ffffffff818e9319: power_state_show (STB_LOCAL)
ffffffff819591d0-ffffffff8195920c: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8192c8f0)
Location: drivers/pci/pci-sysfs.c:149
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff8199f630)
Location: drivers/acpi/device_sysfs.c:357
Inline: False
```
**Symbols:**

```
ffffffff8192c8f0-ffffffff8192c929: power_state_show (STB_LOCAL)
ffffffff8199f630-ffffffff8199f66c: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81975180)
Location: drivers/pci/pci-sysfs.c:149
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff819e7cb0)
Location: drivers/acpi/device_sysfs.c:355
Inline: False
```
**Symbols:**

```
ffffffff81975180-ffffffff819751b9: power_state_show (STB_LOCAL)
ffffffff819e7cb0-ffffffff819e7cec: power_state_show (STB_LOCAL)
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
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffff800010765fd8)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffff800010765fd8-ffff800010766024: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815cc4b0)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff815cc4b0-ffffffff815cc4e1: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815b6030)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff815b6030-ffffffff815b6061: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815cdfc0)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff815cdfc0-ffffffff815cdff1: power_state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t power_state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_sysfs.c (ffffffff815e7e80)
Location: drivers/acpi/device_sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff815e7e80-ffffffff815e7eb1: power_state_show (STB_LOCAL)
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
