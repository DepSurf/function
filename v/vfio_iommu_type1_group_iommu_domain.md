# Function: <code>vfio_iommu_type1_group_iommu_domain</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *vfio_iommu_type1_group_iommu_domain(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818acda0)
Location: drivers/vfio/vfio_iommu_type1.c:2995
Inline: True
```
**Symbols:**

```
ffffffff818acda0-ffffffff818ace3d: vfio_iommu_type1_group_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *vfio_iommu_type1_group_iommu_domain(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188fd70)
Location: drivers/vfio/vfio_iommu_type1.c:3221
Inline: True
```
**Symbols:**

```
ffffffff8188fd70-ffffffff8188fe0d: vfio_iommu_type1_group_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *vfio_iommu_type1_group_iommu_domain(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819238f0)
Location: drivers/vfio/vfio_iommu_type1.c:3223
Inline: True
```
**Symbols:**

```
ffffffff819238f0-ffffffff8192398d: vfio_iommu_type1_group_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *vfio_iommu_type1_group_iommu_domain(void *iommu_data, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79360)
Location: drivers/vfio/vfio_iommu_type1.c:3215
Inline: True
```
**Symbols:**

```
ffffffff81a79360-ffffffff81a79419: vfio_iommu_type1_group_iommu_domain (STB_LOCAL)
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
