# Function: <code>vunmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cee80)
Location: mm/vmalloc.c:1533
Inline: True
Direct callers:
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/base/dma-mapping.c:dma_common_pages_remap
  - drivers/base/dma-mapping.c:dma_common_free_remap
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff811cee80-ffffffff811ceeb4: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec010)
Location: mm/vmalloc.c:1554
Inline: True
Direct callers:
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/base/dma-mapping.c:dma_common_free_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:__fw_free_buf
```
**Symbols:**

```
ffffffff811ec010-ffffffff811ec044: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd250)
Location: mm/vmalloc.c:1569
Inline: True
Direct callers:
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/base/dma-mapping.c:dma_common_free_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:__fw_free_buf
```
**Symbols:**

```
ffffffff811fd250-ffffffff811fd284: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81207f30)
Location: mm/vmalloc.c:1621
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/base/dma-mapping.c:dma_common_free_remap
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:fw_free_buf
```
**Symbols:**

```
ffffffff81207f30-ffffffff81207f64: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81221010)
Location: mm/vmalloc.c:1619
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/base/dma-mapping.c:dma_common_free_remap
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:__fw_free_buf
```
**Symbols:**

```
ffffffff81221010-ffffffff81221044: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242ec0)
Location: mm/vmalloc.c:1606
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_common_free_remap
  - kernel/dma/mapping.c:dma_common_contiguous_remap
  - kernel/dma/mapping.c:dma_common_pages_remap
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81242ec0-ffffffff81242ef4: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812575d0)
Location: mm/vmalloc.c:1612
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff812575d0-ffffffff81257604: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81269810)
Location: mm/vmalloc.c:2344
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
```
**Symbols:**

```
ffffffff81269810-ffffffff81269846: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81278750)
Location: mm/vmalloc.c:2350
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
```
**Symbols:**

```
ffffffff81278750-ffffffff81278786: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac000)
Location: mm/vmalloc.c:2397
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_vunmap
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_release
  - net/xdp/xsk_buff_pool.c:xp_create
```
**Symbols:**

```
ffffffff812ac000-ffffffff812ac038: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b75c0)
Location: mm/vmalloc.c:2379
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff812b75c0-ffffffff812b75f8: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bce90)
Location: mm/vmalloc.c:2661
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff812bce90-ffffffff812bcec8: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff600)
Location: mm/vmalloc.c:2714
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff812ff600-ffffffff812ff638: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81366750)
Location: mm/vmalloc.c:2758
Inline: True
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_unmap_memory
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81366750-ffffffff81366791: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e23a0)
Location: mm/vmalloc.c:2820
Inline: True
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_unmap_memory
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff813e23a0-ffffffff813e23e1: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81416c10)
Location: mm/vmalloc.c:2861
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/module/decompress.c:module_decompress_cleanup
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81416c10-ffffffff81416c6f: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814436e0)
Location: mm/vmalloc.c:2861
Inline: True
Direct callers:
  - kernel/dma/mapping.c:dma_vunmap_noncontiguous
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/module/decompress.c:module_decompress_cleanup
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - kernel/bpf/ringbuf.c:ringbuf_map_free
  - mm/vmalloc.c:vmap
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vunmap
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff814436e0-ffffffff8144373f: vunmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030f0c8)
Location: mm/vmalloc.c:2350
Inline: True
Direct callers:
  - arch/arm64/mm/ioremap.c:iounmap
  - arch/arm64/mm/ioremap.c:__ioremap_caller
  - kernel/dma/remap.c:arch_dma_free
  - kernel/dma/remap.c:__dma_common_pages_remap
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
```
**Symbols:**

```
ffff80001030f0c8-ffff80001030f114: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052a92c)
Location: mm/vmalloc.c:2350
Inline: True
Direct callers:
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
  - arch/arm/mm/ioremap.c:__iounmap
  - arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/dma/remap.c:__dma_common_pages_remap
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - fs/pstore/ram_core.c:persistent_ram_free
  - security/keys/big_key.c:big_key_free_buffer
  - net/xdp/xdp_umem.c:xdp_umem_unmap_pages
```
**Symbols:**

```
c052a92c-c052a988: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e0120)
Location: mm/vmalloc.c:2350
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_64.c:pcibios_unmap_io_space
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
```
**Symbols:**

```
c0000000003e0120-c0000000003e0194: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000217890)
Location: mm/vmalloc.c:2350
Inline: True
Direct callers:
  - arch/riscv/mm/ioremap.c:iounmap
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
```
**Symbols:**

```
ffffffe000217890-ffffffe0002178da: vunmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270da0)
Location: mm/vmalloc.c:2350
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
```
**Symbols:**

```
ffffffff81270da0-ffffffff81270dd6: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81262d10)
Location: mm/vmalloc.c:2350
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
  - drivers/hv/ring_buffer.c:hv_ringbuffer_cleanup
```
**Symbols:**

```
ffffffff81262d10-ffffffff81262d46: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126eb40)
Location: mm/vmalloc.c:2350
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/base/firmware_loader/main.c:fw_map_paged_buf
```
**Symbols:**

```
ffffffff8126eb40-ffffffff8126eb76: vunmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void vunmap(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127e530)
Location: mm/vmalloc.c:2350
Inline: True
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/relay.c:relay_destroy_buf
  - mm/vmalloc.c:vmap
  - security/keys/big_key.c:big_key_free_buffer
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
```
**Symbols:**

```
ffffffff8127e530-ffffffff8127e558: vunmap (STB_GLOBAL)
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
