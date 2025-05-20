# Function: <code>pci_enable_msix_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81454620)
Location: drivers/pci/msi.c:1103
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81454620-ffffffff81454678: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a1130)
Location: drivers/pci/msi.c:1161
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff814a1130-ffffffff814a1143: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c2cc0)
Location: drivers/pci/msi.c:1174
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
**Symbols:**

```
ffffffff814c2cc0-ffffffff814c2d1c: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cd180)
Location: drivers/pci/msi.c:1126
Inline: False
```
**Symbols:**

```
ffffffff814cd180-ffffffff814cd1dc: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150d6c0)
Location: drivers/pci/msi.c:1126
Inline: False
```
**Symbols:**

```
ffffffff8150d6c0-ffffffff8150d71c: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815425b0)
Location: drivers/pci/msi.c:1125
Inline: False
```
**Symbols:**

```
ffffffff815425b0-ffffffff8154260c: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815599a0)
Location: drivers/pci/msi.c:1141
Inline: False
```
**Symbols:**

```
ffffffff815599a0-ffffffff815599b3: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81589a60)
Location: drivers/pci/msi.c:1163
Inline: False
```
**Symbols:**

```
ffffffff81589a60-ffffffff81589a76: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aba50)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
ffffffff815aba50-ffffffff815aba66: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81654aa0)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
ffffffff81654aa0-ffffffff81654ad1: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165e030)
Location: drivers/pci/msi.c:1188
Inline: False
```
**Symbols:**

```
ffffffff8165e030-ffffffff8165e061: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81640210)
Location: drivers/pci/msi.c:1194
Inline: False
```
**Symbols:**

```
ffffffff81640210-ffffffff81640241: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1102
Inline: False
```
**Symbols:**

```
ffffffff81ce5baa-ffffffff81ce5bc8: pci_enable_msix_range.cold (STB_LOCAL)
ffffffff816b1340-ffffffff816b14be: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d4b20)
Location: drivers/pci/msi/msi.c:973
Inline: False
```
**Symbols:**

```
ffffffff817d4b20-ffffffff817d4b48: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f41a0)
Location: drivers/pci/msi/api.c:108
Inline: False
```
**Symbols:**

```
ffffffff818f41a0-ffffffff818f41c8: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff819375d0)
Location: drivers/pci/msi/api.c:108
Inline: False
```
**Symbols:**

```
ffffffff819375d0-ffffffff819375f8: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81980430)
Location: drivers/pci/msi/api.c:108
Inline: False
```
**Symbols:**

```
ffffffff81980430-ffffffff81980458: pci_enable_msix_range (STB_GLOBAL)
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
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff8000107153a8)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
ffff8000107153a8-ffff8000107153fc: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089fc48)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
c089fc48-c089fc78: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000884f70)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
c000000000884f70-c000000000884f8c: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004deaec)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
ffffffe0004deaec-ffffffe0004deb32: pci_enable_msix_range (STB_GLOBAL)
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
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f220)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
ffffffff8159f220-ffffffff8159f236: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158e3b0)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
ffffffff8158e3b0-ffffffff8158e3c6: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f7a0)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
ffffffff8159f7a0-ffffffff8159f7b6: pci_enable_msix_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_enable_msix_range(struct pci_dev *dev, struct msix_entry *entries, int minvec, int maxvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b9bd0)
Location: drivers/pci/msi.c:1164
Inline: False
```
**Symbols:**

```
ffffffff815b9bd0-ffffffff815b9be6: pci_enable_msix_range (STB_GLOBAL)
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
