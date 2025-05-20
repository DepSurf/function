# Function: <code>vfio_pci_set_intx_unmask</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d9200)
Location: drivers/vfio/pci/vfio_pci_intrs.c:404
Inline: True
```
**Symbols:**

```
ffffffff817d9200-ffffffff817d9285: vfio_pci_set_intx_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6ef0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:418
Inline: True
```
**Symbols:**

```
ffffffff818a6ef0-ffffffff818a6fcf: vfio_pci_set_intx_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5de0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:420
Inline: True
```
**Symbols:**

```
ffffffff818b5de0-ffffffff818b5ebf: vfio_pci_set_intx_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81899290)
Location: drivers/vfio/pci/vfio_pci_intrs.c:420
Inline: True
```
**Symbols:**

```
ffffffff81899290-ffffffff8189936f: vfio_pci_set_intx_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192c8ef)
Location: drivers/vfio/pci/vfio_pci_intrs.c:420
Inline: True
```
**Symbols:**

```
ffffffff8192c8c0-ffffffff8192c9d9: vfio_pci_set_intx_unmask (STB_LOCAL)
ffffffff81d12397-ffffffff81d123bf: vfio_pci_set_intx_unmask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:420
Inline: False
```
**Symbols:**

```
ffffffff81a82f40-ffffffff81a8307a: vfio_pci_set_intx_unmask (STB_LOCAL)
ffffffff81edd0cd-ffffffff81edd0f7: vfio_pci_set_intx_unmask.cold (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab93a0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:404
Inline: True
```
**Symbols:**

```
c000000000ab93a0-c000000000ab94a8: vfio_pci_set_intx_unmask (STB_LOCAL)
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
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817832b0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:404
Inline: True
```
**Symbols:**

```
ffffffff817832b0-ffffffff81783335: vfio_pci_set_intx_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817ce080)
Location: drivers/vfio/pci/vfio_pci_intrs.c:404
Inline: True
```
**Symbols:**

```
ffffffff817ce080-ffffffff817ce105: vfio_pci_set_intx_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_unmask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e8320)
Location: drivers/vfio/pci/vfio_pci_intrs.c:404
Inline: True
```
**Symbols:**

```
ffffffff817e8320-ffffffff817e83a5: vfio_pci_set_intx_unmask (STB_LOCAL)
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
