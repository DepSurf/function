# Function: <code>do_io_rw</code>

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
ssize_t do_io_rw(void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817d9430)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:46
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff817d9430-ffffffff817d96bf: do_io_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_io_rw(struct vfio_pci_device *vdev, bool test_mem, void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818a72c0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:97
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff818a72c0-ffffffff818a77c0: do_io_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_io_rw(struct vfio_pci_device *vdev, bool test_mem, void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818b6220)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:97
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff818b6220-ffffffff818b6720: do_io_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_io_rw(struct vfio_pci_device *vdev, bool test_mem, void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818996e0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:97
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff818996e0-ffffffff81899bce: do_io_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t do_io_rw(struct vfio_pci_core_device *vdev, bool test_mem, void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff8192d290)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:97
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff8192d290-ffffffff8192d77e: do_io_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t do_io_rw(struct vfio_pci_core_device *vdev, bool test_mem, void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81a83a30)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:97
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81a83a30-ffffffff81a83f3c: do_io_rw (STB_LOCAL)
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
ssize_t do_io_rw(void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (c000000000ab9710)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:46
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
c000000000ab9710-c000000000ab9a68: do_io_rw (STB_LOCAL)
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
ssize_t do_io_rw(void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817834e0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:46
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff817834e0-ffffffff8178376f: do_io_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_io_rw(void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817ce2b0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:46
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff817ce2b0-ffffffff817ce53f: do_io_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_io_rw(void *io, char *buf, loff_t off, size_t count, size_t x_start, size_t x_end, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817e8550)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:46
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff817e8550-ffffffff817e87df: do_io_rw (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_pci_device *vdev</code>
</li>
<li>
<b>Param added. </b>
<code>bool test_mem</code>
</li>
<li>
<b>Param reordered. </b>
<code>io, buf, off, count, x_start, x_end, iswrite</code> ➡️ <code>vdev, test_mem, io, buf, off, count, x_start, x_end, iswrite</code>
</li>
</ul>
</details>
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
