# Function: <code>queue_iova</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81629ff0)
Location: drivers/iommu/iova.c:541
Inline: False
```
**Symbols:**

```
ffffffff81629ff0-ffffffff8162a117: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81664d00)
Location: drivers/iommu/iova.c:541
Inline: False
```
**Symbols:**

```
ffffffff81664d00-ffffffff81664e32: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81683300)
Location: drivers/iommu/iova.c:550
Inline: False
```
**Symbols:**

```
ffffffff81683300-ffffffff81683432: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ba8c0)
Location: drivers/iommu/iova.c:549
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816ba8c0-ffffffff816ba9e4: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dd700)
Location: drivers/iommu/iova.c:549
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816dd700-ffffffff816dd831: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817944e0)
Location: drivers/iommu/iova.c:549
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/intel/iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff817944e0-ffffffff8179460d: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0f70)
Location: drivers/iommu/iova.c:564
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
**Symbols:**

```
ffffffff817c0f70-ffffffff817c109b: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a43c0)
Location: drivers/iommu/iova.c:629
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
**Symbols:**

```
ffffffff817a43c0-ffffffff817a44eb: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8182dae0)
Location: drivers/iommu/iova.c:631
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
**Symbols:**

```
ffffffff8182dae0-ffffffff8182dcce: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196add0)
Location: drivers/iommu/dma-iommu.c:170
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad52b0)
Location: drivers/iommu/dma-iommu.c:173
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b23a60)
Location: drivers/iommu/dma-iommu.c:174
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void queue_iova(struct iommu_dma_cookie *cookie, long unsigned int pfn, long unsigned int pages, struct list_head *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b79500)
Location: drivers/iommu/dma-iommu.c:200
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
**Symbols:**

```
ffffffff81b79500-ffffffff81b79654: queue_iova (STB_LOCAL)
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
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cdb38)
Location: drivers/iommu/iova.c:549
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
**Symbols:**

```
ffff8000108cdb38-ffff8000108cdce0: queue_iova (STB_GLOBAL)
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
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a3150)
Location: drivers/iommu/iova.c:549
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816a3150-ffffffff816a3281: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680b40)
Location: drivers/iommu/iova.c:549
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff81680b40-ffffffff81680c71: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d13c0)
Location: drivers/iommu/iova.c:549
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816d13c0-ffffffff816d14f1: queue_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void queue_iova(struct iova_domain *iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ebcd0)
Location: drivers/iommu/iova.c:549
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816ebcd0-ffffffff816ebe01: queue_iova (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
