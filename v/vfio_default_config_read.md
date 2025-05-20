# Function: <code>vfio_default_config_read</code>

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
int vfio_default_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
ffffffff817d9f70-ffffffff817da05a: vfio_default_config_read (STB_LOCAL)
ffffffff817dbf16-ffffffff817dbf22: vfio_default_config_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
ffffffff818a8130-ffffffff818a821a: vfio_default_config_read (STB_LOCAL)
ffffffff818aa23b-ffffffff818aa247: vfio_default_config_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
ffffffff818b6f60-ffffffff818b704a: vfio_default_config_read (STB_LOCAL)
ffffffff81c1a2ba-ffffffff81c1a2c6: vfio_default_config_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
ffffffff8189a430-ffffffff8189a51e: vfio_default_config_read (STB_LOCAL)
ffffffff81c0c14d-ffffffff81c0c159: vfio_default_config_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_read(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
ffffffff8192e420-ffffffff8192e517: vfio_default_config_read (STB_LOCAL)
ffffffff81d1253d-ffffffff81d12568: vfio_default_config_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_read(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
ffffffff81a84c60-ffffffff81a84d67: vfio_default_config_read (STB_LOCAL)
ffffffff81edd265-ffffffff81edd292: vfio_default_config_read.cold (STB_LOCAL)
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
int vfio_default_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000aba5f0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
c000000000aba5f0-c000000000aba750: vfio_default_config_read (STB_LOCAL)
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
int vfio_default_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
ffffffff81784020-ffffffff8178410a: vfio_default_config_read (STB_LOCAL)
ffffffff81785fc6-ffffffff81785fd2: vfio_default_config_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
ffffffff817cedf0-ffffffff817ceeda: vfio_default_config_read (STB_LOCAL)
ffffffff817d0d96-ffffffff817d0da2: vfio_default_config_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_read(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:174
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read
```
**Symbols:**

```
ffffffff817e9090-ffffffff817e917a: vfio_default_config_read (STB_LOCAL)
ffffffff817eb036-ffffffff817eb042: vfio_default_config_read.cold (STB_LOCAL)
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
