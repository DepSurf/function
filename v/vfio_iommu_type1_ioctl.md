# Function: <code>vfio_iommu_type1_ioctl</code>

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
long int vfio_iommu_type1_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d58e0)
Location: drivers/vfio/vfio_iommu_type1.c:2214
Inline: True
```
**Symbols:**

```
ffffffff817d58e0-ffffffff817d5ddf: vfio_iommu_type1_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int vfio_iommu_type1_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a16a0)
Location: drivers/vfio/vfio_iommu_type1.c:2593
Inline: True
```
**Symbols:**

```
ffffffff818a16a0-ffffffff818a1ce1: vfio_iommu_type1_ioctl.part.0 (STB_LOCAL)
ffffffff818a1cf0-ffffffff818a1d97: vfio_iommu_type1_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_iommu_type1_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818b0630)
Location: drivers/vfio/vfio_iommu_type1.c:2865
Inline: False
```
**Symbols:**

```
ffffffff818b0630-ffffffff818b07b1: vfio_iommu_type1_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfio_iommu_type1_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81894040)
Location: drivers/vfio/vfio_iommu_type1.c:3090
Inline: False
```
**Symbols:**

```
ffffffff81894040-ffffffff818941c1: vfio_iommu_type1_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int vfio_iommu_type1_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81927bd0)
Location: drivers/vfio/vfio_iommu_type1.c:3092
Inline: False
```
**Symbols:**

```
ffffffff81927bd0-ffffffff81927d51: vfio_iommu_type1_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int vfio_iommu_type1_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7e430)
Location: drivers/vfio/vfio_iommu_type1.c:3084
Inline: False
```
**Symbols:**

```
ffffffff81a7e430-ffffffff81a7e5dd: vfio_iommu_type1_ioctl (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
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
long int vfio_iommu_type1_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177f990)
Location: drivers/vfio/vfio_iommu_type1.c:2214
Inline: True
```
**Symbols:**

```
ffffffff8177f990-ffffffff8177fe8f: vfio_iommu_type1_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int vfio_iommu_type1_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817ca760)
Location: drivers/vfio/vfio_iommu_type1.c:2214
Inline: True
```
**Symbols:**

```
ffffffff817ca760-ffffffff817cac5f: vfio_iommu_type1_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int vfio_iommu_type1_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e4a00)
Location: drivers/vfio/vfio_iommu_type1.c:2214
Inline: True
```
**Symbols:**

```
ffffffff817e4a00-ffffffff817e4eff: vfio_iommu_type1_ioctl (STB_LOCAL)
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
