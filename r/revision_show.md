# Function: <code>revision_show</code>

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
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814a8bf0)
Location: drivers/pci/pci-sysfs.c:54
Inline: False
```
**Symbols:**

```
ffffffff814a8bf0-ffffffff814a8c13: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814b31b0)
Location: drivers/pci/pci-sysfs.c:53
Inline: False
```
**Symbols:**

```
ffffffff814b31b0-ffffffff814b31d6: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814f28c0)
Location: drivers/pci/pci-sysfs.c:54
Inline: False
```
**Symbols:**

```
ffffffff814f28c0-ffffffff814f28e6: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81522bd0)
Location: drivers/pci/pci-sysfs.c:51
Inline: False
```
**Symbols:**

```
ffffffff81522bd0-ffffffff81522bf6: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81538a10)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
ffffffff81538a10-ffffffff81538a36: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81568400)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
ffffffff81568400-ffffffff81568427: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff815896e0)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
ffffffff815896e0-ffffffff81589707: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816305d0)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
ffffffff816305d0-ffffffff816305f7: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81655c50)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b6470)
Location: drivers/mmc/core/sdio_bus.c:45
Inline: False
```
**Symbols:**

```
ffffffff81655c50-ffffffff81655c77: revision_show (STB_LOCAL)
ffffffff819b6470-ffffffff819b649d: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81638910)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199ac20)
Location: drivers/mmc/core/sdio_bus.c:45
Inline: False
```
**Symbols:**

```
ffffffff81638910-ffffffff81638934: revision_show (STB_LOCAL)
ffffffff8199ac20-ffffffff8199ac4d: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816a8c40)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a47560)
Location: drivers/mmc/core/sdio_bus.c:45
Inline: False
```
**Symbols:**

```
ffffffff816a8c40-ffffffff816a8c67: revision_show (STB_LOCAL)
ffffffff81a47560-ffffffff81a4758d: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff817cb940)
Location: drivers/pci/pci-sysfs.c:51
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb5490)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff817cb940-ffffffff817cb970: revision_show (STB_LOCAL)
ffffffff81bb5490-ffffffff81bb54c9: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff818e91a0)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d59c10)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff818e91a0-ffffffff818e91d0: revision_show (STB_LOCAL)
ffffffff81d59c10-ffffffff81d59c49: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8192c7b0)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc45b0)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff8192c7b0-ffffffff8192c7e0: revision_show (STB_LOCAL)
ffffffff81dc45b0-ffffffff81dc45e9: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81975040)
Location: drivers/pci/pci-sysfs.c:52
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7ce90)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff81975040-ffffffff8197506d: revision_show (STB_LOCAL)
ffffffff81e7ce90-ffffffff81e7cec9: revision_show (STB_LOCAL)
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
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffff8000106edf08)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
ffff8000106edf08-ffff8000106edf48: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c0888ffc)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
c0888ffc-c0889030: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c00000000086a5a0)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
c00000000086a5a0-c00000000086a5ec: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffe0004c2a10)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
ffffffe0004c2a10-ffffffe0004c2a4e: revision_show (STB_LOCAL)
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
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157d570)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
ffffffff8157d570-ffffffff8157d597: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8156c340)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
```
In drivers/acpi/nfit/core.c (ffffffff815f46b0)
Location: drivers/acpi/nfit/core.c:1246
Inline: False
```
**Symbols:**

```
ffffffff8156c340-ffffffff8156c367: revision_show (STB_LOCAL)
ffffffff815f46b0-ffffffff815f46e4: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157d430)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
ffffffff8157d430-ffffffff8157d457: revision_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t revision_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff815978e0)
Location: drivers/pci/pci-sysfs.c:50
Inline: False
```
**Symbols:**

```
ffffffff815978e0-ffffffff81597907: revision_show (STB_LOCAL)
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
