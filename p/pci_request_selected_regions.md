# Function: <code>pci_request_selected_regions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81434a10)
Location: drivers/pci/pci.c:2953
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff81434a10-ffffffff81434a22: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814803a9)
Location: drivers/pci/pci.c:3131
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff81480380-ffffffff81480392: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a19f9)
Location: drivers/pci/pci.c:3169
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff814a19d0-ffffffff814a19e2: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab589)
Location: drivers/pci/pci.c:3186
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff814ab560-ffffffff814ab572: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ea7a9)
Location: drivers/pci/pci.c:3296
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff814ea780-ffffffff814ea792: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151ae55)
Location: drivers/pci/pci.c:3442
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff8151ae30-ffffffff8151ae42: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81530bc5)
Location: drivers/pci/pci.c:3707
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff81530ba0-ffffffff81530bb2: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560505)
Location: drivers/pci/pci.c:3803
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff815604e0-ffffffff815604f2: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581625)
Location: drivers/pci/pci.c:3799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff81581600-ffffffff81581612: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816277b5)
Location: drivers/pci/pci.c:3869
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff81627790-ffffffff816277a2: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164d459)
Location: drivers/pci/pci.c:3933
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff8164d430-ffffffff8164d442: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162fd39)
Location: drivers/pci/pci.c:3964
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff8162fd10-ffffffff8162fd22: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169fa19)
Location: drivers/pci/pci.c:4014
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff8169f9f0-ffffffff8169fa02: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c14a9)
Location: drivers/pci/pci.c:4108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff817c1480-ffffffff817c149e: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818ddbd9)
Location: drivers/pci/pci.c:4051
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff818ddba0-ffffffff818ddbbe: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81921039)
Location: drivers/pci/pci.c:4089
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff81921000-ffffffff8192101e: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819691d9)
Location: drivers/pci/pci.c:4203
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
```
**Symbols:**

```
ffffffff819691a0-ffffffff819691be: pci_request_selected_regions (STB_GLOBAL)
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
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e470c)
Location: drivers/pci/pci.c:3799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffff8000106e46a8-ffff8000106e46f0: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08804b4)
Location: drivers/pci/pci.c:3799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
c0880480-c08804a0: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085eda0)
Location: drivers/pci/pci.c:3799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
c00000000085ed70-c00000000085ed88: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bbbc6)
Location: drivers/pci/pci.c:3799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffe0004bbb70-ffffffe0004bbbac: pci_request_selected_regions (STB_GLOBAL)
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
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575b45)
Location: drivers/pci/pci.c:3799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/nvme/host/pci.c:nvme_probe
```
**Symbols:**

```
ffffffff81575b20-ffffffff81575b32: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815642a5)
Location: drivers/pci/pci.c:3799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff81564280-ffffffff81564292: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575375)
Location: drivers/pci/pci.c:3799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff81575350-ffffffff81575362: pci_request_selected_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_request_selected_regions(struct pci_dev *pdev, int bars, const char *res_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158f945)
Location: drivers/pci/pci.c:3799
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_request_regions
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_setup_barmap
```
**Symbols:**

```
ffffffff8158f920-ffffffff8158f932: pci_request_selected_regions (STB_GLOBAL)
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
