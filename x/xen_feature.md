# Function: <code>xen_feature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff8102420d)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024d8c)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
```
```
In arch/x86/xen/pmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102b7a5)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff814c668f)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff814d27d0)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff810234cd)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810240e0)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
```
```
In arch/x86/xen/pmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102ab00)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81523504)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff81023c1f)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024810)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
```
```
In arch/x86/xen/pmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102ac90)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/grant-table.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8154f9dd)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/pmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/suspend_pv.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff8101d99d)
Location: include/xen/features.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155c3f4)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/biomerge.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/xen/features.h:18
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/xen/features.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/irq.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/time.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/setup.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/pmu.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/suspend_pv.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff8101e60b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/manage.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c0704)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: include/xen/features.h:19
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ae26)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff8101b655)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
  - arch/x86/xen/mmu.c:xen_remap_domain_mfn_array
  - arch/x86/xen/mmu.c:xen_remap_domain_gfn_range
  - arch/x86/xen/mmu.c:remap_area_pfn_pte_fn
```
```
In arch/x86/xen/time.c (ffffffff826d2dcd)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff826d3574)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
```
In arch/x86/xen/setup.c (ffffffff826d3a0b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101e118)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e790)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101ec90)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d55aa)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810262f2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:m2p
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
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a26f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff815f3355)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
```
```
In drivers/xen/balloon.c (ffffffff815f4091)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff815f45a2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82723fb7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f841a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff827240f4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82724262)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815fee8f)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81600ade)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602acf)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff816056a7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162dde2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff816b122c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81748319)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff8273c6a0)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b5f6)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff8101b8c5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
```
```
In arch/x86/xen/time.c (ffffffff8288914d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82889498)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
```
In arch/x86/xen/setup.c (ffffffff82889aab)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101d998)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e03f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101e540)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b62e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025ea2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_batched_set_pte
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a8bf)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff8160e3b5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160ef41)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff8160f402)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828dc190)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8161377a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff828dc2cd)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828dc43b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81619f5f)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8161bbae)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161d7ef)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
  - drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous
