# Function: <code>virt_to_pfn</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff838bcddf)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8103b1a1)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff8103c000)
Location: arch/x86/include/asm/xen/page.h:298
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
In arch/x86/xen/enlighten_pv.c (ffffffff838bef7d)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810435a8)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a444)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/manage.c (ffffffff81ab7922)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83943e6b)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf535)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac150f)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83944283)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81ac7e97)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad0ed9)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0ecb5)
Location: arch/x86/include/asm/xen/page.h:298
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
