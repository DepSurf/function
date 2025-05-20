# Function: <code>clflush_cache_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106c1b0)
Location: arch/x86/mm/pageattr.c:130
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel_irq_remapping.c:modify_irte
```
**Symbols:**

```
ffffffff8106c1b0-ffffffff8106c1f0: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106c020)
Location: arch/x86/mm/pageattr.c:134
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel_irq_remapping.c:modify_irte
```
**Symbols:**

```
ffffffff8106c020-ffffffff8106c057: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106fc40)
Location: arch/x86/mm/pageattr.c:134
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel_irq_remapping.c:modify_irte
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8106fc40-ffffffff8106fc77: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f360)
Location: arch/x86/mm/pageattr.c:135
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel_irq_remapping.c:modify_irte
```
**Symbols:**

```
ffffffff8106f360-ffffffff8106f397: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81074700)
Location: arch/x86/mm/pageattr.c:135
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush_range
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel_irq_remapping.c:modify_irte
```
**Symbols:**

```
ffffffff81074700-ffffffff81074739: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81077170)
Location: arch/x86/mm/pageattr.c:153
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush_range
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
**Symbols:**

```
ffffffff81077170-ffffffff810771a8: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107d8d5)
Location: arch/x86/mm/pageattr.c:298
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff8107d8b0-ffffffff8107d8c6: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810811d5)
Location: arch/x86/mm/pageattr.c:299
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff810811b0-ffffffff810811c6: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082275)
Location: arch/x86/mm/pageattr.c:299
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81082230-ffffffff81082267: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bd35)
Location: arch/x86/mm/pat/set_memory.c:306
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
**Symbols:**

```
ffffffff8108bcf0-ffffffff8108bd27: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bd55)
Location: arch/x86/mm/pat/set_memory.c:306
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
**Symbols:**

```
ffffffff8108bd10-ffffffff8108bd47: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c925)
Location: arch/x86/mm/pat/set_memory.c:314
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff8108c960-ffffffff8108c997: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c185)
Location: arch/x86/mm/pat/set_memory.c:314
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff8109c1c0-ffffffff8109c1f7: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810af915)
Location: arch/x86/mm/pat/set_memory.c:317
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff810af8c0-ffffffff810af903: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810c9f15)
Location: arch/x86/mm/pat/set_memory.c:335
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
  - drivers/iommu/intel/iommu.c:iommu_context_addr
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
**Symbols:**

```
ffffffff810c9eb0-ffffffff810c9ef3: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd565)
Location: arch/x86/mm/pat/set_memory.c:336
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
  - drivers/iommu/intel/iommu.c:iommu_context_addr
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
**Symbols:**

```
ffffffff810cd500-ffffffff810cd543: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d5c45)
Location: arch/x86/mm/pat/set_memory.c:336
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
**Symbols:**

```
ffffffff810d5be0-ffffffff810d5c23: clflush_cache_range (STB_GLOBAL)
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
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081275)
Location: arch/x86/mm/pageattr.c:299
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81081230-ffffffff81081267: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810701c5)
Location: arch/x86/mm/pageattr.c:299
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81070180-ffffffff810701b7: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081225)
Location: arch/x86/mm/pageattr.c:299
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff810811e0-ffffffff81081217: clflush_cache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clflush_cache_range(void *vaddr, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083345)
Location: arch/x86/mm/pageattr.c:299
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:arch_invalidate_pmem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-iommu.c:iommu_context_addr
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81083300-ffffffff81083337: clflush_cache_range (STB_GLOBAL)
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
