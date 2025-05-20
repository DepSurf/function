# Function: <code>__pfn_to_mfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bb30)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
```
```
In arch/x86/xen/setup.c (ffffffff8107c9fb)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff81f623c7)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_do_pin
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
```
```
In arch/x86/xen/suspend.c (ffffffff81023f46)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024750)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
```
```
In arch/x86/xen/pmu.c (ffffffff810266a2)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/smp.c (ffffffff8102baa1)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff814c5641)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant
```
```
In drivers/xen/balloon.c (ffffffff814c65c4)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff814c7541)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81fa4a3b)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff814cab81)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc390)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816f4246)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff814d0dc9)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff814d27e9)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d4265)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xlate_mmu.c (ffffffff814d6f3a)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff040)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xen_pv_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_pv_console_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81574cd0)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff815fb1f5)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101bb30-ffffffff8101bb6d: __pfn_to_mfn (STB_LOCAL)
ffffffff8107c9fb-ffffffff8107ca38: __pfn_to_mfn (STB_LOCAL)
ffffffff816f4246-ffffffff816f4283: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bd03)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
```
```
In arch/x86/xen/setup.c (ffffffff8107e46b)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101de03)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_do_pin
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
```
```
In arch/x86/xen/suspend.c (ffffffff8102354c)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810241eb)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/pmu.c (ffffffff81025b41)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/smp.c (ffffffff8102ab91)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff81516a12)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff81516ce5)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81517dc5)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81fd0ffd)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151bac0)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151d207)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff817592a2)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81521a31)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8152355e)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815250b9)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81527cd9)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154f76f)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff815cc720)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8165b136)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101af70-ffffffff8101afad: __pfn_to_mfn (STB_LOCAL)
ffffffff8107e46b-ffffffff8107e4a9: __pfn_to_mfn (STB_LOCAL)
ffffffff817592a2-ffffffff817592e0: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c513)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
```
```
In arch/x86/xen/setup.c (ffffffff81082a7e)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101e4f3)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_do_pin
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
```
```
In arch/x86/xen/suspend.c (ffffffff81023c84)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102491b)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/pmu.c (ffffffff81026273)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/smp.c (ffffffff8102ad21)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff81542e86)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff8154315f)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff815440b5)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8200e975)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81547f90)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81549757)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8178581c)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8154df01)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8154fa33)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81551579)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff8155424a)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157bfef)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff815f92f1)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81688e46)
Location: arch/x86/include/asm/xen/page.h:85
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101b6a0-ffffffff8101b6dd: __pfn_to_mfn (STB_LOCAL)
ffffffff81082a7e-ffffffff81082abc: __pfn_to_mfn (STB_LOCAL)
ffffffff8178581c-ffffffff8178585a: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101aa0a)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/setup.c (ffffffff8101bcfc)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff8101cbf2)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101d0d8)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101da9e)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f3d2)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024a22)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff810297b3)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff81556d36)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff81556fe9)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81557f2d)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff820f0425)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155ba90)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d63e)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560d48)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81562391)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81564145)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81565d3a)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81568dd6)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8159025b)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff8160d468)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8169e695)
Location: arch/x86/include/asm/xen/page.h:105
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101bcfc-ffffffff8101bd39: __pfn_to_mfn (STB_LOCAL)
ffffffff8101ea40-ffffffff8101ea7d: __pfn_to_mfn (STB_LOCAL)
ffffffff81560d48-ffffffff81560d85: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b30a)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/setup.c (ffffffff8101c9f8)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff8101d8a2)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101dda8)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101e6dd)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101fe84)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810255c2)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff810299d5)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff815bad69)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff815baff5)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff815bc0a8)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff826f9c2f)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bfdb0)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1951)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c5028)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815c6691)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff815c8295)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815c9eda)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff815ccf86)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4d5b)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81675ce8)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81709835)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101c9f8-ffffffff8101ca35: __pfn_to_mfn (STB_LOCAL)
ffffffff8101f620-ffffffff8101f65d: __pfn_to_mfn (STB_LOCAL)
ffffffff815c5028-ffffffff815c5065: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101bcde)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_pfn_pte_fn
```
```
In arch/x86/xen/setup.c (ffffffff8101d40c)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff8101e191)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e7a2)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101f2af)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d5223)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102630c)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a414)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff815f32c9)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff815f3708)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff815f45a8)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82723fc3)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f8486)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f99d9)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fd69e)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815fef42)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81600b05)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602afa)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff816056a9)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162debd)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff816b13e3)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8174831f)
Location: arch/x86/include/asm/xen/page.h:115
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101d40c-ffffffff8101d444: __pfn_to_mfn (STB_LOCAL)
ffffffff815fd69e-ffffffff815fd6d6: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b981)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff8101cc9c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff8101da11)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e051)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101eb8e)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b203)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025ebc)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_batched_set_pte
  - arch/x86/xen/mmu_pv.c:xen_batched_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a8f4)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff8160e329)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160e764)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8160f408)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828dc19c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff816137e6)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614a94)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8161877e)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8161a012)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8161bbd5)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161d81a)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81620789)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c0cd)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff816d1723)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8176c3df)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101cc9c-ffffffff8101ccd4: __pfn_to_mfn (STB_LOCAL)
