# Function: <code>vfio_msi_config_read</code>

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
int vfio_msi_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817da060)
Location: drivers/vfio/pci/vfio_pci_config.c:1055
Inline: False
```
**Symbols:**

```
ffffffff817da060-ffffffff817da0e7: vfio_msi_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_msi_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a9070)
Location: drivers/vfio/pci/vfio_pci_config.c:1087
Inline: False
```
**Symbols:**

```
ffffffff818a9070-ffffffff818a9100: vfio_msi_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_msi_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b7fa0)
Location: drivers/vfio/pci/vfio_pci_config.c:1092
Inline: False
```
**Symbols:**

```
ffffffff818b7fa0-ffffffff818b8030: vfio_msi_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_msi_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189baf0)
Location: drivers/vfio/pci/vfio_pci_config.c:1092
Inline: False
```
**Symbols:**

```
ffffffff8189baf0-ffffffff8189bb86: vfio_msi_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_msi_config_read(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192fc30)
Location: drivers/vfio/pci/vfio_pci_config.c:1092
Inline: False
```
**Symbols:**

```
ffffffff8192fc30-ffffffff8192fcc6: vfio_msi_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_msi_config_read(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a86640)
Location: drivers/vfio/pci/vfio_pci_config.c:1128
Inline: False
```
**Symbols:**

```
ffffffff81a86640-ffffffff81a866ee: vfio_msi_config_read (STB_LOCAL)
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
int vfio_msi_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000aba750)
Location: drivers/vfio/pci/vfio_pci_config.c:1055
Inline: False
```
**Symbols:**

```
c000000000aba750-c000000000aba81c: vfio_msi_config_read (STB_LOCAL)
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
int vfio_msi_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81784110)
Location: drivers/vfio/pci/vfio_pci_config.c:1055
Inline: False
```
**Symbols:**

```
ffffffff81784110-ffffffff81784197: vfio_msi_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_msi_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817ceee0)
Location: drivers/vfio/pci/vfio_pci_config.c:1055
Inline: False
```
**Symbols:**

```
ffffffff817ceee0-ffffffff817cef67: vfio_msi_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_msi_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e9180)
Location: drivers/vfio/pci/vfio_pci_config.c:1055
Inline: False
```
**Symbols:**

```
ffffffff817e9180-ffffffff817e9207: vfio_msi_config_read (STB_LOCAL)
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
