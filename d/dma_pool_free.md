# Function: <code>dma_pool_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff811d9410)
Location: mm/dmapool.c:412
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
```
**Symbols:**

```
ffffffff811d9410-ffffffff811d94d3: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff811f75d0)
Location: mm/dmapool.c:411
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
```
**Symbols:**

```
ffffffff811f75d0-ffffffff811f7693: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81207f80)
Location: mm/dmapool.c:411
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
```
**Symbols:**

```
ffffffff81207f80-ffffffff81208043: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81213680)
Location: mm/dmapool.c:411
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
```
**Symbols:**

```
ffffffff81213680-ffffffff81213744: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff8122e200)
Location: mm/dmapool.c:411
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
```
**Symbols:**

```
ffffffff8122e200-ffffffff8122e2c4: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:411
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81251603-ffffffff8125161d: dma_pool_free.cold.14 (STB_LOCAL)
ffffffff81251060-ffffffff81251111: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:411
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81265a0d-ffffffff81265a27: dma_pool_free.cold.9 (STB_LOCAL)
ffffffff81265540-ffffffff812655f1: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81280a0d-ffffffff81280a41: dma_pool_free.cold (STB_LOCAL)
ffffffff81280700-ffffffff812807da: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff8129043d-ffffffff81290471: dma_pool_free.cold (STB_LOCAL)
ffffffff81290130-ffffffff8129020a: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:408
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff812c3093-ffffffff812c30c7: dma_pool_free.cold (STB_LOCAL)
ffffffff812c2d90-ffffffff812c2e6a: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:404
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81be891e-ffffffff81be8962: dma_pool_free.cold (STB_LOCAL)
ffffffff812cea50-ffffffff812ceb1e: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:405
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81bda92d-ffffffff81bda971: dma_pool_free.cold (STB_LOCAL)
ffffffff812d55a0-ffffffff812d566e: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:404
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81cbf0b6-ffffffff81cbf0fa: dma_pool_free.cold (STB_LOCAL)
ffffffff8131b3c0-ffffffff8131b48b: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:404
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81e712ce-ffffffff81e71312: dma_pool_free.cold (STB_LOCAL)
ffffffff81386bb0-ffffffff81386c8f: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81404a10)
Location: mm/dmapool.c:404
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81404a10-ffffffff81404b47: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff814386c0)
Location: mm/dmapool.c:450
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff814386c0-ffffffff81438733: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81472050)
Location: mm/dmapool.c:450
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:qh_destroy
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81472050-ffffffff814720c3: dma_pool_free (STB_GLOBAL)
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
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffff80001032d128)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_free_cb_chain
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffff80001032d128-ffff80001032d2a4: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (c0542fe4)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_free_txd
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg
  - drivers/dma/ti/omap-dma.c:omap_dma_desc_free
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_free
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
c0542fe4-c0543108: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (c000000000404bc0)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_free
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
c000000000404bc0-c000000000404d48: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffe00022b880)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_free
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffe00022b880-ffffffe00022b97a: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/nvme/host/lightnvm.c:nvme_nvm_dev_dma_free
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81288a1d-ffffffff81288a51: dma_pool_free.cold (STB_LOCAL)
ffffffff81288710-ffffffff812887ea: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff8127a86d-ffffffff8127a8a1: dma_pool_free.cold (STB_LOCAL)
ffffffff8127a560-ffffffff8127a63a: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff8128682d-ffffffff81286861: dma_pool_free.cold (STB_LOCAL)
ffffffff81286520-ffffffff812865fa: dma_pool_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dma_pool_free(struct dma_pool *pool, void *vaddr, dma_addr_t dma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:410
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ohci-hcd.c:td_free
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_td
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff8129661d-ffffffff81296651: dma_pool_free.cold (STB_LOCAL)
ffffffff81296310-ffffffff812963ea: dma_pool_free (STB_GLOBAL)
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