ffffffff8161877e-ffffffff816187b6: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d4c1)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff8101e7dc)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff8101f5b3)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101fc27)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810206ee)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a264b)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027bbc)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c741)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8164203c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816424ed)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81643203)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828f6a95)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff816475f6)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648774)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164c43f)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8164ddcf)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8164f855)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650a4a)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff81653d0c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81680eb9)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff8170d1af)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817aa200)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101e7dc-ffffffff8101e814: __pfn_to_mfn (STB_LOCAL)
ffffffff8164c43f-ffffffff8164c477: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101de61)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff8101f15c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff8101ff13)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020587)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102104e)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a56ff)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810284fc)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d011)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816645fc)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81664ab6)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff816657a3)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828ffaec)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81669a96)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166ac14)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166e8cf)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff816702af)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81671e05)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81672fca)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff816762ac)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3569)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff817314af)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817cdc60)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101f15c-ffffffff8101f194: __pfn_to_mfn (STB_LOCAL)
ffffffff8166e8cf-ffffffff8166e907: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020221)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff8102175c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff81022633)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022bed)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023842)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_top_mfn_init
  - arch/x86/xen/p2m.c:p2m_top_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81024b4c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a40f)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ef98)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81713b9c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8171467f)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81714e63)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82d16e95)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171984d)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171ae64)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171ec1c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff817207af)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/biomerge.c (ffffffff817224d5)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723719)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726e1c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755acf)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff817edae3)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81898172)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8102175c-ffffffff81021794: __pfn_to_mfn (STB_LOCAL)
ffffffff8171ec1c-ffffffff8171ec54: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020c51)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff81bd29ca)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff81022d13)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810231bd)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023e12)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_top_mfn_init
  - arch/x86/xen/p2m.c:p2m_top_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810252cc)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102adef)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fda8)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81730a8c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81730d5f)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81731a53)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83004a85)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81736a9b)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737fd4)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81c05618)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8173d70f)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/biomerge.c (ffffffff8173f135)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8174040e)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff8174337c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770d3f)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81802413)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff818a6537)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81bd29ca-ffffffff81bd2a02: __pfn_to_mfn (STB_LOCAL)