```
```
In drivers/xen/xlate_mmu.c (ffffffff81620787)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164bff2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff816d156c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8176c3d9)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff828f66bb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d122)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff8101d405)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
```
```
In arch/x86/xen/time.c (ffffffff828a03fb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a081b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_need_lapic
```
```
In arch/x86/xen/setup.c (ffffffff828a0fa7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101f539)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101fbcb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810200af)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2a6b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027ba2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
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
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a5314)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff816420c5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81642d23)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff816431fd)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828f6a89)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81647594)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff828f6bb3)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828f6d2a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8164dd2f)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff8164f838)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650a1f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff81653d0a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81680de4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff8170cffc)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817aa1fa)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff829120fb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101daa2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff8101dda5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
```
```
In arch/x86/xen/time.c (ffffffff828a34eb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a390b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_need_lapic
```
```
In arch/x86/xen/setup.c (ffffffff828a4075)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101fe99)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102052b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020a0f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5b2a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810284e2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a83a4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff81664685)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816652cc)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff8166579d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828ffae0)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81669a34)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff828ffc0a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828ffd81)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8167020f)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81671de8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81672f9f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff816762aa)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3494)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff817312fc)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817cdc5a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff8291be94)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101fecf)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff810202e5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/time.c (ffffffff82cc9807)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82cc9c2e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_need_lapic
```
```
In arch/x86/xen/setup.c (ffffffff82cca358)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff810225b9)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022b8b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023360)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_top_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbe17)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a3f2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
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
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ef67)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff81713c25)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81714b39)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:increase_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff81714e5d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82d16e89)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff817197b8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff82d16fb3)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82d171ee)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8172072b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/biomerge.c (ffffffff817224b8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817236ef)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726e1a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817559e4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff817edac0)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8189816c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff82d31bf4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8102096f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff81020d15)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/time.c (ffffffff82fb5658)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82fb5a9c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_need_lapic
```
```
In arch/x86/xen/setup.c (ffffffff82fb61c6)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81022c99)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102315b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023930)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_top_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7c5f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102add2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fd77)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff81730b15)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81731799)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:increase_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff81731a4d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83004a79)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81736a06)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff83004b7f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83004dce)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8173d68b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/biomerge.c (ffffffff8173f118)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817403a5)
Location: include/xen/features.h:19
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
In drivers/xen/xlate_mmu.c (ffffffff8174337a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81743982)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770c54)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff818023f0)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff818a6531)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff83020c09)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81022d0f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff810230b5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/time.c (ffffffff831bfe96)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff831c02a7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_need_lapic
```
```
In arch/x86/xen/setup.c (ffffffff831c0b6d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81024ee9)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102546b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81026a65)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
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
In arch/x86/xen/enlighten_pv.c (ffffffff831c239a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102b9c2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff81030884)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff817146a5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817151a8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff8171553c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8320f52e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a4f3)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8320f634)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8320f7bf)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8172123f)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81722b5c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723e5a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726d7a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81727372)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754704)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff817e87f4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81889941)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff8322bdd7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff832a024f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff81027225)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/time.c (ffffffff832a05ae)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff832a0a91)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_need_lapic
```
```
In arch/x86/xen/setup.c (ffffffff832a13ff)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8102935e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102997b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102af85)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
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
In arch/x86/xen/enlighten_pv.c (ffffffff832a29d8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81030122)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103573b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff81791445)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/features.c (ffffffff817914df)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/balloon.c (ffffffff817921b8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff8179254c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff832f84d5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798c22)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff832f85db)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff832f8766)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff817a005f)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff817a19ac)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2ce6)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a5daa)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff817a63f2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d7dc7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81874d6e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8191c44e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff833165fc)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8344f0cd)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff8102b3e5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/time.c (ffffffff8344f4b9)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8344fa4c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
```
In arch/x86/xen/setup.c (ffffffff83450421)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8102dc84)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102e227)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff8102f815)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
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
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83451dba)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81035771)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b569)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff818c9b55)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/features.c (ffffffff818c9c14)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/balloon.c (ffffffff818ca440)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff818cad91)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff834b0d13)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1e3d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff834b0e38)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff834b0ff7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff818d9b27)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff818db9e6)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dcf66)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/xen/xlate_mmu.c (ffffffff818dfd2b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff818e0518)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/xen/grant-dma-ops.c (0)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81915fed)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff819bd032)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81a719dc)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff834d0fa5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
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
In arch/x86/xen/enlighten.c (ffffffff83e6aa0f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff81032115)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/time.c (ffffffff83e6af27)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81033585)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
```
In arch/x86/xen/setup.c (ffffffff83e6c728)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81035044)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81035647)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff81036bd5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
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
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6ea3e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d3e1)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043d39)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff81a1aa85)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/features.c (ffffffff81a1ab54)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/balloon.c (ffffffff81a1b980)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff81a1bf53)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83eeab1a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23fad)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff83eead45)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83eeaf16)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a2c617)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81a2eb26)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a303a6)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a3419b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81a34a48)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a35210)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a7170d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81b326f2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c0771c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff83f1518b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
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
In arch/x86/xen/enlighten.c (ffffffff8368b39f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff81032115)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/time.c (ffffffff8368b9c7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81033523)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
```
In arch/x86/xen/setup.c (ffffffff8368d24b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81034fc4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810355c7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff81036b45)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
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
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f3be)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d2b1)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043e4d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In drivers/xen/grant-table.c (ffffffff81a63c35)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/features.c (ffffffff81a63d04)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/balloon.c (ffffffff81a64b20)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff81a650f3)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8371050a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d4e4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff83710735)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83710926)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a75dc7)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81a782e6)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79bb6)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7dbbb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81a7e458)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a7ec20)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abbfbd)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81b85bae)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c6ce25)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff8373b90b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
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
In arch/x86/xen/enlighten.c (ffffffff838baf5f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff81038405)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/time.c (ffffffff838bb587)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81039823)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
```
In arch/x86/xen/setup.c (ffffffff838bce0b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8103b1c4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103b7c7)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff8103cd45)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
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
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bee2e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81043771)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a37c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In drivers/xen/grant-table.c (ffffffff81ab6475)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/features.c (ffffffff81ab6544)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/balloon.c (ffffffff81ab7380)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff81ab7953)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83943e8a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf554)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff839440b5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff839442a6)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81ac7fb7)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81aca606)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc023)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad005b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81ad09c8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad1190)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0ecda)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd9abe)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81d21777)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff839702ab)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/xen/enlighten.c (ffff80001143acbc)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_early_init
```
```
In drivers/xen/grant-table.c (ffff80001082e3b8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/xenbus/xenbus_client.c (ffff8000108346f4)
Location: include/xen/features.h:19
Inline: True
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101daa2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff8101dda5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
```
```
In arch/x86/xen/time.c (ffffffff828914eb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8289192c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_need_lapic
```
```
In arch/x86/xen/setup.c (ffffffff8289209b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101fff9)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102068b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020b6f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893b33)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028642)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff828963b4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff8162a4f5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162aeed)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/manage.c (ffffffff8162b33d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828e72fd)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f8a4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff828e7427)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828e759e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff816362cf)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81637ea8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81638c8f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff8163bf9a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81668ef4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff816f71dc)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8179287a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff82900b98)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101da62)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff8101dd65)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
```
```
In arch/x86/xen/time.c (ffffffff828a44eb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a490b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_need_lapic
```
```
In arch/x86/xen/setup.c (ffffffff828a5075)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101fe59)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810204eb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810209cf)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6b2a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810284a2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a93a4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff816584c5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8165910c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff816595dd)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828fae03)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d874)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff828faf2d)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828fb0a4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8166404f)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff81665c28)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81666ddf)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff8166a0ea)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816972d4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff817247bc)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817c2ada)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff8291619f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101dcb2)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/mmu.c (ffffffff8101dfb5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_unmap_domain_gfn_range
```
```
In arch/x86/xen/time.c (ffffffff828a44cb)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a48df)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_need_lapic
```
```
In arch/x86/xen/setup.c (ffffffff828a5049)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff810200a9)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102073b)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020c1f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6afe)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029132)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:pin_pagetable_pfn
  - arch/x86/xen/mmu_pv.c:xen_do_pin
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a93b4)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In drivers/xen/grant-table.c (ffffffff81672ac5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_suspend
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_foreach_grant
  - drivers/xen/grant-table.c:gnttab_foreach_grant_in_range
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8167370c)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/manage.c (ffffffff81673bdd)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82900b34)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677e84)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff82900c5e)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_ring_ops_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82900dd5)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8167e60f)
Location: include/xen/features.h:19
Inline: True
```
```
In drivers/xen/biomerge.c (ffffffff816801d8)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/biomerge.c:xen_biovec_phys_mergeable
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8168138f)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/xen/xlate_mmu.c (ffffffff816846aa)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_for_each_gfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1884)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/block/xen-blkfront.c (ffffffff81740470)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817dcd9a)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In arch/x86/pci/xen.c (ffffffff8291cef6)
Location: include/xen/features.h:19
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:pci_xen_hvm_init
```
</details>
</li>
</ul>

## Differences
