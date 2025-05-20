# Function: <code>vfio_pci_vga_rw</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817d9930)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:214
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff817d9930-ffffffff817d9b53: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818a79f0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:291
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff818a79f0-ffffffff818a7c19: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818b6950)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:291
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff818b6950-ffffffff818b6b79: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81899e00)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:291
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff81899e00-ffffffff8189a035: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:291
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff81d12502-ffffffff81d12525: vfio_pci_vga_rw.cold (STB_LOCAL)
ffffffff8192db30-ffffffff8192dd77: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:292
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff81edd22a-ffffffff81edd24d: vfio_pci_vga_rw.cold (STB_LOCAL)
ffffffff81a842e0-ffffffff81a84564: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (c000000000ab9d90)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:214
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
c000000000ab9d90-c000000000aba064: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817839e0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:214
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff817839e0-ffffffff81783c03: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817ce7b0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:214
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff817ce7b0-ffffffff817ce9d3: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfio_pci_vga_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817e8a50)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:214
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff817e8a50-ffffffff817e8c73: vfio_pci_vga_rw (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device *vdev</code> ➡️ <code>struct vfio_pci_core_device *vdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
