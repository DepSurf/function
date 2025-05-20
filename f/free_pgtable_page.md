# Function: <code>free_pgtable_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153656b)
Location: drivers/iommu/intel-iommu.c:656
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158f06a)
Location: drivers/iommu/intel-iommu.c:663
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bcb8a)
Location: drivers/iommu/intel-iommu.c:664
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d23da)
Location: drivers/iommu/intel-iommu.c:669
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816391ba)
Location: drivers/iommu/intel-iommu.c:642
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81674420)
Location: drivers/iommu/intel-iommu.c:644
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692a50)
Location: drivers/iommu/intel-iommu.c:520
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff81691040-ffffffff81691052: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c6875)
Location: drivers/iommu/intel-iommu.c:514
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff816c8f60-ffffffff816c8f72: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e97e5)
Location: drivers/iommu/intel-iommu.c:525
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff816ebf20-ffffffff816ebf32: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a2912)
Location: drivers/iommu/intel/iommu.c:522
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:intel_unmap
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:iova_entry_free
  - drivers/iommu/intel/iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff817a3c00-ffffffff817a3c12: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817af1d3)
Location: drivers/iommu/intel/iommu.c:512
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff817b0b40-ffffffff817b0b52: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791bb3)
Location: drivers/iommu/intel/iommu.c:521
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff817935d0-ffffffff817935e2: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff818195a6)
Location: drivers/iommu/intel/iommu.c:510
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff8181b3f0-ffffffff8181b402: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195d8fb)
Location: drivers/iommu/intel/iommu.c:410
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff8195c160-ffffffff8195c17a: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_pgtable_page(u64 *pt);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81abb1ab)
Location: drivers/iommu/amd/io_pgtable_v2.c:108
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac52c0)
Location: drivers/iommu/intel/iommu.c:385
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff81ac3c40-ffffffff81ac3c5a: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_pgtable_page(u64 *pt);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07bc5)
Location: drivers/iommu/amd/io_pgtable_v2.c:102
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b11d30)
Location: drivers/iommu/intel/iommu.c:385
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff81b10630-ffffffff81b1064a: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_pgtable_page(u64 *pt);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bbf5)
Location: drivers/iommu/amd/io_pgtable_v2.c:102
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b675af)
Location: drivers/iommu/intel/iommu.c:248
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff81b650d0-ffffffff81b650ea: free_pgtable_page (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816af2c5)
Location: drivers/iommu/intel-iommu.c:525
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff816b1850-ffffffff816b1862: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168cc15)
Location: drivers/iommu/intel-iommu.c:525
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff8168f350-ffffffff8168f362: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dd4a5)
Location: drivers/iommu/intel-iommu.c:525
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff816dfbe0-ffffffff816dfbf2: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_pgtable_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f79a5)
Location: drivers/iommu/intel-iommu.c:525
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
**Symbols:**

```
ffffffff816fa1f0-ffffffff816fa202: free_pgtable_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 *pt</code>
</li>
<li>
<b>Param removed. </b>
<code>void *vaddr</code>
</li>
</ul>
</details>
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
