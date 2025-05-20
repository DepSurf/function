# Function: <code>vfio_default_config_write</code>

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
int vfio_default_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff817da3b0-ffffffff817da51a: vfio_default_config_write (STB_LOCAL)
ffffffff817dbf22-ffffffff817dbf2e: vfio_default_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff818a8260-ffffffff818a83c9: vfio_default_config_write (STB_LOCAL)
ffffffff818aa247-ffffffff818aa253: vfio_default_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff818b7090-ffffffff818b71f9: vfio_default_config_write (STB_LOCAL)
ffffffff81c1a2c6-ffffffff81c1a2d2: vfio_default_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff8189a560-ffffffff8189a6c5: vfio_default_config_write (STB_LOCAL)
ffffffff81c0c159-ffffffff81c0c165: vfio_default_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_write(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff8192e2b0-ffffffff8192e415: vfio_default_config_write (STB_LOCAL)
ffffffff81d12531-ffffffff81d1253d: vfio_default_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_write(struct vfio_pci_core_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81a84ac0-ffffffff81a84c5f: vfio_default_config_write (STB_LOCAL)
ffffffff81edd259-ffffffff81edd265: vfio_default_config_write.cold (STB_LOCAL)
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
int vfio_default_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000aba950)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
c000000000aba950-c000000000abab28: vfio_default_config_write (STB_LOCAL)
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
int vfio_default_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81784460-ffffffff817845ca: vfio_default_config_write (STB_LOCAL)
ffffffff81785fd2-ffffffff81785fde: vfio_default_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff817cf230-ffffffff817cf39a: vfio_default_config_write (STB_LOCAL)
ffffffff817d0da2-ffffffff817d0dae: vfio_default_config_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_default_config_write(struct vfio_pci_device *vdev, int pos, int count, struct perm_bits *perm, int offset, __le32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:200
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff817e94d0-ffffffff817e963a: vfio_default_config_write (STB_LOCAL)
ffffffff817eb042-ffffffff817eb04e: vfio_default_config_write.cold (STB_LOCAL)
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