ffffffff81c05618-ffffffff81c05650: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022ff1)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff81bc4b68)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff81024f65)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810254cd)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81026af9)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102744d)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102b9df)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff810309c5)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff8171461c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817148eb)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81715542)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8320f53a)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a555)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b884)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81bf7292)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff817212df)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81722b86)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723ec3)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726d7c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817547d9)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff817e893e)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81889947)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81bc4b68-ffffffff81bc4ba0: __pfn_to_mfn (STB_LOCAL)
ffffffff81bf7292-ffffffff81bf72ca: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81027161)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff81c9724d)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff81029405)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810299dd)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102b019)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102ba6d)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103013f)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff810358a3)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff817913bc)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/balloon.c (ffffffff81791738)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81792552)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff832f84e1)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798c85)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a4b4)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81cf6191)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff817a00ff)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff817a19d6)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2d4f)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a5dac)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d7e9c)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81874e3a)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8191c454)
Location: arch/x86/include/asm/xen/page.h:141
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81c9724d-ffffffff81c97285: __pfn_to_mfn (STB_LOCAL)
ffffffff81cf6191-ffffffff81cf61c9: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8102b337)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff81e466ff)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff8102dd50)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102e2a9)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff8102f8b3)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81030314)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103579c)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b6c7)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff818c9aba)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/balloon.c (ffffffff818ca220)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff818cad97)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff834b0d1f)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1ee6)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3d9f)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ebe260)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff818d9be2)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff818dba10)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dcfd8)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/xen/xlate_mmu.c (ffffffff818dfd2d)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (0)
Location: arch/x86/include/asm/xen/page.h:133
Inline: False
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff819160d9)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff819bd0e8)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81a719e2)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81e466ff-ffffffff81e46749: __pfn_to_mfn (STB_LOCAL)
ffffffff81ebe260-ffffffff81ebe2aa: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81032057)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff83e6c72a)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8103504d)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810356c9)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff81036c73)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6eade)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d40c)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043e97)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a1a9ca)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/balloon.c (ffffffff81a1ade0)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81a1bf59)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83eeabf8)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a24059)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a25fa9)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83eeb1ff)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a2c6d2)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81a2eb50)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30418)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a3419d)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a35219)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a717f9)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81b327a8)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c07722)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81032057)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff8368d24d)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81034fcd)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81035649)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff81036be3)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f45e)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d2dc)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043fab)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a63b7a)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/balloon.c (ffffffff81a63f90)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81a650f9)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff837105e8)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d593)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6f559)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83710c0f)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a75e82)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81a78310)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79c28)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7dbbd)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a7ec29)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc0a9)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81b85cc0)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c6ce2b)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81038347)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff838bce0d)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8103b1cd)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103b849)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff8103cde3)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838beece)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8104379c)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a4da)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81ab63ba)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/balloon.c (ffffffff81ab67d0)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81ab7959)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83943f68)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf603)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac1659)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8394458f)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81ac8072)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81aca630)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc096)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad005d)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad1199)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0edc6)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd9bd0)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81d2177d)
Location: arch/x86/include/asm/xen/page.h:133
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/xen/p2m.c (ffff8000100f03c0)
Location: arch/arm/xen/p2m.c:63
Inline: False
Direct callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffff8000100f03c0-ffff8000100f0510: __pfn_to_mfn (STB_GLOBAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101de61)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff8101f2bc)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff81020073)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810206e7)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810211ae)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893708)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102865c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d171)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8162a46c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162a926)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8162b343)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828e7309)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f906)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630a84)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816348e5)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8163636f)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81637ec5)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81638cba)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff8163bf9c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81668fc9)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff816f738f)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81792880)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101f2bc-ffffffff8101f2f4: __pfn_to_mfn (STB_LOCAL)
ffffffff816348e5-ffffffff8163491d: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101de21)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff8101f11c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff8101fed3)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020547)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102100e)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a66ff)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810284bc)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cfd1)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8165843c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816588f6)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff816595e3)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828fae0f)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d8d6)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165ea54)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166270f)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff816640ef)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81665c45)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81666e0a)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff8166a0ec)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816973a9)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff8172496f)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817c2ae0)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101f11c-ffffffff8101f154: __pfn_to_mfn (STB_LOCAL)
ffffffff8166270f-ffffffff81662747: __pfn_to_mfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e071)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff8101f36c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/pmu.c (ffffffff81020123)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020797)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102125e)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a66d3)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102914c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ddc1)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81672a3c)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672f0a)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81673be3)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82900b40)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677ee6)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81679594)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167ccdf)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8167e6af)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff816801f5)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816813ba)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff816846ac)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1959)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81740637)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817dcda0)
Location: arch/x86/include/asm/xen/page.h:142
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101f36c-ffffffff8101f3a4: __pfn_to_mfn (STB_LOCAL)
ffffffff8167ccdf-ffffffff8167cd17: __pfn_to_mfn (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
