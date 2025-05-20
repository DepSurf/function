# Function: <code>vfio_pci_memory_unlock_and_restore</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_memory_unlock_and_restore(struct vfio_pci_device *vdev, u16 cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a412c)
Location: drivers/vfio/pci/vfio_pci.c:1491
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
**Symbols:**

```
ffffffff818a5c40-ffffffff818a5c6f: vfio_pci_memory_unlock_and_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_memory_unlock_and_restore(struct vfio_pci_device *vdev, u16 cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b316b)
Location: drivers/vfio/pci/vfio_pci.c:1566
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
**Symbols:**

```
ffffffff818b4d70-ffffffff818b4d9f: vfio_pci_memory_unlock_and_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_memory_unlock_and_restore(struct vfio_pci_device *vdev, u16 cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81896340)
Location: drivers/vfio/pci/vfio_pci.c:1546
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
**Symbols:**

```
ffffffff81898200-ffffffff81898230: vfio_pci_memory_unlock_and_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_memory_unlock_and_restore(struct vfio_pci_core_device *vdev, u16 cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192a2e0)
Location: drivers/vfio/pci/vfio_pci_core.c:1348
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
**Symbols:**

```
ffffffff8192bb90-ffffffff8192bbc0: vfio_pci_memory_unlock_and_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_memory_unlock_and_restore(struct vfio_pci_core_device *vdev, u16 cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a81e34)
Location: drivers/vfio/pci/vfio_pci_core.c:1378
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
**Symbols:**

```
ffffffff81a820e0-ffffffff81a8211f: vfio_pci_memory_unlock_and_restore (STB_GLOBAL)
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
