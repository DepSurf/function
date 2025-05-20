# Function: <code>vmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ceec0)
Location: mm/vmalloc.c:1552
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:xen_pvh_gnttab_setup
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff811ceec0-ffffffff811cef6e: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec050)
Location: mm/vmalloc.c:1573
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff811ec050-ffffffff811ec0fe: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd290)
Location: mm/vmalloc.c:1588
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff811fd290-ffffffff811fd33e: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81207f70)
Location: mm/vmalloc.c:1640
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81207f70-ffffffff81208014: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81221050)
Location: mm/vmalloc.c:1638
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81221050-ffffffff812210f4: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242f00)
Location: mm/vmalloc.c:1625
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81242f00-ffffffff81242fa4: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257610)
Location: mm/vmalloc.c:1631
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81257610-ffffffff812576b7: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a3f0)
Location: mm/vmalloc.c:2365
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff8126a3f0-ffffffff8126a497: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81279300)
Location: mm/vmalloc.c:2371
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81279300-ffffffff812793a7: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac040)
Location: mm/vmalloc.c:2418
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:map_irq_stack
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/relay.c:relay_alloc_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_vmap
  - net/xdp/xsk_buff_pool.c:xp_create
```
**Symbols:**

```
ffffffff812ac040-ffffffff812ac0ce: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7600)
Location: mm/vmalloc.c:2403
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:map_irq_stack
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/relay.c:relay_alloc_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/dma-buf/heaps/system_heap.c:system_heap_do_vmap
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff812b7600-ffffffff812b76b4: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bced0)
Location: mm/vmalloc.c:2685
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/relay.c:relay_create_buf
  - kernel/relay.c:relay_create_buf
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff812bced0-ffffffff812bcf85: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff640)
Location: mm/vmalloc.c:2738
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/relay.c:relay_create_buf
  - kernel/relay.c:relay_create_buf
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff812ff640-ffffffff812ff6f5: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813667a0)
Location: mm/vmalloc.c:2782
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/dma/remap.c:dma_common_pages_remap
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/relay.c:relay_alloc_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff813667a0-ffffffff8136687d: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e2400)
Location: mm/vmalloc.c:2844
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/dma/remap.c:dma_common_pages_remap
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/relay.c:relay_alloc_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff813e2400-ffffffff813e24dd: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81416c80)
Location: mm/vmalloc.c:2895
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/dma/remap.c:dma_common_pages_remap
  - kernel/module/decompress.c:module_decompress
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/relay.c:relay_alloc_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff81416c80-ffffffff81416d70: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81443750)
Location: mm/vmalloc.c:2895
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/dma/remap.c:dma_common_pages_remap
  - kernel/module/decompress.c:module_decompress
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/relay.c:relay_alloc_buf
  - kernel/relay.c:relay_alloc_buf
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vmap
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff81443750-ffffffff81443840: vmap (STB_GLOBAL)
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
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030fd48)
Location: mm/vmalloc.c:2371
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffff80001030fd48-ffff80001030fe10: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c264)
Location: mm/vmalloc.c:2371
Inline: False
Direct callers:
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - fs/pstore/ram_core.c:persistent_ram_new
  - security/keys/big_key.c:big_key_alloc_buffer
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
c052c264-c052c2e0: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e0fa0)
Location: mm/vmalloc.c:2371
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
c0000000003e0fa0-c0000000003e10ac: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002182aa)
Location: mm/vmalloc.c:2371
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
**Symbols:**

```
ffffffe0002182aa-ffffffe00021833e: vmap (STB_GLOBAL)
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
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271950)
Location: mm/vmalloc.c:2371
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81271950-ffffffff812719f7: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812638c0)
Location: mm/vmalloc.c:2371
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
  - drivers/hv/ring_buffer.c:hv_ringbuffer_init
```
**Symbols:**

```
ffffffff812638c0-ffffffff81263967: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126f6f0)
Location: mm/vmalloc.c:2371
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
```
**Symbols:**

```
ffffffff8126f6f0-ffffffff8126f797: vmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *vmap(struct page **pages, unsigned int count, long unsigned int flags, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f110)
Location: mm/vmalloc.c:2371
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - security/keys/big_key.c:big_key_alloc_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff8127f110-ffffffff8127f1a4: vmap (STB_GLOBAL)
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
