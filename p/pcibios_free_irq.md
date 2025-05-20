# Function: <code>pcibios_free_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8143a6d0)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:pci_enable_msi_range
```
**Symbols:**

```
ffffffff816fa7e0-ffffffff816fa7fa: pcibios_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814865f0)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff814865f0-ffffffff814865fb: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814a7db0)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff814a7db0-ffffffff814a7dbb: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814b1d60)
Location: drivers/pci/pci-driver.c:396
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff814b1d60-ffffffff814b1d6b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814f1440)
Location: drivers/pci/pci-driver.c:396
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff814f1440-ffffffff814f144b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81521630)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff81521630-ffffffff8152163b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81537460)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81537460-ffffffff8153746b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81566db0)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81566db0-ffffffff81566dbb: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81588110)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81588110-ffffffff8158811b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162ee50)
Location: drivers/pci/pci-driver.c:396
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff8162ee50-ffffffff8162ee5b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81654510)
Location: drivers/pci/pci-driver.c:401
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81654510-ffffffff8165451b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81636ec0)
Location: drivers/pci/pci-driver.c:401
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81636ec0-ffffffff81636ecb: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a7100)
Location: drivers/pci/pci-driver.c:415
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
```
**Symbols:**

```
ffffffff816a7100-ffffffff816a710b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c9b90)
Location: drivers/pci/pci-driver.c:427
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
```
**Symbols:**

```
ffffffff817c9b90-ffffffff817c9b9f: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e75b0)
Location: drivers/pci/pci-driver.c:427
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff818e75b0-ffffffff818e75bf: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8192abd0)
Location: drivers/pci/pci-driver.c:427
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff8192abd0-ffffffff8192abdf: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81973460)
Location: drivers/pci/pci-driver.c:427
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81973460-ffffffff8197346f: pcibios_free_irq (STB_WEAK)
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
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106ec4d8)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffff8000106ec4d8-ffff8000106ec4f0: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0887804)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c0887804-c088781c: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c000000000868100)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c000000000868100-c00000000086810c: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffe0004c15a0)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffe0004c15a0-ffffffe0004c15ba: pcibios_free_irq (STB_WEAK)
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
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157bfa0)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8157bfa0-ffffffff8157bfab: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8156ad70)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8156ad70-ffffffff8156ad7b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157be60)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8157be60-ffffffff8157be6b: pcibios_free_irq (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcibios_free_irq(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81596310)
Location: drivers/pci/pci-driver.c:395
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81596310-ffffffff8159631b: pcibios_free_irq (STB_WEAK)
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
