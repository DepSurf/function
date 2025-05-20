# Function: <code>vfio_pci_ioeventfd</code>

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
long int vfio_pci_ioeventfd(struct vfio_pci_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817d9b60)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:301
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff817d9b60-ffffffff817d9e2e: vfio_pci_ioeventfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfio_pci_ioeventfd(struct vfio_pci_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818a7c20)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:387
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff818a7c20-ffffffff818a7eef: vfio_pci_ioeventfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_pci_ioeventfd(struct vfio_pci_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818b6b80)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:413
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff818b6b80-ffffffff818b6e54: vfio_pci_ioeventfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfio_pci_ioeventfd(struct vfio_pci_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff8189a040)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:413
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8189a040-ffffffff8189a315: vfio_pci_ioeventfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int vfio_pci_ioeventfd(struct vfio_pci_core_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff8192dd80)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:413
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
**Symbols:**

```
ffffffff8192dd80-ffffffff8192e156: vfio_pci_ioeventfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int vfio_pci_ioeventfd(struct vfio_pci_core_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81a84570)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:415
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
**Symbols:**

```
ffffffff81a84570-ffffffff81a8491b: vfio_pci_ioeventfd (STB_GLOBAL)
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
long int vfio_pci_ioeventfd(struct vfio_pci_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (c000000000aba070)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:301
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
c000000000aba070-c000000000aba3a8: vfio_pci_ioeventfd (STB_GLOBAL)
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
long int vfio_pci_ioeventfd(struct vfio_pci_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81783c10)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:301
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff81783c10-ffffffff81783ede: vfio_pci_ioeventfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int vfio_pci_ioeventfd(struct vfio_pci_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817ce9e0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:301
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff817ce9e0-ffffffff817cecae: vfio_pci_ioeventfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int vfio_pci_ioeventfd(struct vfio_pci_device *vdev, loff_t offset, uint64_t data, int count, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817e8c80)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:301
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff817e8c80-ffffffff817e8f4e: vfio_pci_ioeventfd (STB_GLOBAL)
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
