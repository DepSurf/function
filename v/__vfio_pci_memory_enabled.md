# Function: <code>__vfio_pci_memory_enabled</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a9d70)
Location: drivers/vfio/pci/vfio_pci_config.c:399
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff818a9d70-ffffffff818a9d9b: __vfio_pci_memory_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b8ca0)
Location: drivers/vfio/pci/vfio_pci_config.c:399
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff818b8ca0-ffffffff818b8ccb: __vfio_pci_memory_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189c170)
Location: drivers/vfio/pci/vfio_pci_config.c:399
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff8189c170-ffffffff8189c19e: __vfio_pci_memory_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff819303c0)
Location: drivers/vfio/pci/vfio_pci_config.c:399
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff819303c0-ffffffff819303ee: __vfio_pci_memory_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __vfio_pci_memory_enabled(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a86e80)
Location: drivers/vfio/pci/vfio_pci_config.c:399
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff81a86e80-ffffffff81a86ece: __vfio_pci_memory_enabled (STB_GLOBAL)
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
In <code>ppc64el</code>: Absent ⚠️
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
