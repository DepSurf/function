# Function: <code>vfio_pci_set_intx_trigger</code>

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
int vfio_pci_set_intx_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8ac0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:451
Inline: False
```
**Symbols:**

```
ffffffff817d8ac0-ffffffff817d8c30: vfio_pci_set_intx_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_set_intx_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6ae0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:465
Inline: False
```
**Symbols:**

```
ffffffff818a6ae0-ffffffff818a6d94: vfio_pci_set_intx_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_set_intx_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b59d0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:467
Inline: False
```
**Symbols:**

```
ffffffff818b59d0-ffffffff818b5c84: vfio_pci_set_intx_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pci_set_intx_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898e80)
Location: drivers/vfio/pci/vfio_pci_intrs.c:467
Inline: False
```
**Symbols:**

```
ffffffff81898e80-ffffffff81899138: vfio_pci_set_intx_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_pci_set_intx_trigger(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:467
Inline: False
```
**Symbols:**

```
ffffffff8192c9e0-ffffffff8192ccff: vfio_pci_set_intx_trigger (STB_LOCAL)
ffffffff81d123bf-ffffffff81d12430: vfio_pci_set_intx_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_pci_set_intx_trigger(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:467
Inline: False
```
**Symbols:**

```
ffffffff81a83080-ffffffff81a833a3: vfio_pci_set_intx_trigger (STB_LOCAL)
ffffffff81edd0f7-ffffffff81edd168: vfio_pci_set_intx_trigger.cold (STB_LOCAL)
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
int vfio_pci_set_intx_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8bd0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:451
Inline: False
```
**Symbols:**

```
c000000000ab8bd0-c000000000ab8dcc: vfio_pci_set_intx_trigger (STB_LOCAL)
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
int vfio_pci_set_intx_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782b70)
Location: drivers/vfio/pci/vfio_pci_intrs.c:451
Inline: False
```
**Symbols:**

```
ffffffff81782b70-ffffffff81782ce0: vfio_pci_set_intx_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_pci_set_intx_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cd940)
Location: drivers/vfio/pci/vfio_pci_intrs.c:451
Inline: False
```
**Symbols:**

```
ffffffff817cd940-ffffffff817cdab0: vfio_pci_set_intx_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_pci_set_intx_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7be0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:451
Inline: False
```
**Symbols:**

```
ffffffff817e7be0-ffffffff817e7d50: vfio_pci_set_intx_trigger (STB_LOCAL)
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
