# Function: <code>vmalloc_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cc580)
Location: mm/vmalloc.c:234
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vwrite
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:add_swap_count_continuation
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/md/dm-io.c:vm_get_page
  - net/netlink/af_netlink.c:netlink_mmap
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff811cc580-ffffffff811cc67c: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811e95e0)
Location: mm/vmalloc.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff811e95e0-ffffffff811e96ee: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fa930)
Location: mm/vmalloc.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff811fa930-ffffffff811faa38: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812056e0)
Location: mm/vmalloc.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff812056e0-ffffffff81205841: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121f6b0)
Location: mm/vmalloc.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:SYSC_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8121f6b0-ffffffff8121f8c2: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81240e30)
Location: mm/vmalloc.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81240e30-ffffffff8124100d: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81254b40)
Location: mm/vmalloc.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81254b40-ffffffff81254d1d: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81266ef0)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff81266ef0-ffffffff812670cd: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812757f0)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff812757f0-ffffffff812759cd: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a71b0)
Location: mm/vmalloc.c:350
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_chunk_addr_search
  - mm/percpu.c:pcpu_unmap_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/blk-map.c:bio_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff812a71b0-ffffffff812a73d3: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b2430)
Location: mm/vmalloc.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_chunk_addr_search
  - mm/percpu.c:pcpu_unmap_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/blk-map.c:bio_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff812b2430-ffffffff812b2653: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b8b00)
Location: mm/vmalloc.c:617
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/blk-map.c:blk_rq_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff812b8b00-ffffffff812b8e7d: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:645
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_unmap_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/blk-map.c:blk_rq_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff81cbceb8-ffffffff81cbced4: vmalloc_to_page.cold (STB_LOCAL)
ffffffff812fb0a0-ffffffff812fb41a: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:646
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_unmap_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/blk-map.c:blk_rq_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff81e6eb63-ffffffff81e6eb7f: vmalloc_to_page.cold (STB_LOCAL)
ffffffff813625a0-ffffffff81362904: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:665
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_unmap_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - mm/memcontrol.c:mem_cgroup_from_obj
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/blk-map.c:blk_rq_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff82064a71-ffffffff82064a8d: vmalloc_to_page.cold (STB_LOCAL)
ffffffff813ddf30-ffffffff813de2a7: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:659
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_unmap_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:aligned_vread_iter
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - mm/memcontrol.c:mem_cgroup_from_obj
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/blk-map.c:blk_rq_map_kern
  - lib/iov_iter.c:iov_iter_extract_pages
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff820e4176-ffffffff820e4192: vmalloc_to_page.cold (STB_LOCAL)
ffffffff81412790-ffffffff81412b1a: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:659
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_unmap_pages
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:aligned_vread_iter
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - mm/memcontrol.c:mem_cgroup_from_obj
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/blk-map.c:blk_rq_map_kern
  - lib/iov_iter.c:iov_iter_extract_pages
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_helper_fb_probe
  - drivers/spi/spi.c:spi_map_buf_attrs
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
**Symbols:**

```
ffffffff821c0daa-ffffffff821c0dc6: vmalloc_to_page.cold (STB_LOCAL)
ffffffff8143f200-ffffffff8143f58a: vmalloc_to_page (STB_GLOBAL)
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
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030bcc8)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
  - virt/kvm/arm/mmu.c:create_hyp_mappings
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:__iommu_dma_free
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:__packet_get_status
  - net/packet/af_packet.c:__packet_get_status
  - net/packet/af_packet.c:__packet_set_status
```
**Symbols:**

```
ffff80001030bcc8-ffff80001030bdb4: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0527ce0)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/arm/kernel/patch.c:__patch_text_real
  - kernel/relay.c:relay_buf_fault
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free_work
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
  - sound/core/pcm_memory.c:snd_pcm_lib_get_vmalloc_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_current_block
```
**Symbols:**

```
c0527ce0-c0527dc0: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003db9d0)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-flash.c:image_data_write
  - arch/powerpc/platforms/powernv/opal-flash.c:image_data_write
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_current_block
```
**Symbols:**

```
c0000000003db9d0-c0000000003dbd28: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002151ca)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:__packet_get_status
  - net/packet/af_packet.c:__packet_get_status
  - net/packet/af_packet.c:__packet_set_status
  - net/packet/af_packet.c:__packet_set_status
```
**Symbols:**

```
ffffffe0002151ca-ffffffe000215266: vmalloc_to_page (STB_GLOBAL)
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
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126de40)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8126de40-ffffffff8126e01d: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8125fe70)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - drivers/hv/channel.c:virt_to_hvpfn
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8125fe70-ffffffff8125ffcc: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126bbe0)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8126bbe0-ffffffff8126bdbd: vmalloc_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *vmalloc_to_page(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127b5f0)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/relay.c:relay_buf_fault
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_balance_workfn
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vmalloc_to_pfn
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:swp_swapcount
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - block/bio.c:bio_map_kern
  - drivers/spi/spi.c:spi_map_buf
  - drivers/md/dm-io.c:vm_get_page
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8127b5f0-ffffffff8127b7cd: vmalloc_to_page (STB_GLOBAL)
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
