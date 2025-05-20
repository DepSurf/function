# Function: <code>vfio_iommu_type1_dma_rw</code>

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
int vfio_iommu_type1_dma_rw(void *iommu_data, dma_addr_t user_iova, void *data, size_t count, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a0410)
Location: drivers/vfio/vfio_iommu_type1.c:2914
Inline: False
```
**Symbols:**

```
ffffffff818a0410-ffffffff818a04bf: vfio_iommu_type1_dma_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_iommu_type1_dma_rw(void *iommu_data, dma_addr_t user_iova, void *data, size_t count, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818aedf0)
Location: drivers/vfio/vfio_iommu_type1.c:2971
Inline: False
```
**Symbols:**

```
ffffffff818aedf0-ffffffff818aee9f: vfio_iommu_type1_dma_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_iommu_type1_dma_rw(void *iommu_data, dma_addr_t user_iova, void *data, size_t count, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81891500)
Location: drivers/vfio/vfio_iommu_type1.c:3197
Inline: False
```
**Symbols:**

```
ffffffff81891500-ffffffff818915af: vfio_iommu_type1_dma_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_iommu_type1_dma_rw(void *iommu_data, dma_addr_t user_iova, void *data, size_t count, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81924fe0)
Location: drivers/vfio/vfio_iommu_type1.c:3199
Inline: False
```
**Symbols:**

```
ffffffff81924fe0-ffffffff8192508f: vfio_iommu_type1_dma_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_iommu_type1_dma_rw(void *iommu_data, dma_addr_t user_iova, void *data, size_t count, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7abf0)
Location: drivers/vfio/vfio_iommu_type1.c:3191
Inline: False
```
**Symbols:**

```
ffffffff81a7abf0-ffffffff81a7acba: vfio_iommu_type1_dma_rw (STB_LOCAL)
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
