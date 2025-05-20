# Function: <code>pci_unmap_rom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8143cf60)
Location: drivers/pci/rom.c:181
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff8143cf60-ffffffff8143cf98: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81488ec0)
Location: drivers/pci/rom.c:169
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff81488ec0-ffffffff81488eec: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff814aa690)
Location: drivers/pci/rom.c:174
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff814aa690-ffffffff814aa6bc: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff814b49e0)
Location: drivers/pci/rom.c:174
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff814b49e0-ffffffff814b4a0c: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff814f4200)
Location: drivers/pci/rom.c:181
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff814f4200-ffffffff814f422c: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff815242c0)
Location: drivers/pci/rom.c:180
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff815242c0-ffffffff815242ec: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8153a100)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff8153a100-ffffffff8153a12c: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81569b70)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff81569b70-ffffffff81569ba1: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8158ab40)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff8158ab40-ffffffff8158ab71: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81631ae0)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81631ae0-ffffffff81631b59: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff816570f0)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff816570f0-ffffffff81657169: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff816399b0)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff816399b0-ffffffff81639a29: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff816aa180)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff816aa180-ffffffff816aa1f9: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff817cd090)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff817cd090-ffffffff817cd0d2: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff818ec4e0)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff818ec4e0-ffffffff818ec522: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8192f9c0)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff8192f9c0-ffffffff8192fa02: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81978340)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff81978340-ffffffff81978382: pci_unmap_rom (STB_GLOBAL)
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
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffff8000106ef690)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffff8000106ef690-ffff8000106ef6e0: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (c088a378)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
c088a378-c088a3b0: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (c00000000086c680)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
c00000000086c680-c00000000086c6e8: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffe0004c35e6)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffe0004c35e6-ffffffe0004c3634: pci_unmap_rom (STB_GLOBAL)
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
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8157e9c0)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff8157e9c0-ffffffff8157e9f1: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8156d7a0)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff8156d7a0-ffffffff8156d7d1: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8157e890)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff8157e890-ffffffff8157e8c1: pci_unmap_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_unmap_rom(struct pci_dev *pdev, void *rom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81598d40)
Location: drivers/pci/rom.c:187
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81598d40-ffffffff81598d71: pci_unmap_rom (STB_GLOBAL)
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
