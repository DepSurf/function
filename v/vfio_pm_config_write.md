# Function: <code>vfio_pm_config_write</code>

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
int vfio_pm_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817daaa0)
Location: drivers/vfio/pci/vfio_pci_config.c:664
Inline: True
```
**Symbols:**

```
ffffffff817daaa0-ffffffff817daafc: vfio_pm_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfio_pm_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a8b10)
Location: drivers/vfio/pci/vfio_pci_config.c:690
Inline: True
```
**Symbols:**

```
ffffffff818a8b10-ffffffff818a8b6c: vfio_pm_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfio_pm_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b7a50)
Location: drivers/vfio/pci/vfio_pci_config.c:695
Inline: True
```
**Symbols:**

```
ffffffff818b7a50-ffffffff818b7aac: vfio_pm_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfio_pm_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189aef0)
Location: drivers/vfio/pci/vfio_pci_config.c:695
Inline: True
```
**Symbols:**

```
ffffffff8189aef0-ffffffff8189af4e: vfio_pm_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfio_pm_config_write(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192ef20)
Location: drivers/vfio/pci/vfio_pci_config.c:695
Inline: True
```
**Symbols:**

```
ffffffff8192ef20-ffffffff8192ef7e: vfio_pm_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfio_pm_config_write(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a857c0)
Location: drivers/vfio/pci/vfio_pci_config.c:714
Inline: True
```
**Symbols:**

```
ffffffff81a857c0-ffffffff81a85864: vfio_pm_config_write (STB_LOCAL)
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
int vfio_pm_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abc060)
Location: drivers/vfio/pci/vfio_pci_config.c:664
Inline: True
```
**Symbols:**

```
c000000000abc060-c000000000abc144: vfio_pm_config_write (STB_LOCAL)
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
int vfio_pm_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81784b50)
Location: drivers/vfio/pci/vfio_pci_config.c:664
Inline: True
```
**Symbols:**

```
ffffffff81784b50-ffffffff81784bac: vfio_pm_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfio_pm_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cf920)
Location: drivers/vfio/pci/vfio_pci_config.c:664
Inline: True
```
**Symbols:**

```
ffffffff817cf920-ffffffff817cf97c: vfio_pm_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfio_pm_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e9bc0)
Location: drivers/vfio/pci/vfio_pci_config.c:664
Inline: True
```
**Symbols:**

```
ffffffff817e9bc0-ffffffff817e9c1c: vfio_pm_config_write (STB_LOCAL)
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
