# Function: <code>apply_to_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c03f0)
Location: mm/memory.c:1879
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffff811c03f0-ffffffff811c0847: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dbe00)
Location: mm/memory.c:1942
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffff811dbe00-ffffffff811dc23b: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811eb910)
Location: mm/memory.c:1942
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffff811eb910-ffffffff811ebd47: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f6840)
Location: mm/memory.c:2148
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffff811f6840-ffffffff811f6c4e: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120ecd0)
Location: mm/memory.c:2265
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffff8120ecd0-ffffffff8120f17b: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81230aa0)
Location: mm/memory.c:2307
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffff81230aa0-ffffffff81230ef5: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81242e30)
Location: mm/memory.c:2043
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffff81242e30-ffffffff81243282: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2097
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - mm/vmalloc.c:alloc_vm_area
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
```
**Symbols:**

```
ffffffff81257480-ffffffff81257498: apply_to_page_range.cold (STB_LOCAL)
ffffffff81254cb0-ffffffff812550b4: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81263220)
Location: mm/memory.c:2102
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - mm/vmalloc.c:alloc_vm_area
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
```
**Symbols:**

```
ffffffff81263220-ffffffff8126362d: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81293860)
Location: mm/memory.c:2364
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - mm/vmalloc.c:alloc_vm_area
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
  - drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array
```
**Symbols:**

```
ffffffff81293860-ffffffff81293876: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e150)
Location: mm/memory.c:2543
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - mm/vmalloc.c:vmap_pfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
  - drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array
```
**Symbols:**

```
ffffffff8129e150-ffffffff8129e166: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a3880)
Location: mm/memory.c:2604
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - mm/vmalloc.c:vmap_pfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
  - drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array
```
**Symbols:**

```
ffffffff812a3880-ffffffff812a3896: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e4b80)
Location: mm/memory.c:2699
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - mm/vmalloc.c:vmap_pfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
  - drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array
```
**Symbols:**

```
ffffffff812e4b80-ffffffff812e4b96: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81346490)
Location: mm/memory.c:2792
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - mm/vmalloc.c:vmap_pfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
  - drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array
```
**Symbols:**

```
ffffffff81346490-ffffffff813464b8: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813be850)
Location: mm/memory.c:2763
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - mm/vmalloc.c:vmap_pfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
  - drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array
```
**Symbols:**

```
ffffffff813be850-ffffffff813be878: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f34a0)
Location: mm/memory.c:2763
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - mm/vmalloc.c:vmap_pfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
  - drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array
```
**Symbols:**

```
ffffffff813f34a0-ffffffff813f34c8: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141e190)
Location: mm/memory.c:2786
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - mm/vmalloc.c:vmap_pfn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
  - drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array
```
**Symbols:**

```
ffffffff8141e190-ffffffff8141e1b8: apply_to_page_range (STB_GLOBAL)
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
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fac90)
Location: mm/memory.c:2102
Inline: False
Direct callers:
  - arch/arm64/kernel/efi.c:efi_set_mapping_permissions
  - arch/arm64/mm/pageattr.c:set_direct_map_default_noflush
  - arch/arm64/mm/pageattr.c:set_direct_map_invalid_noflush
  - arch/arm64/mm/pageattr.c:__change_memory_common
  - mm/vmalloc.c:alloc_vm_area
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
```
**Symbols:**

```
ffff8000102fac90-ffff8000102fafb4: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05181ac)
Location: mm/memory.c:2102
Inline: False
Direct callers:
  - arch/arm/kernel/efi.c:efi_set_mapping_permissions
  - arch/arm/mm/dma-mapping.c:__dma_remap
  - arch/arm/mm/pageattr.c:change_memory_common
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
c05181ac-c05183f4: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c55a0)
Location: mm/memory.c:2102
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
c0000000003c55a0-c0000000003c5b94: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020a606)
Location: mm/memory.c:2102
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffe00020a606-ffffffe00020a842: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b870)
Location: mm/memory.c:2102
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - mm/vmalloc.c:alloc_vm_area
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
```
**Symbols:**

```
ffffffff8125b870-ffffffff8125bc7d: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124de30)
Location: mm/memory.c:2102
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffff8124de30-ffffffff8124e23b: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81259610)
Location: mm/memory.c:2102
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - mm/vmalloc.c:alloc_vm_area
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
```
**Symbols:**

```
ffffffff81259610-ffffffff81259a1d: apply_to_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int apply_to_page_range(struct mm_struct *mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81269010)
Location: mm/memory.c:2102
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - mm/vmalloc.c:alloc_vm_area
  - drivers/xen/xlate_mmu.c:xen_remap_vma_range
```
**Symbols:**

```
ffffffff81269010-ffffffff8126941a: apply_to_page_range (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
