# Function: <code>xen_safe_read_ulong</code>

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
In arch/x86/xen/setup.c (ffffffff81f61cd6)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff8101e830)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff81023f2b)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024ee8)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102ba86)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc4a9)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816f42a3)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d47df)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff374)
Location: arch/x86/include/asm/xen/page.h:70
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
In arch/x86/xen/setup.c (ffffffff81f88fb0)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101dc5b)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff810231d3)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102427f)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102ad9f)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151d1f8)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8175930d)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8152618b)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154fdde)
Location: arch/x86/include/asm/xen/page.h:70
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
In arch/x86/xen/setup.c (ffffffff81fc43a4)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101e34b)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff81023923)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810249af)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102af4a)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81549748)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81785887)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8155269b)
Location: arch/x86/include/asm/xen/page.h:70
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157c98e)
Location: arch/x86/include/asm/xen/page.h:70
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
In arch/x86/xen/setup.c (ffffffff820a420b)
Location: arch/x86/include/asm/xen/page.h:89
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101ce35)
Location: arch/x86/include/asm/xen/page.h:89
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101db83)
Location: arch/x86/include/asm/xen/page.h:89
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102051d)
Location: arch/x86/include/asm/xen/page.h:89
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102979d)
Location: arch/x86/include/asm/xen/page.h:89
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d627)
Location: arch/x86/include/asm/xen/page.h:89
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560db2)
Location: arch/x86/include/asm/xen/page.h:89
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566e6b)
Location: arch/x86/include/asm/xen/page.h:89
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590a52)
Location: arch/x86/include/asm/xen/page.h:89
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
In arch/x86/xen/setup.c (ffffffff826aa8e9)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101dae9)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101e86a)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021200)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810299bc)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1937)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c5092)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815cb01f)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f5732)
Location: arch/x86/include/asm/xen/page.h:99
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
In arch/x86/xen/setup.c (ffffffff826d3a50)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e54c)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101f213)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021ce0)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a403)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f99c7)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fd703)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8160387c)
Location: arch/x86/include/asm/xen/page.h:99
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e4d2)
Location: arch/x86/include/asm/xen/page.h:99
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
In arch/x86/xen/setup.c (ffffffff82889adf)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101ddcb)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101eabd)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021505)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a8dd)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614a7c)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816187d6)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161e988)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c707)
Location: arch/x86/include/asm/xen/page.h:111
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
In arch/x86/xen/setup.c (ffffffff828a0e89)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101f969)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102061d)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023075)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c72a)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8164875c)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164c497)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816513bb)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81681217)
Location: arch/x86/include/asm/xen/page.h:111
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
In arch/x86/xen/setup.c (ffffffff828a3f55)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810202c9)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020f7d)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810239b5)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cffa)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166abfc)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166e927)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8167379b)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a38c7)
Location: arch/x86/include/asm/xen/page.h:111
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
In arch/x86/xen/setup.c (ffffffff82cca50b)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022919)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023771)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026195)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ef81)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171ae4c)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171ec74)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723f6f)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755d47)
Location: arch/x86/include/asm/xen/page.h:110
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
In arch/x86/xen/setup.c (ffffffff82fb6379)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022ee9)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023d41)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810268a5)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fd91)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737fbc)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81c05670)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817405d3)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770fb7)
Location: arch/x86/include/asm/xen/page.h:110
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
In arch/x86/xen/setup.c (ffffffff831c0913)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81025209)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81026792)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4f2e)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810309ae)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b86c)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81bf72ea)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817241d1)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754a77)
Location: arch/x86/include/asm/xen/page.h:110
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
In arch/x86/xen/setup.c (ffffffff832a11a5)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81029719)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102aca2)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c9779c)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103588b)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81790f29)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a49c)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81cf61e9)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a3057)
Location: arch/x86/include/asm/xen/page.h:110
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d8137)
Location: arch/x86/include/asm/xen/page.h:110
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
In arch/x86/xen/setup.c (ffffffff834501d0)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102e078)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff8102e738)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81031b38)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b6af)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff818c95a3)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3e38)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ebe2d6)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dce88)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff819165e6)
Location: arch/x86/include/asm/xen/page.h:106
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
In arch/x86/xen/setup.c (ffffffff83e6c48f)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81035478)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff81035c88)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810393d8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043e7f)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a1a450)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a26048)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a2a6d8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a302b8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a72056)
Location: arch/x86/include/asm/xen/page.h:106
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
In arch/x86/xen/setup.c (ffffffff8368cf5b)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810353f8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff81035c08)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039318)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043f93)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a6385e)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6f5f8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a73e88)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79ac8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc91d)
Location: arch/x86/include/asm/xen/page.h:106
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
In arch/x86/xen/setup.c (ffffffff838bcb1b)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103b5f8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/p2m.c (ffffffff8103bc08)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:mfn_to_pfn
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f7c8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:mfn_to_pfn
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a4c2)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81ab60aa)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac16f8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac5fe8)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acbf38)
Location: arch/x86/include/asm/xen/page.h:106
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:mfn_to_pfn
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0f6dd)
Location: arch/x86/include/asm/xen/page.h:106
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
In arch/x86/xen/setup.c (ffffffff82891f7b)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020429)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810210dd)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023b15)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d15a)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630a6c)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8163493d)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8163948b)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81669327)
Location: arch/x86/include/asm/xen/page.h:111
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
In arch/x86/xen/setup.c (ffffffff828a4f55)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020289)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020f3d)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023975)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cfba)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165ea3c)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81662767)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816675db)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697707)
Location: arch/x86/include/asm/xen/page.h:111
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
In arch/x86/xen/setup.c (ffffffff828a4f29)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810204d9)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102118d)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023e25)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ddaa)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8167957c)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167cd37)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681b9b)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b2027)
Location: arch/x86/include/asm/xen/page.h:111
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
</details>
</li>
</ul>

## Differences
