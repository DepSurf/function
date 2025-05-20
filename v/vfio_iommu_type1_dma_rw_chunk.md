# Function: <code>vfio_iommu_type1_dma_rw_chunk</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu *iommu, dma_addr_t user_iova, void *data, size_t count, bool write, size_t *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a01b0)
Location: drivers/vfio/vfio_iommu_type1.c:2854
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw
```
**Symbols:**

```
ffffffff818a01b0-ffffffff818a0406: vfio_iommu_type1_dma_rw_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu *iommu, dma_addr_t user_iova, void *data, size_t count, bool write, size_t *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818aeb90)
Location: drivers/vfio/vfio_iommu_type1.c:2910
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw
```
**Symbols:**

```
ffffffff818aeb90-ffffffff818aeded: vfio_iommu_type1_dma_rw_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu *iommu, dma_addr_t user_iova, void *data, size_t count, bool write, size_t *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818912a0)
Location: drivers/vfio/vfio_iommu_type1.c:3135
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw
```
**Symbols:**

```
ffffffff818912a0-ffffffff818914f2: vfio_iommu_type1_dma_rw_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu *iommu, dma_addr_t user_iova, void *data, size_t count, bool write, size_t *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:3137
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw
```
**Symbols:**

```
ffffffff81924d70-ffffffff81924fd1: vfio_iommu_type1_dma_rw_chunk (STB_LOCAL)
ffffffff81d1195e-ffffffff81d11a09: vfio_iommu_type1_dma_rw_chunk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_dma_rw_chunk(struct vfio_iommu *iommu, dma_addr_t user_iova, void *data, size_t count, bool write, size_t *copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:3129
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw
```
**Symbols:**

```
ffffffff81a7a980-ffffffff81a7abe5: vfio_iommu_type1_dma_rw_chunk (STB_LOCAL)
ffffffff81edc5dc-ffffffff81edc677: vfio_iommu_type1_dma_rw_chunk.cold (STB_LOCAL)
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
