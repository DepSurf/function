# Function: <code>vfio_basic_config_write</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vfio_basic_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:536
Inline: False
```
**Symbols:**

```
ffffffff817da600-ffffffff817da7e9: vfio_basic_config_write (STB_LOCAL)
ffffffff817dbf2e-ffffffff817dbffe: vfio_basic_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_basic_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a8430)
Location: drivers/vfio/pci/vfio_pci_config.c:552
Inline: False
```
**Symbols:**

```
ffffffff818a8430-ffffffff818a868d: vfio_basic_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_basic_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b7260)
Location: drivers/vfio/pci/vfio_pci_config.c:555
Inline: False
```
**Symbols:**

```
ffffffff818b7260-ffffffff818b74eb: vfio_basic_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_basic_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:555
Inline: False
```
**Symbols:**

```
ffffffff8189a6d0-ffffffff8189a960: vfio_basic_config_write (STB_LOCAL)
ffffffff81c0c165-ffffffff81c0c251: vfio_basic_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_basic_config_write(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:555
Inline: False
```
**Symbols:**

```
ffffffff8192ebf0-ffffffff8192ef14: vfio_basic_config_write (STB_LOCAL)
ffffffff81d12584-ffffffff81d126df: vfio_basic_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_basic_config_write(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:558
Inline: False
```
**Symbols:**

```
ffffffff81a854a0-ffffffff81a857be: vfio_basic_config_write (STB_LOCAL)
ffffffff81edd2b6-ffffffff81edd3e4: vfio_basic_config_write.cold (STB_LOCAL)
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
int vfio_basic_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abac90)
Location: drivers/vfio/pci/vfio_pci_config.c:536
Inline: False
```
**Symbols:**

```
c000000000abac90-c000000000abb014: vfio_basic_config_write (STB_LOCAL)
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
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vfio_basic_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:536
Inline: False
```
**Symbols:**

```
ffffffff817846b0-ffffffff81784899: vfio_basic_config_write (STB_LOCAL)
ffffffff81785fde-ffffffff817860ae: vfio_basic_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_basic_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:536
Inline: False
```
**Symbols:**

```
ffffffff817cf480-ffffffff817cf669: vfio_basic_config_write (STB_LOCAL)
ffffffff817d0dae-ffffffff817d0e7e: vfio_basic_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_basic_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:536
Inline: False
```
**Symbols:**

```
ffffffff817e9720-ffffffff817e9909: vfio_basic_config_write (STB_LOCAL)
ffffffff817eb04e-ffffffff817eb11e: vfio_basic_config_write.cold (STB_LOCAL)
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
