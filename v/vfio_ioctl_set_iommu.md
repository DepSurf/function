# Function: <code>vfio_ioctl_set_iommu</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0a0a)
Location: drivers/vfio/vfio.c:1102
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfio_ioctl_set_iommu(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189aec0)
Location: drivers/vfio/vfio.c:1117
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8189aec0-ffffffff8189b0c5: vfio_ioctl_set_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_ioctl_set_iommu(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9ad0)
Location: drivers/vfio/vfio.c:1118
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff818a9ad0-ffffffff818a9cd5: vfio_ioctl_set_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfio_ioctl_set_iommu(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188ce70)
Location: drivers/vfio/vfio.c:1012
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff8188ce70-ffffffff8188d075: vfio_ioctl_set_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int vfio_ioctl_set_iommu(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:1098
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff819204f0-ffffffff81920706: vfio_ioctl_set_iommu (STB_LOCAL)
ffffffff81d1165d-ffffffff81d11678: vfio_ioctl_set_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int vfio_ioctl_set_iommu(struct vfio_container *container, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:783
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
**Symbols:**

```
ffffffff81a775a0-ffffffff81a777b7: vfio_ioctl_set_iommu (STB_LOCAL)
ffffffff81edc41c-ffffffff81edc431: vfio_ioctl_set_iommu.cold (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000ab02f0)
Location: drivers/vfio/vfio.c:1102
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177aaba)
Location: drivers/vfio/vfio.c:1102
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c588a)
Location: drivers/vfio/vfio.c:1102
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817dfb2a)
Location: drivers/vfio/vfio.c:1102
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_unl_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
