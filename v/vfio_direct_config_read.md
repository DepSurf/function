# Function: <code>vfio_direct_config_read</code>

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
int vfio_direct_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817da0f0)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: True
```
**Symbols:**

```
ffffffff817da0f0-ffffffff817da196: vfio_direct_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfio_direct_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a9c40)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: True
```
**Symbols:**

```
ffffffff818a9c40-ffffffff818a9d68: vfio_direct_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfio_direct_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b8b70)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: True
```
**Symbols:**

```
ffffffff818b8b70-ffffffff818b8c98: vfio_direct_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfio_direct_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189c030)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: True
```
**Symbols:**

```
ffffffff8189c030-ffffffff8189c169: vfio_direct_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfio_direct_config_read(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81930280)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: True
```
**Symbols:**

```
ffffffff81930280-ffffffff819303b9: vfio_direct_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_direct_config_read(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a86d30)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: False
```
**Symbols:**

```
ffffffff81a86d30-ffffffff81a86e7d: vfio_direct_config_read (STB_LOCAL)
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
int vfio_direct_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abbd20)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: True
```
**Symbols:**

```
c000000000abbd20-c000000000abbe48: vfio_direct_config_read (STB_LOCAL)
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
int vfio_direct_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817841a0)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: True
```
**Symbols:**

```
ffffffff817841a0-ffffffff81784246: vfio_direct_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfio_direct_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cef70)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: True
```
**Symbols:**

```
ffffffff817cef70-ffffffff817cf016: vfio_direct_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfio_direct_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e9210)
Location: drivers/vfio/pci/vfio_pci_config.c:247
Inline: True
```
**Symbols:**

```
ffffffff817e9210-ffffffff817e92b6: vfio_direct_config_read (STB_LOCAL)
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
