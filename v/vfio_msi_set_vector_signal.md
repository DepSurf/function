# Function: <code>vfio_msi_set_vector_signal</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:284
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
ffffffff817d84a0-ffffffff817d86f5: vfio_msi_set_vector_signal (STB_LOCAL)
ffffffff817d9361-ffffffff817d938f: vfio_msi_set_vector_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:288
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
ffffffff818a5fd0-ffffffff818a6247: vfio_msi_set_vector_signal (STB_LOCAL)
ffffffff818a7097-ffffffff818a70c1: vfio_msi_set_vector_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:288
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
ffffffff818b4ec0-ffffffff818b5137: vfio_msi_set_vector_signal (STB_LOCAL)
ffffffff81c1a274-ffffffff81c1a2ae: vfio_msi_set_vector_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:288
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
ffffffff81898360-ffffffff818985d8: vfio_msi_set_vector_signal (STB_LOCAL)
ffffffff81c0c107-ffffffff81c0c141: vfio_msi_set_vector_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_core_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:288
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
ffffffff8192bbe0-ffffffff8192be58: vfio_msi_set_vector_signal (STB_LOCAL)
ffffffff81d1224e-ffffffff81d12288: vfio_msi_set_vector_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_core_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:288
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
ffffffff81a822e0-ffffffff81a82598: vfio_msi_set_vector_signal (STB_LOCAL)
ffffffff81edcf88-ffffffff81edcfbc: vfio_msi_set_vector_signal.cold (STB_LOCAL)
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
int vfio_msi_set_vector_signal(struct vfio_pci_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab7ed0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:284
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
c000000000ab7ed0-c000000000ab8240: vfio_msi_set_vector_signal (STB_LOCAL)
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
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:284
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
ffffffff81782550-ffffffff817827a5: vfio_msi_set_vector_signal (STB_LOCAL)
ffffffff81783411-ffffffff8178343f: vfio_msi_set_vector_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:284
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
ffffffff817cd320-ffffffff817cd575: vfio_msi_set_vector_signal (STB_LOCAL)
ffffffff817ce1e1-ffffffff817ce20f: vfio_msi_set_vector_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_device *vdev, int vector, int fd, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:284
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block
```
**Symbols:**

```
ffffffff817e75c0-ffffffff817e7815: vfio_msi_set_vector_signal (STB_LOCAL)
ffffffff817e8481-ffffffff817e84af: vfio_msi_set_vector_signal.cold (STB_LOCAL)
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
