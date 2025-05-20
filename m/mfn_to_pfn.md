# Function: <code>mfn_to_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81f61cbd)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff8101e810)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:m2v
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu.c:m2v
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
```
```
In arch/x86/xen/suspend.c (ffffffff81023ebf)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024e11)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102b90d)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc4a0)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816f4283)
Location: arch/x86/include/asm/xen/page.h:153
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d47d2)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff367)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_pv_console_init
```
**Symbols:**

```
ffffffff8101e810-ffffffff8101e925: mfn_to_pfn.part.9 (STB_LOCAL)
ffffffff816f4283-ffffffff816f42f8: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81f88f8a)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff81f8a088)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:m2v
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu.c:m2v
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
```
```
In arch/x86/xen/suspend.c (ffffffff8102315f)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024141)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102aca6)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151d1e4)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff817592e0)
Location: arch/x86/include/asm/xen/page.h:153
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81526177)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154fdca)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff8101dc30-ffffffff8101dd48: mfn_to_pfn.part.8 (STB_LOCAL)
ffffffff817592e0-ffffffff81759358: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81fc437e)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff81fc5482)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:m2v
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu.c:m2v
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
```
```
In arch/x86/xen/suspend.c (ffffffff810238af)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024871)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102ae50)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81549734)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8178585a)
Location: arch/x86/include/asm/xen/page.h:153
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81552687)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157c97a)
Location: arch/x86/include/asm/xen/page.h:153
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff8101e320-ffffffff8101e438: mfn_to_pfn.part.7 (STB_LOCAL)
ffffffff8178585a-ffffffff817858d2: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff820a41e5)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101cdc7)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101d9fe)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a62e1)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2v
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2v
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff810295f4)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d613)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560d85)
Location: arch/x86/include/asm/xen/page.h:179
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566e57)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590a3e)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff810204f0-ffffffff81020604: mfn_to_pfn.part.12 (STB_LOCAL)
ffffffff81560d85-ffffffff81560dfd: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff826aa8c3)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101da77)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101e685)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ac9b8)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2v
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2v
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029832)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1923)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c5065)
Location: arch/x86/include/asm/xen/page.h:186
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815cb007)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f571e)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff810211e0-ffffffff810212e2: mfn_to_pfn.part.13 (STB_LOCAL)
ffffffff815c5065-ffffffff815c50e0: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff826d3a2d)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e4e9)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101f1ee)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d5b55)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a26f)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f99b3)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fd6d6)
Location: arch/x86/include/asm/xen/page.h:186
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81603864)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e4be)
Location: arch/x86/include/asm/xen/page.h:186
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81021cc0-ffffffff81021db1: mfn_to_pfn.part.14 (STB_LOCAL)
ffffffff815fd6d6-ffffffff815fd74c: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82889ac9)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101dd78)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101eaa3)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288bbfb)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a8bf)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614a73)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816187b6)
Location: arch/x86/include/asm/xen/page.h:213
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161e978)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c6fe)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff810214f0-ffffffff810215dc: mfn_to_pfn.part.17 (STB_LOCAL)
ffffffff816187b6-ffffffff81618823: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a0e73)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101f917)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020603)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a303c)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c710)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648753)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164c477)
Location: arch/x86/include/asm/xen/page.h:213
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816513a7)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8168120e)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81023060-ffffffff8102314c: mfn_to_pfn.part.0 (STB_LOCAL)
ffffffff8164c477-ffffffff8164c4e8: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a3f3f)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020277)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020f63)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a60ef)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cfe0)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166abf3)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166e907)
Location: arch/x86/include/asm/xen/page.h:213
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673787)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a38be)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff810239a0-ffffffff81023a8c: mfn_to_pfn.part.0 (STB_LOCAL)
ffffffff8166e907-ffffffff8166e978: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82cca4f2)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810228c7)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023757)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc595)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ef67)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171ae43)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171ec54)
Location: arch/x86/include/asm/xen/page.h:212
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723f5b)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755d3e)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81026180-ffffffff8102625e: mfn_to_pfn.part.0 (STB_LOCAL)
ffffffff8171ec54-ffffffff8171ecc5: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82fb6360)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81022e97)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81023d27)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb83d1)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fd77)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737fb3)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81c05650)
Location: arch/x86/include/asm/xen/page.h:212
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817405bf)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770fae)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81026890-ffffffff8102696e: mfn_to_pfn.part.0 (STB_LOCAL)
ffffffff81c05650-ffffffff81c056c1: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff831c08fa)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810251b7)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81026720)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4f0e)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff81030884)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b863)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81bf72ca)
Location: arch/x86/include/asm/xen/page.h:212
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817241c1)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754a6e)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81bc4f0e-ffffffff81bc4fd6: mfn_to_pfn (STB_LOCAL)
ffffffff81bf72ca-ffffffff81bf733b: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff832a118c)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810296c7)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102ac30)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c9777c)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103573b)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81790f20)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a493)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81cf61c9)
Location: arch/x86/include/asm/xen/page.h:212
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a3047)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d812e)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81c9777c-ffffffff81c97844: mfn_to_pfn (STB_LOCAL)
ffffffff81cf61c9-ffffffff81cf623a: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff834501b3)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8102e040)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8102e700)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81031b00)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_p4d_val
  - arch/x86/xen/mmu_pv.c:xen_pud_val
  - arch/x86/xen/mmu_pv.c:xen_pmd_val
  - arch/x86/xen/mmu_pv.c:xen_pgd_val
  - arch/x86/xen/mmu_pv.c:xen_pte_val
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b569)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff818c9593)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3e00)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ebe2aa)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dce50)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff819165d6)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff8102e040-ffffffff8102e13d: mfn_to_pfn (STB_LOCAL)
ffffffff8102e700-ffffffff8102e7fd: mfn_to_pfn (STB_LOCAL)
ffffffff81031b00-ffffffff81031bfd: mfn_to_pfn (STB_LOCAL)
ffffffff818d3e00-ffffffff818d3efd: mfn_to_pfn (STB_LOCAL)
ffffffff81ebe2aa-ffffffff81ebe32a: mfn_to_pfn (STB_LOCAL)
ffffffff818dce50-ffffffff818dcf31: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff83e6c554)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81035440)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81035c50)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810393a0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_p4d_val
  - arch/x86/xen/mmu_pv.c:xen_pud_val
  - arch/x86/xen/mmu_pv.c:xen_pmd_val
  - arch/x86/xen/mmu_pv.c:xen_pgd_val
  - arch/x86/xen/mmu_pv.c:xen_pte_val
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043d39)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a1a440)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a26010)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a2a6a0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30280)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a72046)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81035440-ffffffff8103553d: mfn_to_pfn (STB_LOCAL)
ffffffff81035c50-ffffffff81035d4d: mfn_to_pfn (STB_LOCAL)
ffffffff810393a0-ffffffff8103949d: mfn_to_pfn (STB_LOCAL)
ffffffff81a26010-ffffffff81a2610d: mfn_to_pfn (STB_LOCAL)
ffffffff81a2a6a0-ffffffff81a2a79d: mfn_to_pfn (STB_LOCAL)
ffffffff81a30280-ffffffff81a30361: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8368d02d)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810353c0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81035bd0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810392e0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_p4d_val
  - arch/x86/xen/mmu_pv.c:xen_pud_val
  - arch/x86/xen/mmu_pv.c:xen_pmd_val
  - arch/x86/xen/mmu_pv.c:xen_pgd_val
  - arch/x86/xen/mmu_pv.c:xen_pte_val
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043e4d)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81a6384e)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6f5c0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a73e50)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79a90)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc90d)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff810353c0-ffffffff810354bd: mfn_to_pfn (STB_LOCAL)
ffffffff81035bd0-ffffffff81035ccd: mfn_to_pfn (STB_LOCAL)
ffffffff810392e0-ffffffff810393dd: mfn_to_pfn (STB_LOCAL)
ffffffff81a6f5c0-ffffffff81a6f6bd: mfn_to_pfn (STB_LOCAL)
ffffffff81a73e50-ffffffff81a73f4d: mfn_to_pfn (STB_LOCAL)
ffffffff81a79a90-ffffffff81a79b71: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff838bcbed)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8103b5c0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8103bbd0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f790)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_p4d_val
  - arch/x86/xen/mmu_pv.c:xen_pud_val
  - arch/x86/xen/mmu_pv.c:xen_pmd_val
  - arch/x86/xen/mmu_pv.c:xen_pgd_val
  - arch/x86/xen/mmu_pv.c:xen_pte_val
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a37c)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In drivers/xen/grant-table.c (ffffffff81ab609a)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac16c0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac5fb0)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acbf00)
Location: arch/x86/include/asm/xen/page.h:204
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0f6cd)
Location: arch/x86/include/asm/xen/page.h:204
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff8103b5c0-ffffffff8103b6bd: mfn_to_pfn (STB_LOCAL)
ffffffff8103bbd0-ffffffff8103bccd: mfn_to_pfn (STB_LOCAL)
ffffffff8103f790-ffffffff8103f88d: mfn_to_pfn (STB_LOCAL)
ffffffff81ac16c0-ffffffff81ac17bd: mfn_to_pfn (STB_LOCAL)
ffffffff81ac5fb0-ffffffff81ac60ad: mfn_to_pfn (STB_LOCAL)
ffffffff81acbf00-ffffffff81acbfe1: mfn_to_pfn (STB_LOCAL)
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

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82891f65)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff810203d7)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff810210c3)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828940f8)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d140)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630a63)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8163491d)
Location: arch/x86/include/asm/xen/page.h:213
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639477)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8166931e)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81023b00-ffffffff81023bec: mfn_to_pfn.part.0 (STB_LOCAL)
ffffffff8163491d-ffffffff8163498e: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a4f3f)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020237)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81020f23)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a70ef)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cfa0)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165ea33)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81662747)
Location: arch/x86/include/asm/xen/page.h:213
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816675c7)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816976fe)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81023960-ffffffff81023a4c: mfn_to_pfn.part.0 (STB_LOCAL)
ffffffff81662747-ffffffff816627b8: mfn_to_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a4f13)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff81020487)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81021173)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a70c3)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
Direct callers:
  - arch/x86/xen/mmu_pv.c:m2p
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102dd90)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81679573)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167cd17)
Location: arch/x86/include/asm/xen/page.h:213
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681b87)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b201e)
Location: arch/x86/include/asm/xen/page.h:213
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
**Symbols:**

```
ffffffff81023e10-ffffffff81023efc: mfn_to_pfn.part.0 (STB_LOCAL)
ffffffff8167cd17-ffffffff8167cd88: mfn_to_pfn (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
