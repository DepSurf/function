# Function: <code>lookup_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106d310)
Location: arch/x86/mm/pageattr.c:367
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
Direct callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
  - arch/x86/xen/enlighten.c:set_aliased_prot
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/mm/mmio-mod.c:pre
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff8106d310-ffffffff8106d33f: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e1f1)
Location: arch/x86/mm/pageattr.c:373
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
Direct callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
  - arch/x86/xen/enlighten.c:set_aliased_prot
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff8106d120-ffffffff8106d14f: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071e73)
Location: arch/x86/mm/pageattr.c:373
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
Direct callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
  - arch/x86/xen/enlighten.c:set_aliased_prot
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff81070d60-ffffffff81070d8f: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107152f)
Location: arch/x86/mm/pageattr.c:402
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
Direct callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff810704b0-ffffffff810704df: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81076ca7)
Location: arch/x86/mm/pageattr.c:402
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush_range
Direct callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff81075a20-ffffffff81075a4f: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107979e)
Location: arch/x86/mm/pageattr.c:422
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush_range
Direct callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff810784c0-ffffffff810784ef: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107ecde)
Location: arch/x86/mm/pageattr.c:606
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
Direct callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff8107ec70-ffffffff8107ec9f: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084ae9)
Location: arch/x86/mm/pageattr.c:615
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
Direct callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff81082540-ffffffff8108256a: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810857e9)
Location: arch/x86/mm/pageattr.c:615
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
Direct callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff81083600-ffffffff8108362a: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f5b2)
Location: arch/x86/mm/pat/set_memory.c:624
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/mmio-mod.c:print_pte
  - arch/x86/mm/pti.c:pti_setup_vsyscall
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
```
**Symbols:**

```
ffffffff8108d270-ffffffff8108d2a5: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f372)
Location: arch/x86/mm/pat/set_memory.c:624
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/mmio-mod.c:print_pte
  - arch/x86/mm/pti.c:pti_setup_vsyscall
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
```
**Symbols:**

```
ffffffff8108d140-ffffffff8108d175: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ff02)
Location: arch/x86/mm/pat/set_memory.c:632
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
```
**Symbols:**

```
ffffffff8108dcf0-ffffffff8108dd25: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f9e3)
Location: arch/x86/mm/pat/set_memory.c:632
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_unprotect
  - mm/kfence/core.c:kfence_protect
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
```
**Symbols:**

```
ffffffff81ca1280-ffffffff81ca129c: lookup_address.cold (STB_LOCAL)
ffffffff8109d5a0-ffffffff8109d5f3: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3813)
Location: arch/x86/mm/pat/set_memory.c:635
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_protect_page
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
```
**Symbols:**

```
ffffffff81e5088c-ffffffff81e508a8: lookup_address.cold (STB_LOCAL)
ffffffff810b0e80-ffffffff810b0ee0: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce413)
Location: arch/x86/mm/pat/set_memory.c:710
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_protect_page
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
```
**Symbols:**

```
ffffffff82054d0a-ffffffff82054d26: lookup_address.cold (STB_LOCAL)
ffffffff810cb5a0-ffffffff810cb600: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d19d3)
Location: arch/x86/mm/pat/set_memory.c:711
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_init_pool
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
```
**Symbols:**

```
ffffffff820d32e0-ffffffff820d32fc: lookup_address.cold (STB_LOCAL)
ffffffff810cebc0-ffffffff810cec20: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810da103)
Location: arch/x86/mm/pat/set_memory.c:711
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
Direct callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
```
**Symbols:**

```
ffffffff821ae14e-ffffffff821ae16a: lookup_address.cold (STB_LOCAL)
ffffffff810d72a0-ffffffff810d7300: lookup_address (STB_GLOBAL)
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
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810847e9)
Location: arch/x86/mm/pageattr.c:615
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
Direct callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff81082600-ffffffff8108262a: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810733e9)
Location: arch/x86/mm/pageattr.c:615
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff810713b0-ffffffff810713da: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084799)
Location: arch/x86/mm/pageattr.c:615
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
Direct callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff810825b0-ffffffff810825da: lookup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
pte_t *lookup_address(long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810868e9)
Location: arch/x86/mm/pageattr.c:615
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
  - arch/x86/mm/pageattr.c:cpa_flush
Direct callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
**Symbols:**

```
ffffffff810846d0-ffffffff810846fa: lookup_address (STB_GLOBAL)
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
