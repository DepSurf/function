# Function: <code>pfn_to_mfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f6076e)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten.c:xen_load_gdt
```
```
In arch/x86/xen/setup.c (ffffffff8107ca38)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff81f623b1)
Location: arch/x86/include/asm/xen/page.h:102
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
In arch/x86/xen/suspend.c (ffffffff8102420d)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024716)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
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
In arch/x86/xen/pmu.c (ffffffff810265b6)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/smp.c (ffffffff8102ba16)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff814c5641)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_foreach_grant
```
```
In drivers/xen/balloon.c (ffffffff814c65c4)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff814c7541)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81fa4a3b)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff814cab81)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc390)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fa4cc1)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff814d0dc9)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff814d27e9)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d4265)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/xlate_mmu.c (ffffffff814d6f3a)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff040)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81574cd0)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff815fb1f5)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8107ca38-ffffffff8107ca5c: pfn_to_mfn.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f883da)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten.c:xen_load_gdt
```
```
In arch/x86/xen/setup.c (ffffffff81f88e3c)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff8101ddd0)
Location: arch/x86/include/asm/xen/page.h:102
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
In arch/x86/xen/suspend.c (ffffffff810234cd)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810240e0)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
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
In arch/x86/xen/pmu.c (ffffffff81025a58)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/smp.c (ffffffff8102ab91)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff81516a12)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff81516ce5)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81517dc5)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81fd0ffd)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151bac0)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151cf0f)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fd1288)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81521a31)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8152355e)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815250b9)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81527cd9)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154f76f)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff815cc720)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8165b136)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8107e4a9-ffffffff8107e4c9: pfn_to_mfn.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81fc37c8)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten.c:xen_load_gdt
```
```
In arch/x86/xen/setup.c (ffffffff81fc4230)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff8101e4c0)
Location: arch/x86/include/asm/xen/page.h:102
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
In arch/x86/xen/suspend.c (ffffffff81023c1f)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024810)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
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
In arch/x86/xen/pmu.c (ffffffff81026178)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/smp.c (ffffffff8102ad21)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff81542e3d)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff8154315f)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff815440b5)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8200e975)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81547f90)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815493df)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8200ec18)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8154df01)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8154fa33)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81551579)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff8155424a)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157bfef)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff815f92f1)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81688e46)
Location: arch/x86/include/asm/xen/page.h:102
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81082abc-ffffffff81082adc: pfn_to_mfn.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101a9d0)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/setup.c (ffffffff820a41c4)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101caf0)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101d06a)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101d99d)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
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
In arch/x86/xen/enlighten_pv.c (ffffffff820a5a1e)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810249f8)
Location: arch/x86/include/asm/xen/page.h:128
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
In arch/x86/xen/smp_pv.c (ffffffff810296f4)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff81556ced)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff81556fe9)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81557f2d)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff820f0425)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155ba90)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d356)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff820f06e2)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81562391)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81564145)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81565d3a)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81568dd6)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8159025b)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff8160d468)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8169e695)
Location: arch/x86/include/asm/xen/page.h:128
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101bd39-ffffffff8101bd57: pfn_to_mfn.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b2d0)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/setup.c (ffffffff826aa8a2)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101d7a0)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101dd3a)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101e60b)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
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
In arch/x86/xen/enlighten_pv.c (ffffffff826ac0e5)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025598)
Location: arch/x86/include/asm/xen/page.h:138
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
In arch/x86/xen/smp_pv.c (ffffffff81029913)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff815bad1d)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff815baff5)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff815bc0a8)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff826f9c2f)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bfdb0)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1656)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff826f9eec)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815c6691)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff815c8295)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815c9eda)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff815ccf86)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4d5b)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81675ce8)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81709835)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101ca35-ffffffff8101ca53: pfn_to_mfn.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101bc96)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_pfn_pte_fn
```
```
In arch/x86/xen/setup.c (ffffffff826d3a0b)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101e118)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e790)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101ec90)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
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
In arch/x86/xen/enlighten_pv.c (ffffffff826d5217)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810262f2)
Location: arch/x86/include/asm/xen/page.h:138
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
In arch/x86/xen/smp_pv.c (ffffffff8102a458)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff815f32c9)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff815f3708)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff815f45a8)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82723fc3)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f8486)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f9775)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8272426b)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815fef42)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81600b05)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602afa)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff816056a9)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162debd)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff816b13e3)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8174831f)
Location: arch/x86/include/asm/xen/page.h:138
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101d444-ffffffff8101d462: pfn_to_mfn.part.1 (STB_LOCAL)
ffffffff81020620-ffffffff81020680: pfn_to_mfn.part.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b956)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff82889aab)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101d998)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e03f)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101e540)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/enlighten_pv.c (ffffffff8288b1f7)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025ea2)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/smp_pv.c (ffffffff8102aafc)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/grant-table.c (ffffffff8160e329)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160e764)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8160f408)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828dc19c)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff816137e6)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614835)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828dc444)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8161a012)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8161bbd5)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161d81a)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81620789)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c0cd)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff816d1723)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8176c3df)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101ccd4-ffffffff8101ccf2: pfn_to_mfn.part.1 (STB_LOCAL)
ffffffff81020090-ffffffff810200f0: pfn_to_mfn.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d496)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a0fa7)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101f539)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101fbcb)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810200af)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a263f)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027ba2)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/smp_pv.c (ffffffff8102c8b4)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8164203c)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816424ed)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81643203)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828f6a95)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff816475f6)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648511)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828f6d33)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8164ddcf)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8164f855)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650a4a)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
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
```
In drivers/xen/xlate_mmu.c (ffffffff81653d0c)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81680eb9)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff8170d1af)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817aa200)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101e814-ffffffff8101e832: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff81021bd0-ffffffff81021c30: pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101de36)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a4075)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101fe99)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102052b)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020a0f)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a56f3)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810284e2)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/smp_pv.c (ffffffff8102d184)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816645fc)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81664ab6)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff816657a3)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828ffaec)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81669a96)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166a9b1)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828ffd8a)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff816702af)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81671e05)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81672fca)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
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
```
In drivers/xen/xlate_mmu.c (ffffffff816762ac)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3569)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff817314af)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817cdc60)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101f194-ffffffff8101f1b2: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff81022510-ffffffff81022570: pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810201f6)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff82cca358)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff810225b9)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022b8b)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023360)
Location: arch/x86/include/asm/xen/page.h:164
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
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbbc7)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a3f2)
Location: arch/x86/include/asm/xen/page.h:164
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
In arch/x86/xen/smp_pv.c (ffffffff8102f134)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81713b9c)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8171467f)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81714e63)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82d16e95)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171984d)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171abb3)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82d17086)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff817207af)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/biomerge.c (ffffffff817224d5)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723719)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
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
```
In drivers/xen/xlate_mmu.c (ffffffff81726e1c)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755acf)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff817edae3)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81898172)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81021794-ffffffff810217b2: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff81024910-ffffffff81024970: pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020c26)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff82fb61c6)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81022c99)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102315b)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023930)
Location: arch/x86/include/asm/xen/page.h:164
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
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7a27)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102add2)
Location: arch/x86/include/asm/xen/page.h:164
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
In arch/x86/xen/smp_pv.c (ffffffff8102ff44)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81730a8c)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81730d5f)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81731a53)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83004a85)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81736a9b)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737d23)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83004c66)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8173d70f)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/biomerge.c (ffffffff8173f135)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8174040e)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
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
```
```
In drivers/xen/xlate_mmu.c (ffffffff8174337c)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770d3f)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81802413)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff818a6537)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81bd2a02-ffffffff81bd2a20: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff81025090-ffffffff810250f0: pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022fc6)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff831c0b6d)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81024ee9)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102546b)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810266cd)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c1f8a)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102b9c2)
Location: arch/x86/include/asm/xen/page.h:164
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
In arch/x86/xen/smp_pv.c (ffffffff81030a41)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff8171461c)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817148eb)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81715542)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8320f53a)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a555)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b749)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8320f7c8)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff817212df)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81722b86)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723ec3)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
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
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726d7c)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817547d9)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff817e893e)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81889947)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81bc4ba0-ffffffff81bc4bbe: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff81027250-ffffffff810272ae: pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81027136)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff832a13ff)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8102935e)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102997b)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102abdd)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a29d8)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81030122)
Location: arch/x86/include/asm/xen/page.h:164
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
In arch/x86/xen/smp_pv.c (ffffffff81035918)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff817913bc)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81791738)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81792552)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff832f84e1)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798c85)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a1f8)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff832f876f)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff817a00ff)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff817a19d6)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2d4f)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
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
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a5dac)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d7e9c)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81874e3a)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8191c454)
Location: arch/x86/include/asm/xen/page.h:164
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81c97285-ffffffff81c972a3: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff8102b700-ffffffff8102b75e: pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8102b2fb)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff83450421)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8102dc84)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102e227)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102f634)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83451dba)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81035771)
Location: arch/x86/include/asm/xen/page.h:156
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
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b76b)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff818c9aba)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff818ca220)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff818cad97)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff834b0d1f)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1ee6)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3d9f)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff834b1000)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff818d9be2)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff818dba10)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dcfd8)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
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
```
```
In drivers/xen/xlate_mmu.c (ffffffff818dfd2d)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (0)
Location: arch/x86/include/asm/xen/page.h:156
Inline: False
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff819160d9)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff819bd0e8)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81a719e2)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81e46749-ffffffff81e4676f: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff810301b0-ffffffff81030230: pfn_to_mfn.part.0 (STB_LOCAL)
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
In arch/x86/xen/mmu.c (ffffffff8103201b)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff83e6c728)
Location: arch/x86/include/asm/xen/page.h:156
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
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81035044)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81035647)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810369c4)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6ea3e)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d3e1)
Location: arch/x86/include/asm/xen/page.h:156
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
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043f3b)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a1a9ca)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a1ade0)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81a1bf59)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83eeabf8)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a24059)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a25fa9)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83eeb1ff)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a2c6d2)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81a2eb50)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30418)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
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
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a3419d)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a35219)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a717f9)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81b327a8)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c07722)
Location: arch/x86/include/asm/xen/page.h:156
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
In arch/x86/xen/mmu.c (ffffffff8103201b)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff8368d24b)
Location: arch/x86/include/asm/xen/page.h:156
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
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81034fc4)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810355c7)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81036934)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f3be)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d2b1)
Location: arch/x86/include/asm/xen/page.h:156
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
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104404f)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a63b7a)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a63f90)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81a650f9)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff837105e8)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d593)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6f559)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83710c0f)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a75e82)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81a78310)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79c28)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
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
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7dbbd)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a7ec29)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc0a9)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81b85cc0)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c6ce2b)
Location: arch/x86/include/asm/xen/page.h:156
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
In arch/x86/xen/mmu.c (ffffffff8103830b)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/setup.c (ffffffff838bce0b)
Location: arch/x86/include/asm/xen/page.h:156
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
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8103b1c4)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103b7c7)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8103cb34)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bee2e)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81043771)
Location: arch/x86/include/asm/xen/page.h:156
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
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a57e)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81ab63ba)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81ab67d0)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81ab7959)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83943f68)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf603)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac1659)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8394458f)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81ac8072)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81aca630)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc096)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
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
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad005d)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad1199)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0edc6)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd9bd0)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81d2177d)
Location: arch/x86/include/asm/xen/page.h:156
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
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101de36)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff8289209b)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101fff9)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102068b)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020b6f)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/enlighten_pv.c (ffffffff828936fc)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028642)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/smp_pv.c (ffffffff8102d2e4)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8162a46c)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162a926)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8162b343)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828e7309)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f906)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630821)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828e75a7)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8163636f)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81637ec5)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81638cba)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
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
```
In drivers/xen/xlate_mmu.c (ffffffff8163bf9c)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81668fc9)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff816f738f)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81792880)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101f2f4-ffffffff8101f312: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff81022670-ffffffff810226d0: pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ddf6)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a5075)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101fe59)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810204eb)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810209cf)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a66f3)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810284a2)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/smp_pv.c (ffffffff8102d144)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8165843c)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816588f6)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff816595e3)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828fae0f)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d8d6)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165e7f1)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828fb0ad)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff816640ef)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81665c45)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81666e0a)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
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
```
In drivers/xen/xlate_mmu.c (ffffffff8166a0ec)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816973a9)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff8172496f)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817c2ae0)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101f154-ffffffff8101f172: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff810224d0-ffffffff81022530: pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e046)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a5049)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff810200a9)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102073b)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020c1f)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a66c7)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029132)
Location: arch/x86/include/asm/xen/page.h:165
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
In arch/x86/xen/smp_pv.c (ffffffff8102df34)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81672a3c)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672f0a)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff81673be3)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82900b40)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677ee6)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81679331)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82900dde)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8167e6af)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff816801f5)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816813ba)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
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
```
In drivers/xen/xlate_mmu.c (ffffffff816846ac)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1959)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/block/xen-blkfront.c (ffffffff81740637)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817dcda0)
Location: arch/x86/include/asm/xen/page.h:165
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8101f3a4-ffffffff8101f3c2: pfn_to_mfn.part.0 (STB_LOCAL)
ffffffff810227e0-ffffffff81022840: pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
