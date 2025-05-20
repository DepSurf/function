# Function: <code>vfio_sanity_check_pfn_list</code>

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
void vfio_sanity_check_pfn_list(struct vfio_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3470)
Location: drivers/vfio/vfio_iommu_type1.c:1885
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
**Symbols:**

```
ffffffff817d3470-ffffffff817d34b7: vfio_sanity_check_pfn_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_sanity_check_pfn_list(struct vfio_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189ddf0)
Location: drivers/vfio/vfio_iommu_type1.c:2245
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
**Symbols:**

```
ffffffff8189ddf0-ffffffff8189de3d: vfio_sanity_check_pfn_list (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void vfio_sanity_check_pfn_list(struct vfio_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d520)
Location: drivers/vfio/vfio_iommu_type1.c:1885
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
**Symbols:**

```
ffffffff8177d520-ffffffff8177d567: vfio_sanity_check_pfn_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void vfio_sanity_check_pfn_list(struct vfio_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c82f0)
Location: drivers/vfio/vfio_iommu_type1.c:1885
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
**Symbols:**

```
ffffffff817c82f0-ffffffff817c8337: vfio_sanity_check_pfn_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void vfio_sanity_check_pfn_list(struct vfio_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2590)
Location: drivers/vfio/vfio_iommu_type1.c:1885
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
**Symbols:**

```
ffffffff817e2590-ffffffff817e25d7: vfio_sanity_check_pfn_list (STB_LOCAL)
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
