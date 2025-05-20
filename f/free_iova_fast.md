# Function: <code>free_iova_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580840)
Location: drivers/iommu/iova.c:443
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:__queue_flush
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81580840-ffffffff81580a26: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815ad690)
Location: drivers/iommu/iova.c:443
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:__queue_flush
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815ad690-ffffffff815ad896: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c32b0)
Location: drivers/iommu/iova.c:417
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815c32b0-ffffffff815c3504: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81629c30)
Location: drivers/iommu/iova.c:442
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81629c30-ffffffff81629e76: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81664940)
Location: drivers/iommu/iova.c:442
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81664940-ffffffff81664b86: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81682f30)
Location: drivers/iommu/iova.c:451
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_page
```
**Symbols:**

```
ffffffff81682f30-ffffffff81683185: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ba730)
Location: drivers/iommu/iova.c:450
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816ba730-ffffffff816ba75d: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dd570)
Location: drivers/iommu/iova.c:450
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816dd570-ffffffff816dd59d: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8179438d)
Location: drivers/iommu/iova.c:450
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_ring_free
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/intel/iommu.c:bounce_map_single
  - drivers/iommu/intel/iommu.c:intel_map_sg
  - drivers/iommu/intel/iommu.c:intel_unmap
  - drivers/iommu/intel/iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81794660-ffffffff817946c2: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0d70)
Location: drivers/iommu/iova.c:465
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/iova.c:fq_ring_free
```
**Symbols:**

```
ffffffff817c0d70-ffffffff817c0e07: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a3fd0)
Location: drivers/iommu/iova.c:531
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/iova.c:fq_ring_free
```
**Symbols:**

```
ffffffff817a3fd0-ffffffff817a4254: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8182d150)
Location: drivers/iommu/iova.c:532
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/iova.c:fq_ring_free
```
**Symbols:**

```
ffffffff8182d150-ffffffff8182d3cb: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8196e6f0)
Location: drivers/iommu/iova.c:482
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
**Symbols:**

```
ffffffff8196e6f0-ffffffff8196e96f: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81ad9060)
Location: drivers/iommu/iova.c:487
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
**Symbols:**

```
ffffffff81ad9060-ffffffff81ad9254: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b27120)
Location: drivers/iommu/iova.c:487
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
**Symbols:**

```
ffffffff81b27120-ffffffff81b273d3: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b7d730)
Location: drivers/iommu/iova.c:488
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free_locked
```
**Symbols:**

```
ffffffff81b7d730-ffffffff81b7d92d: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cd8e8)
Location: drivers/iommu/iova.c:450
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
**Symbols:**

```
ffff8000108cd8e8-ffff8000108cd940: free_iova_fast (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2fc0)
Location: drivers/iommu/iova.c:450
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816a2fc0-ffffffff816a2fed: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816809b0)
Location: drivers/iommu/iova.c:450
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816809b0-ffffffff816809dd: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d1230)
Location: drivers/iommu/iova.c:450
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816d1230-ffffffff816d125d: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_iova_fast(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ebb40)
Location: drivers/iommu/iova.c:450
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816ebb40-ffffffff816ebb6d: free_iova_fast (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
