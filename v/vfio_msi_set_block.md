# Function: <code>vfio_msi_set_block</code>

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
int vfio_msi_set_block(struct vfio_pci_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8700)
Location: drivers/vfio/pci/vfio_pci_intrs.c:354
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
ffffffff817d8700-ffffffff817d87ca: vfio_msi_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_msi_set_block(struct vfio_pci_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6250)
Location: drivers/vfio/pci/vfio_pci_intrs.c:365
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
ffffffff818a6250-ffffffff818a631a: vfio_msi_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_msi_set_block(struct vfio_pci_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5140)
Location: drivers/vfio/pci/vfio_pci_intrs.c:367
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
ffffffff818b5140-ffffffff818b520a: vfio_msi_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_msi_set_block(struct vfio_pci_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818985e0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:367
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
ffffffff818985e0-ffffffff818986aa: vfio_msi_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_msi_set_block(struct vfio_pci_core_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192be60)
Location: drivers/vfio/pci/vfio_pci_intrs.c:367
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
ffffffff8192be60-ffffffff8192bf2a: vfio_msi_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_msi_set_block(struct vfio_pci_core_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a825a0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:367
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
ffffffff81a825a0-ffffffff81a82682: vfio_msi_set_block (STB_LOCAL)
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
int vfio_msi_set_block(struct vfio_pci_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8240)
Location: drivers/vfio/pci/vfio_pci_intrs.c:354
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
c000000000ab8240-c000000000ab8418: vfio_msi_set_block (STB_LOCAL)
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
int vfio_msi_set_block(struct vfio_pci_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817827b0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:354
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
ffffffff817827b0-ffffffff8178287a: vfio_msi_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_msi_set_block(struct vfio_pci_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cd580)
Location: drivers/vfio/pci/vfio_pci_intrs.c:354
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
ffffffff817cd580-ffffffff817cd64a: vfio_msi_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_msi_set_block(struct vfio_pci_device *vdev, unsigned int start, unsigned int count, int32_t *fds, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7820)
Location: drivers/vfio/pci/vfio_pci_intrs.c:354
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
```
**Symbols:**

```
ffffffff817e7820-ffffffff817e78ea: vfio_msi_set_block (STB_LOCAL)
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
