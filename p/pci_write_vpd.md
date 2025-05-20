# Function: <code>pci_write_vpd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142df20)
Location: drivers/pci/access.c:201
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_write
Direct callers:
  - drivers/pci/pci-sysfs.c:write_vpd_attr
```
**Symbols:**

```
ffffffff8142df20-ffffffff8142df4b: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814795e2)
Location: drivers/pci/access.c:270
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_write
Direct callers:
  - drivers/pci/pci-sysfs.c:write_vpd_attr
  - drivers/pci/pci-sysfs.c:write_vpd_attr
```
**Symbols:**

```
ffffffff814792b0-ffffffff814792da: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149aa72)
Location: drivers/pci/access.c:282
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_write
Direct callers:
  - drivers/pci/pci-sysfs.c:write_vpd_attr
  - drivers/pci/pci-sysfs.c:write_vpd_attr
```
**Symbols:**

```
ffffffff8149a640-ffffffff8149a66a: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a46f2)
Location: drivers/pci/access.c:290
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_write
Direct callers:
  - drivers/pci/pci-sysfs.c:write_vpd_attr
  - drivers/pci/pci-sysfs.c:write_vpd_attr
```
**Symbols:**

```
ffffffff814a41e0-ffffffff814a420a: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e34b2)
Location: drivers/pci/access.c:290
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_write
Direct callers:
  - drivers/pci/pci-sysfs.c:write_vpd_attr
  - drivers/pci/pci-sysfs.c:write_vpd_attr
```
**Symbols:**

```
ffffffff814e2f60-ffffffff814e2f90: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8152528d)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
```
**Symbols:**

```
ffffffff81525180-ffffffff815251b0: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8153b11d)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
```
**Symbols:**

```
ffffffff8153b010-ffffffff8153b040: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8156abb2)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
```
**Symbols:**

```
ffffffff8156aaa0-ffffffff8156aad0: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8158bb82)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff8158ba70-ffffffff8158baa0: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81632e62)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff81632b10-ffffffff81632b40: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81657fb2)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff81657c60-ffffffff81657c90: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8163a823)
Location: drivers/pci/vpd.c:58
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:pci_vpd_f0_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff8163a530-ffffffff8163a560: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff816ab695)
Location: drivers/pci/vpd.c:416
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff816ab600-ffffffff816ab684: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff817ce669)
Location: drivers/pci/vpd.c:450
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff817ce920-ffffffff817ce9cb: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff818ee139)
Location: drivers/pci/vpd.c:450
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_write
```
**Symbols:**

```
ffffffff818ee430-ffffffff818ee4db: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81931619)
Location: drivers/pci/vpd.c:450
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_write
```
**Symbols:**

```
ffffffff81931910-ffffffff819319bb: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8197a236)
Location: drivers/pci/vpd.c:480
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_write
```
**Symbols:**

```
ffffffff8197a500-ffffffff8197a5ab: pci_write_vpd (STB_GLOBAL)
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
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffff8000106f0ac0)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
```
**Symbols:**

```
ffff8000106f08d0-ffff8000106f0938: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c088b508)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
```
**Symbols:**

```
c088b350-c088b3a8: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c00000000086e118)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
c00000000086df40-c00000000086dfa0: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffe0004c4526)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
```
**Symbols:**

```
ffffffe0004c43a2-ffffffe0004c43f2: pci_write_vpd (STB_GLOBAL)
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
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8157fa02)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
```
**Symbols:**

```
ffffffff8157f8f0-ffffffff8157f920: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8156e7e2)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff8156e6d0-ffffffff8156e700: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8157f8d2)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff8157f7c0-ffffffff8157f7f0: pci_write_vpd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_vpd(struct pci_dev *dev, loff_t pos, size_t count, const void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81599d82)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:pci_vpd_f0_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
```
**Symbols:**

```
ffffffff81599c70-ffffffff81599ca0: pci_write_vpd (STB_GLOBAL)
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
