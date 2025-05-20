# Function: <code>vfio_set_irqs_validate_and_prepare</code>

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
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817cff50)
Location: drivers/vfio/vfio.c:1875
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff817cff50-ffffffff817cffe4: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189a9b0)
Location: drivers/vfio/vfio.c:1895
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8189a9b0-ffffffff8189aa44: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9560)
Location: drivers/vfio/vfio.c:1896
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff818a9560-ffffffff818a95f4: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188c920)
Location: drivers/vfio/vfio.c:1795
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8188c920-ffffffff8188c9bb: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8191fe00)
Location: drivers/vfio/vfio.c:1902
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
**Symbols:**

```
ffffffff8191fe00-ffffffff8191fe9b: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a758f0)
Location: drivers/vfio/vfio.c:1867
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
**Symbols:**

```
ffffffff81a758f0-ffffffff81a7598f: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
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
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aad930)
Location: drivers/vfio/vfio.c:1875
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
c000000000aad930-c000000000aada18: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
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
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a000)
Location: drivers/vfio/vfio.c:1875
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8177a000-ffffffff8177a094: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c4dd0)
Location: drivers/vfio/vfio.c:1875
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff817c4dd0-ffffffff817c4e64: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_set_irqs_validate_and_prepare(struct vfio_irq_set *hdr, int num_irqs, int max_irq_type, size_t *data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df070)
Location: drivers/vfio/vfio.c:1875
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff817df070-ffffffff817df104: vfio_set_irqs_validate_and_prepare (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
