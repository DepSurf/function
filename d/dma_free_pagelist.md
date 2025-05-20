# Function: <code>dma_free_pagelist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81536540)
Location: drivers/iommu/intel-iommu.c:1276
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:flush_unmaps
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff81536540-ffffffff81536590: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158aad0)
Location: drivers/iommu/intel-iommu.c:1283
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff8158aad0-ffffffff8158ab16: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b8140)
Location: drivers/iommu/intel-iommu.c:1297
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff815b8140-ffffffff815b817c: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cd6c0)
Location: drivers/iommu/intel-iommu.c:1302
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff815cd6c0-ffffffff815cd6fd: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816344e0)
Location: drivers/iommu/intel-iommu.c:1278
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:iova_entry_free
```
**Symbols:**

```
ffffffff816344e0-ffffffff8163451d: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8166fa00)
Location: drivers/iommu/intel-iommu.c:1280
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:iova_entry_free
```
**Symbols:**

```
ffffffff8166fa00-ffffffff8166fa3c: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e270)
Location: drivers/iommu/intel-iommu.c:1156
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:iova_entry_free
```
**Symbols:**

```
ffffffff8168e270-ffffffff8168e2ac: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c58e0)
Location: drivers/iommu/intel-iommu.c:1161
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
  - drivers/iommu/intel-iommu.c:iova_entry_free
```
**Symbols:**

```
ffffffff816c58e0-ffffffff816c591f: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e8910)
Location: drivers/iommu/intel-iommu.c:1172
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
  - drivers/iommu/intel-iommu.c:iova_entry_free
```
**Symbols:**

```
ffffffff816e8910-ffffffff816e894f: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a28fd)
Location: drivers/iommu/intel/iommu.c:1188
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:intel_unmap
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:iova_entry_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817af1c0)
Location: drivers/iommu/intel/iommu.c:1278
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791ba0)
Location: drivers/iommu/intel/iommu.c:1297
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81819593)
Location: drivers/iommu/intel/iommu.c:1301
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ae3f0)
Location: drivers/iommu/intel-iommu.c:1172
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
  - drivers/iommu/intel-iommu.c:iova_entry_free
```
**Symbols:**

```
ffffffff816ae3f0-ffffffff816ae42f: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168bd50)
Location: drivers/iommu/intel-iommu.c:1172
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
  - drivers/iommu/intel-iommu.c:iova_entry_free
```
**Symbols:**

```
ffffffff8168bd50-ffffffff8168bd8f: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dc5d0)
Location: drivers/iommu/intel-iommu.c:1172
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
  - drivers/iommu/intel-iommu.c:iova_entry_free
```
**Symbols:**

```
ffffffff816dc5d0-ffffffff816dc60f: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_free_pagelist(struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f6c10)
Location: drivers/iommu/intel-iommu.c:1172
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
  - drivers/iommu/intel-iommu.c:iova_entry_free
```
**Symbols:**

```
ffffffff816f6c10-ffffffff816f6c4f: dma_free_pagelist (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
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
