# Function: <code>vfio_pci_set_msi_trigger</code>

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
int vfio_pci_set_msi_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8e40)
Location: drivers/vfio/pci/vfio_pci_intrs.c:494
Inline: False
```
**Symbols:**

```
ffffffff817d8e40-ffffffff817d90c1: vfio_pci_set_msi_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6890)
Location: drivers/vfio/pci/vfio_pci_intrs.c:508
Inline: False
```
**Symbols:**

```
ffffffff818a6890-ffffffff818a6a1f: vfio_pci_set_msi_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5780)
Location: drivers/vfio/pci/vfio_pci_intrs.c:510
Inline: False
```
**Symbols:**

```
ffffffff818b5780-ffffffff818b590f: vfio_pci_set_msi_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898c20)
Location: drivers/vfio/pci/vfio_pci_intrs.c:510
Inline: False
```
**Symbols:**

```
ffffffff81898c20-ffffffff81898db3: vfio_pci_set_msi_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192c630)
Location: drivers/vfio/pci/vfio_pci_intrs.c:510
Inline: False
```
**Symbols:**

```
ffffffff8192c630-ffffffff8192c7c3: vfio_pci_set_msi_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a82c70)
Location: drivers/vfio/pci/vfio_pci_intrs.c:510
Inline: False
```
**Symbols:**

```
ffffffff81a82c70-ffffffff81a82e36: vfio_pci_set_msi_trigger (STB_LOCAL)
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
int vfio_pci_set_msi_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8dd0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:494
Inline: False
```
**Symbols:**

```
c000000000ab8dd0-c000000000ab91a0: vfio_pci_set_msi_trigger (STB_LOCAL)
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
int vfio_pci_set_msi_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782ef0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:494
Inline: False
```
**Symbols:**

```
ffffffff81782ef0-ffffffff81783171: vfio_pci_set_msi_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdcc0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:494
Inline: False
```
**Symbols:**

```
ffffffff817cdcc0-ffffffff817cdf41: vfio_pci_set_msi_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7f60)
Location: drivers/vfio/pci/vfio_pci_intrs.c:494
Inline: False
```
**Symbols:**

```
ffffffff817e7f60-ffffffff817e81e1: vfio_pci_set_msi_trigger (STB_LOCAL)
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
