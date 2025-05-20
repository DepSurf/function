# Function: <code>vfio_pci_set_intx_mask</code>

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
int vfio_pci_set_intx_mask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d9170)
Location: drivers/vfio/pci/vfio_pci_intrs.c:431
Inline: True
```
**Symbols:**

```
ffffffff817d9170-ffffffff817d91c5: vfio_pci_set_intx_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_mask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6e40)
Location: drivers/vfio/pci/vfio_pci_intrs.c:445
Inline: True
```
**Symbols:**

```
ffffffff818a6e40-ffffffff818a6e99: vfio_pci_set_intx_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_mask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5d30)
Location: drivers/vfio/pci/vfio_pci_intrs.c:447
Inline: True
```
**Symbols:**

```
ffffffff818b5d30-ffffffff818b5d89: vfio_pci_set_intx_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_mask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818991e0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:447
Inline: True
```
**Symbols:**

```
ffffffff818991e0-ffffffff81899239: vfio_pci_set_intx_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_mask(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192cdd0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:447
Inline: True
```
**Symbols:**

```
ffffffff8192cdd0-ffffffff8192ce29: vfio_pci_set_intx_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_pci_set_intx_mask(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a83480)
Location: drivers/vfio/pci/vfio_pci_intrs.c:447
Inline: False
```
**Symbols:**

```
ffffffff81a83480-ffffffff81a834f3: vfio_pci_set_intx_mask (STB_LOCAL)
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
int vfio_pci_set_intx_mask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab9290)
Location: drivers/vfio/pci/vfio_pci_intrs.c:431
Inline: True
```
**Symbols:**

```
c000000000ab9290-c000000000ab9330: vfio_pci_set_intx_mask (STB_LOCAL)
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
int vfio_pci_set_intx_mask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81783220)
Location: drivers/vfio/pci/vfio_pci_intrs.c:431
Inline: True
```
**Symbols:**

```
ffffffff81783220-ffffffff81783275: vfio_pci_set_intx_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_mask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdff0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:431
Inline: True
```
**Symbols:**

```
ffffffff817cdff0-ffffffff817ce045: vfio_pci_set_intx_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_set_intx_mask(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e8290)
Location: drivers/vfio/pci/vfio_pci_intrs.c:431
Inline: True
```
**Symbols:**

```
ffffffff817e8290-ffffffff817e82e5: vfio_pci_set_intx_mask (STB_LOCAL)
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
