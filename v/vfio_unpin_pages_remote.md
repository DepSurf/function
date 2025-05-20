# Function: <code>vfio_unpin_pages_remote</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma *dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3990)
Location: drivers/vfio/vfio_iommu_type1.c:476
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff817d3990-ffffffff817d3a5b: vfio_unpin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma *dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e710)
Location: drivers/vfio/vfio_iommu_type1.c:566
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8189e710-ffffffff8189e836: vfio_unpin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma *dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad850)
Location: drivers/vfio/vfio_iommu_type1.c:589
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff818ad850-ffffffff818ad976: vfio_unpin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma *dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818908a0)
Location: drivers/vfio/vfio_iommu_type1.c:760
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff818908a0-ffffffff818909ce: vfio_unpin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma *dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81924380)
Location: drivers/vfio/vfio_iommu_type1.c:761
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff81924380-ffffffff819244ae: vfio_unpin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma *dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79c60)
Location: drivers/vfio/vfio_iommu_type1.c:759
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff81a79c60-ffffffff81a79da5: vfio_unpin_pages_remote (STB_LOCAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma *dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177da40)
Location: drivers/vfio/vfio_iommu_type1.c:476
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8177da40-ffffffff8177db0b: vfio_unpin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma *dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8810)
Location: drivers/vfio/vfio_iommu_type1.c:476
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff817c8810-ffffffff817c88db: vfio_unpin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int vfio_unpin_pages_remote(struct vfio_dma *dma, dma_addr_t iova, long unsigned int pfn, long int npage, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2ab0)
Location: drivers/vfio/vfio_iommu_type1.c:476
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff817e2ab0-ffffffff817e2b7b: vfio_unpin_pages_remote (STB_LOCAL)
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
