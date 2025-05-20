# Function: <code>pci_msix_vec_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81453820)
Location: drivers/pci/msi.c:919
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff81453820-ffffffff8145387e: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a00c0)
Location: drivers/pci/msi.c:933
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff814a00c0-ffffffff814a011e: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c1c40)
Location: drivers/pci/msi.c:947
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff814c1c40-ffffffff814c1c9e: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cc2a0)
Location: drivers/pci/msi.c:923
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff814cc2a0-ffffffff814cc2fa: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150c7d0)
Location: drivers/pci/msi.c:923
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff8150c7d0-ffffffff8150c82a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81541610)
Location: drivers/pci/msi.c:923
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff81541610-ffffffff8154166a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81558970)
Location: drivers/pci/msi.c:922
Inline: False
```
**Symbols:**

```
ffffffff81558970-ffffffff815589ca: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81588a00)
Location: drivers/pci/msi.c:957
Inline: False
```
**Symbols:**

```
ffffffff81588a00-ffffffff81588a5a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aa320)
Location: drivers/pci/msi.c:958
Inline: False
```
**Symbols:**

```
ffffffff815aa320-ffffffff815aa37a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816543fd)
Location: drivers/pci/msi.c:958
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
```
**Symbols:**

```
ffffffff816532c0-ffffffff8165331a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165dadd)
Location: drivers/pci/msi.c:982
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
```
**Symbols:**

```
ffffffff8165cff0-ffffffff8165d04a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8163fce7)
Location: drivers/pci/msi.c:990
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
```
**Symbols:**

```
ffffffff8163f590-ffffffff8163f5ea: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b1628)
Location: drivers/pci/msi.c:898
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
  - drivers/pci/msi.c:msix_capability_init
```
**Symbols:**

```
ffffffff816b0420-ffffffff816b047a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d3e69)
Location: drivers/pci/msi/msi.c:776
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:msix_setup_msi_descs
```
**Symbols:**

```
ffffffff817d3a10-ffffffff817d3a7a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f4120)
Location: drivers/pci/msi/api.c:71
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msix_setup_msi_descs
```
**Symbols:**

```
ffffffff818f4120-ffffffff818f418a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81937550)
Location: drivers/pci/msi/api.c:71
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msix_setup_msi_descs
```
**Symbols:**

```
ffffffff81937550-ffffffff819375ba: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff819803b0)
Location: drivers/pci/msi/api.c:71
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msix_setup_msi_descs
```
**Symbols:**

```
ffffffff819803b0-ffffffff8198041a: pci_msix_vec_count (STB_GLOBAL)
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
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010713888)
Location: drivers/pci/msi.c:958
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_vec_count
```
**Symbols:**

```
ffff800010713888-ffff800010713900: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089e49c)
Location: drivers/pci/msi.c:958
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_vec_count
```
**Symbols:**

```
c089e49c-c089e518: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000883180)
Location: drivers/pci/msi.c:958
Inline: False
```
**Symbols:**

```
c000000000883180-c000000000883218: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004dd5f4)
Location: drivers/pci/msi.c:958
Inline: False
```
**Symbols:**

```
ffffffe0004dd5f4-ffffffe0004dd638: pci_msix_vec_count (STB_GLOBAL)
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
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159daf0)
Location: drivers/pci/msi.c:958
Inline: False
```
**Symbols:**

```
ffffffff8159daf0-ffffffff8159db4a: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158cc80)
Location: drivers/pci/msi.c:958
Inline: False
```
**Symbols:**

```
ffffffff8158cc80-ffffffff8158ccda: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159e070)
Location: drivers/pci/msi.c:958
Inline: False
```
**Symbols:**

```
ffffffff8159e070-ffffffff8159e0ca: pci_msix_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_msix_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b84a0)
Location: drivers/pci/msi.c:958
Inline: False
```
**Symbols:**

```
ffffffff815b84a0-ffffffff815b84fa: pci_msix_vec_count (STB_GLOBAL)
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
