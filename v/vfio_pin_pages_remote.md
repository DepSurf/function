# Function: <code>vfio_pin_pages_remote</code>

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
long int vfio_pin_pages_remote(struct vfio_dma *dma, long unsigned int vaddr, long int npage, long unsigned int *pfn_base, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d4800)
Location: drivers/vfio/vfio_iommu_type1.c:397
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff817d4800-ffffffff817d4b54: vfio_pin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma *dma, long unsigned int vaddr, long int npage, long unsigned int *pfn_base, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f860)
Location: drivers/vfio/vfio_iommu_type1.c:487
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
**Symbols:**

```
ffffffff8189f860-ffffffff8189fc1c: vfio_pin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma *dma, long unsigned int vaddr, long int npage, long unsigned int *pfn_base, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818aeea0)
Location: drivers/vfio/vfio_iommu_type1.c:510
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
**Symbols:**

```
ffffffff818aeea0-ffffffff818af25c: vfio_pin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma *dma, long unsigned int vaddr, long int npage, long unsigned int *pfn_base, long unsigned int limit, struct vfio_batch *batch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:649
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
**Symbols:**

```
ffffffff81891d80-ffffffff8189219e: vfio_pin_pages_remote (STB_LOCAL)
ffffffff81c0be59-ffffffff81c0be89: vfio_pin_pages_remote.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma *dma, long unsigned int vaddr, long int npage, long unsigned int *pfn_base, long unsigned int limit, struct vfio_batch *batch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:650
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
**Symbols:**

```
ffffffff81925fa0-ffffffff819263e4: vfio_pin_pages_remote (STB_LOCAL)
ffffffff81d11bbf-ffffffff81d11c28: vfio_pin_pages_remote.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma *dma, long unsigned int vaddr, long int npage, long unsigned int *pfn_base, long unsigned int limit, struct vfio_batch *batch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:648
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
**Symbols:**

```
ffffffff81a7b1f0-ffffffff81a7b661: vfio_pin_pages_remote (STB_LOCAL)
ffffffff81edc6a7-ffffffff81edc745: vfio_pin_pages_remote.cold (STB_LOCAL)
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
long int vfio_pin_pages_remote(struct vfio_dma *dma, long unsigned int vaddr, long int npage, long unsigned int *pfn_base, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177e8b0)
Location: drivers/vfio/vfio_iommu_type1.c:397
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff8177e8b0-ffffffff8177ec04: vfio_pin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma *dma, long unsigned int vaddr, long int npage, long unsigned int *pfn_base, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c9680)
Location: drivers/vfio/vfio_iommu_type1.c:397
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff817c9680-ffffffff817c99d4: vfio_pin_pages_remote (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma *dma, long unsigned int vaddr, long int npage, long unsigned int *pfn_base, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e3920)
Location: drivers/vfio/vfio_iommu_type1.c:397
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff817e3920-ffffffff817e3c74: vfio_pin_pages_remote (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_batch *batch</code>
</li>
</ul>
</details>
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
