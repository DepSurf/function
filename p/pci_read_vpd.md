# Function: <code>pci_read_vpd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142def0)
Location: drivers/pci/access.c:185
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_read
Direct callers:
  - drivers/pci/pci-sysfs.c:read_vpd_attr
```
**Symbols:**

```
ffffffff8142def0-ffffffff8142df1a: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81479672)
Location: drivers/pci/access.c:255
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/access.c:pci_vpd_size
  - drivers/pci/access.c:pci_vpd_size
Direct callers:
  - drivers/pci/pci-sysfs.c:read_vpd_attr
  - drivers/pci/pci-sysfs.c:read_vpd_attr
```
**Symbols:**

```
ffffffff81479280-ffffffff814792a9: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149ab02)
Location: drivers/pci/access.c:267
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/access.c:pci_vpd_size
  - drivers/pci/access.c:pci_vpd_size
Direct callers:
  - drivers/pci/pci-sysfs.c:read_vpd_attr
  - drivers/pci/pci-sysfs.c:read_vpd_attr
```
**Symbols:**

```
ffffffff8149a610-ffffffff8149a639: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4782)
Location: drivers/pci/access.c:275
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/access.c:pci_vpd_size
  - drivers/pci/access.c:pci_vpd_size
Direct callers:
  - drivers/pci/pci-sysfs.c:read_vpd_attr
  - drivers/pci/pci-sysfs.c:read_vpd_attr
```
**Symbols:**

```
ffffffff814a41b0-ffffffff814a41d9: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3542)
Location: drivers/pci/access.c:275
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/access.c:pci_vpd_size
  - drivers/pci/access.c:pci_vpd_size
Direct callers:
  - drivers/pci/pci-sysfs.c:read_vpd_attr
  - drivers/pci/pci-sysfs.c:read_vpd_attr
```
**Symbols:**

```
ffffffff814e2f30-ffffffff814e2f5f: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8152522d)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
```
**Symbols:**

```
ffffffff81525150-ffffffff8152517f: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8153b0bd)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
```
**Symbols:**

```
ffffffff8153afe0-ffffffff8153b00f: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8156ab52)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
```
**Symbols:**

```
ffffffff8156aa70-ffffffff8156aa9f: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8158bb22)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff8158ba40-ffffffff8158ba6f: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81632fd2)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff81632ae0-ffffffff81632b0f: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81658122)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff81657c30-ffffffff81657c5f: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8163a8f3)
Location: drivers/pci/vpd.c:43
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff8163a500-ffffffff8163a52f: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff816ab7f5)
Location: drivers/pci/vpd.c:391
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff816ab410-ffffffff816ab494: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff817ceb49)
Location: drivers/pci/vpd.c:412
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_read
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff817ce9d0-ffffffff817cea7b: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff818ee689)
Location: drivers/pci/vpd.c:412
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_read
```
**Symbols:**

```
ffffffff818ee4f0-ffffffff818ee59b: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81931b69)
Location: drivers/pci/vpd.c:412
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_read
```
**Symbols:**

```
ffffffff819319d0-ffffffff81931a7b: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81979ac6)
Location: drivers/pci/vpd.c:442
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_read
```
**Symbols:**

```
ffffffff8197a680-ffffffff8197a72b: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffff8000106f0a28)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
```
**Symbols:**

```
ffff8000106f0868-ffff8000106f08d0: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c088b46c)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
```
**Symbols:**

```
c088b2f8-c088b350: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c00000000086e078)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
c00000000086dee0-c00000000086df40: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffe0004c44b6)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
```
**Symbols:**

```
ffffffe0004c4352-ffffffe0004c43a2: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8157f9a2)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
```
**Symbols:**

```
ffffffff8157f8c0-ffffffff8157f8ef: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8156e782)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff8156e6a0-ffffffff8156e6cf: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8157f872)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff8157f790-ffffffff8157f7bf: pci_read_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_read_vpd(struct pci_dev *dev, loff_t pos, size_t count, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81599d22)
Location: drivers/pci/vpd.c:40
Inline: True
Inline callers:
  - drivers/pci/vpd.c:read_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/vpd.c:pci_vpd_size
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff81599c40-ffffffff81599c6f: pci_read_vpd (STB_GLOBAL)
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
