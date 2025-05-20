# Function: <code>mfn_to_pfn_no_overrides</code>

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
In arch/x86/xen/setup.c (ffffffff81f61cc9)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff8101e810)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff81023f1e)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024edb)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102ba75)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc4a0)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816f4296)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d47d2)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff367)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_pv_console_init
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
In arch/x86/xen/setup.c (ffffffff81f88f96)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101dc30)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff810231bb)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102426b)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102ad83)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151d1e4)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff817592f3)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81526177)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154fdca)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff81fc438a)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101e320)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff8102390b)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102499b)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102af36)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81549734)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8178586d)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81552687)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157c97a)
Location: arch/x86/include/asm/xen/page.h:130
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff820a41f1)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101ce21)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101db6b)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810204f0)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029789)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d613)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560d98)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566e57)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590a3e)
Location: arch/x86/include/asm/xen/page.h:156
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff826aa8cf)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101dad1)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101e856)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810211e0)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810299a8)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1923)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c5078)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815cb007)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f571e)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff826d3a36)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e534)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101f1fb)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021cc0)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a3eb)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f99b3)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fd6e9)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81603864)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e4be)
Location: arch/x86/include/asm/xen/page.h:166
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff82889ad2)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101ddc2)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101eab4)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810214f0)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a8d4)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614a73)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816187c9)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161e978)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c6fe)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff828a0e7c)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101f960)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020614)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023060)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c721)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648753)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164c48a)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816513a7)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8168120e)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff828a3f48)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810202c0)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020f74)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810239a0)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cff1)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166abf3)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166e91a)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673787)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a38be)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff82cca4fe)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022910)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023768)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026180)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ef78)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171ae43)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171ec67)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723f5b)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755d3e)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff82fb636c)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022ee0)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023d38)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026890)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fd88)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737fb3)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81c05663)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817405bf)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770fae)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff831c0906)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81025200)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81026782)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4f25)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810309a5)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b863)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81bf72dd)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817241c1)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754a6e)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff832a1198)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81029710)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102ac92)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c97793)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff81035882)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81790f20)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a493)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81cf61dc)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a3047)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d812e)
Location: arch/x86/include/asm/xen/page.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff834501bc)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102e068)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff8102e728)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81031b28)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b69f)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff818c9593)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3e28)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ebe2c2)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dce78)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff819165d6)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff83e6c47f)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81035468)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff81035c78)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810393c8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043e6f)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a1a440)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a26038)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a2a6c8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a302a8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a72046)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff8368cf52)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810353e8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff81035bf8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039308)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043f83)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a6384e)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6f5e8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a73e78)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79ab8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc90d)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff838bcb12)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103b5e8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff8103bbf8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f7b8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a4b2)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81ab609a)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac16e8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac5fd8)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acbf28)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0f6cd)
Location: arch/x86/include/asm/xen/page.h:184
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82891f6e)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020420)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810210d4)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023b00)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d151)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630a63)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81634930)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639477)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8166931e)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff828a4f48)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020280)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020f34)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023960)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cfb1)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165ea33)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166275a)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816675c7)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816976fe)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In arch/x86/xen/setup.c (ffffffff828a4f1c)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810204d0)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81021184)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023e10)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102dda1)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81679573)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167cd2a)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681b87)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b201e)
Location: arch/x86/include/asm/xen/page.h:193
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
</details>
</li>
</ul>

## Differences
