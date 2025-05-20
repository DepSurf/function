# Function: <code>alloc_pgtable_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815357e0)
Location: drivers/iommu/intel-iommu.c:645
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815357e0-ffffffff8153583f: alloc_pgtable_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158d309)
Location: drivers/iommu/intel-iommu.c:652
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8158a040-ffffffff8158a099: alloc_pgtable_page (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff82015bc0)
Location: drivers/iommu/intel-iommu.c:653
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
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
In drivers/iommu/intel-iommu.c (ffffffff820f7882)
Location: drivers/iommu/intel-iommu.c:658
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
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
In drivers/iommu/intel-iommu.c (ffffffff82700f63)
Location: drivers/iommu/intel-iommu.c:631
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
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
In drivers/iommu/intel-iommu.c (ffffffff8272ac77)
Location: drivers/iommu/intel-iommu.c:633
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81690260)
Location: drivers/iommu/intel-iommu.c:509
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff81690260-ffffffff816902a2: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c8400)
Location: drivers/iommu/intel-iommu.c:503
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816c8400-ffffffff816c8442: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eb3b0)
Location: drivers/iommu/intel-iommu.c:514
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816eb3b0-ffffffff816eb3f2: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff82d1d85e)
Location: drivers/iommu/intel/iommu.c:511
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff817a3bb0-ffffffff817a3bf2: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8300b57a)
Location: drivers/iommu/intel/iommu.c:501
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff817b0af0-ffffffff817b0b32: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff83215f0f)
Location: drivers/iommu/intel/iommu.c:510
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff81793580-ffffffff817935c2: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181a387)
Location: drivers/iommu/intel/iommu.c:499
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff8181b3a0-ffffffff8181b3e2: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195bd69)
Location: drivers/iommu/intel/iommu.c:399
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_context_table
```
**Symbols:**

```
ffffffff8195c110-ffffffff8195c15e: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81abb107)
Location: drivers/iommu/amd/io_pgtable_v2.c:49
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac3585)
Location: drivers/iommu/intel/iommu.c:374
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
**Symbols:**

```
ffffffff81ac3be0-ffffffff81ac3c2e: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page(int nid, gfp_t gfp);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06c70)
Location: drivers/iommu/amd/amd_iommu.h:126
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07ad8)
Location: drivers/iommu/amd/amd_iommu.h:126
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f0a0)
Location: drivers/iommu/intel/iommu.c:374
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
**Symbols:**

```
ffffffff81b0f0a0-ffffffff81b0f153: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *alloc_pgtable_page(int nid, gfp_t gfp);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b57553)
Location: drivers/iommu/amd/amd_iommu.h:145
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ac46)
Location: drivers/iommu/amd/amd_iommu.h:145
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bb08)
Location: drivers/iommu/amd/amd_iommu.h:145
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b63990)
Location: drivers/iommu/intel/iommu.c:237
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
**Symbols:**

```
ffffffff81b63990-ffffffff81b63a43: alloc_pgtable_page (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b0ce0)
Location: drivers/iommu/intel-iommu.c:514
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816b0ce0-ffffffff816b0d22: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e7e0)
Location: drivers/iommu/intel-iommu.c:514
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff8168e7e0-ffffffff8168e822: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816df070)
Location: drivers/iommu/intel-iommu.c:514
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816df070-ffffffff816df0b2: alloc_pgtable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *alloc_pgtable_page(int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f9680)
Location: drivers/iommu/intel-iommu.c:514
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
**Symbols:**

```
ffffffff816f9680-ffffffff816f96c2: alloc_pgtable_page (STB_GLOBAL)
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
<b>Param removed. </b>
<code>int node</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
