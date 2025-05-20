# Function: <code>vfio_vpd_config_write</code>

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
int vfio_vpd_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817da7f0)
Location: drivers/vfio/pci/vfio_pci_config.c:719
Inline: False
```
**Symbols:**

```
ffffffff817da7f0-ffffffff817da8de: vfio_vpd_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_vpd_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a8690)
Location: drivers/vfio/pci/vfio_pci_config.c:745
Inline: False
```
**Symbols:**

```
ffffffff818a8690-ffffffff818a877d: vfio_vpd_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_vpd_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b74f0)
Location: drivers/vfio/pci/vfio_pci_config.c:750
Inline: False
```
**Symbols:**

```
ffffffff818b74f0-ffffffff818b75dd: vfio_vpd_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_vpd_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189a960)
Location: drivers/vfio/pci/vfio_pci_config.c:750
Inline: False
```
**Symbols:**

```
ffffffff8189a960-ffffffff8189aa52: vfio_vpd_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_vpd_config_write(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192e520)
Location: drivers/vfio/pci/vfio_pci_config.c:750
Inline: False
```
**Symbols:**

```
ffffffff8192e520-ffffffff8192e612: vfio_vpd_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_vpd_config_write(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a84d70)
Location: drivers/vfio/pci/vfio_pci_config.c:786
Inline: False
```
**Symbols:**

```
ffffffff81a84d70-ffffffff81a84e7e: vfio_vpd_config_write (STB_LOCAL)
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
int vfio_vpd_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abb020)
Location: drivers/vfio/pci/vfio_pci_config.c:719
Inline: False
```
**Symbols:**

```
c000000000abb020-c000000000abb16c: vfio_vpd_config_write (STB_LOCAL)
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
int vfio_vpd_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817848a0)
Location: drivers/vfio/pci/vfio_pci_config.c:719
Inline: False
```
**Symbols:**

```
ffffffff817848a0-ffffffff8178498e: vfio_vpd_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_vpd_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cf670)
Location: drivers/vfio/pci/vfio_pci_config.c:719
Inline: False
```
**Symbols:**

```
ffffffff817cf670-ffffffff817cf75e: vfio_vpd_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_vpd_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e9910)
Location: drivers/vfio/pci/vfio_pci_config.c:719
Inline: False
```
**Symbols:**

```
ffffffff817e9910-ffffffff817e99fe: vfio_vpd_config_write (STB_LOCAL)
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
