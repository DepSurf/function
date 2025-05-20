# Function: <code>pci_map_rom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8143d040)
Location: drivers/pci/rom.c:117
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff8143d040-ffffffff8143d187: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81488f90)
Location: drivers/pci/rom.c:125
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff81488f90-ffffffff8148905a: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff814aa760)
Location: drivers/pci/rom.c:130
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff814aa760-ffffffff814aa82a: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff814b4ab0)
Location: drivers/pci/rom.c:130
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff814b4ab0-ffffffff814b4b73: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff814f42d0)
Location: drivers/pci/rom.c:130
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff814f42d0-ffffffff814f43a3: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81524390)
Location: drivers/pci/rom.c:129
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff81524390-ffffffff8152445e: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8153a130)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff8153a130-ffffffff8153a2dd: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff81569d3c-ffffffff81569d5d: pci_map_rom.cold (STB_LOCAL)
ffffffff81569bb0-ffffffff81569d3c: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff8158ad0c-ffffffff8158ad2d: pci_map_rom.cold (STB_LOCAL)
ffffffff8158ab80-ffffffff8158ad0c: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81631b60)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81631b60-ffffffff81631c71: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81657170)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81657170-ffffffff81657281: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81bea063-ffffffff81bea07c: pci_map_rom.cold (STB_LOCAL)
ffffffff81639a30-ffffffff81639bf4: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81ce4e62-ffffffff81ce4e7b: pci_map_rom.cold (STB_LOCAL)
ffffffff816aa200-ffffffff816aa3c1: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81eab8ec-ffffffff81eab905: pci_map_rom.cold (STB_LOCAL)
ffffffff817cd0e0-ffffffff817cd25c: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff818ec540)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff818ec540-ffffffff818ec6d1: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8192fa20)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff8192fa20-ffffffff8192fbb1: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff819783a0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff819783a0-ffffffff81978531: pci_map_rom (STB_GLOBAL)
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
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffff8000106ef6e0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffff8000106ef6e0-ffff8000106ef9d4: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (c088a3b0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
c088a3b0-c088a57c: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (c00000000086c6f0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
c00000000086c6f0-c00000000086cc3c: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffe0004c3634)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffe0004c3634-ffffffe0004c37dc: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
**Symbols:**

```
ffffffff8157eb8c-ffffffff8157ebad: pci_map_rom.cold (STB_LOCAL)
ffffffff8157ea00-ffffffff8157eb8c: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff8156d96c-ffffffff8156d98d: pci_map_rom.cold (STB_LOCAL)
ffffffff8156d7e0-ffffffff8156d96c: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff8157ea5c-ffffffff8157ea7d: pci_map_rom.cold (STB_LOCAL)
ffffffff8157e8d0-ffffffff8157ea5c: pci_map_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *pci_map_rom(struct pci_dev *pdev, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:136
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81598f0c-ffffffff81598f2d: pci_map_rom.cold (STB_LOCAL)
ffffffff81598d80-ffffffff81598f0c: pci_map_rom (STB_GLOBAL)
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
