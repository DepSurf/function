# Function: <code>pci_release_selected_regions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81434780)
Location: drivers/pci/pci.c:2917
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffffffff81434780-ffffffff814347bf: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81480151)
Location: drivers/pci/pci.c:3095
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffffffff81480100-ffffffff8148013f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a17a1)
Location: drivers/pci/pci.c:3133
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffffffff814a1750-ffffffff814a178f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab331)
Location: drivers/pci/pci.c:3150
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffffffff814ab2e0-ffffffff814ab31f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ea551)
Location: drivers/pci/pci.c:3260
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffffffff814ea500-ffffffff814ea53f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151ac45)
Location: drivers/pci/pci.c:3406
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffffffff8151ac00-ffffffff8151ac3f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815309a5)
Location: drivers/pci/pci.c:3671
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffffffff81530960-ffffffff8153099f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560325)
Location: drivers/pci/pci.c:3767
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffffffff815602e0-ffffffff8156031f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581445)
Location: drivers/pci/pci.c:3763
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff81581400-ffffffff8158143f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81627815)
Location: drivers/pci/pci.c:3833
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff816276d0-ffffffff8162770f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164d4be)
Location: drivers/pci/pci.c:3897
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff8164d370-ffffffff8164d3af: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162fd9e)
Location: drivers/pci/pci.c:3928
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff8162fc50-ffffffff8162fc8f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169fa7e)
Location: drivers/pci/pci.c:3978
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_mmap
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff8169f930-ffffffff8169f96f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c153e)
Location: drivers/pci/pci.c:4072
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_mmap
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff817c13a0-ffffffff817c13e7: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818ddc9e)
Location: drivers/pci/pci.c:4015
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff818ddaa0-ffffffff818ddae7: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819210fe)
Location: drivers/pci/pci.c:4053
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff81920f00-ffffffff81920f47: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196929e)
Location: drivers/pci/pci.c:4167
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_remove
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff819690a0-ffffffff819690e7: pci_release_selected_regions (STB_GLOBAL)
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
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e445c)
Location: drivers/pci/pci.c:3763
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffff8000106e43d0-ffff8000106e4434: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c088027c)
Location: drivers/pci/pci.c:3763
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
c088021c-c0880268: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085ea28)
Location: drivers/pci/pci.c:3763
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
c00000000085e960-c00000000085e9f4: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bb976)
Location: drivers/pci/pci.c:3763
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
```
**Symbols:**

```
ffffffe0004bb90e-ffffffe0004bb962: pci_release_selected_regions (STB_GLOBAL)
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
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575965)
Location: drivers/pci/pci.c:3763
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/nvme/host/pci.c:nvme_probe
```
**Symbols:**

```
ffffffff81575920-ffffffff8157595f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815640c5)
Location: drivers/pci/pci.c:3763
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff81564080-ffffffff815640bf: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575195)
Location: drivers/pci/pci.c:3763
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff81575150-ffffffff8157518f: pci_release_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_release_selected_regions(struct pci_dev *pdev, int bars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158f765)
Location: drivers/pci/pci.c:3763
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_release_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff8158f720-ffffffff8158f75f: pci_release_selected_regions (STB_GLOBAL)
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
