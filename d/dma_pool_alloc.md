# Function: <code>dma_pool_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff811d95c0)
Location: mm/dmapool.c:321
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff811d95c0-ffffffff811d97fd: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff811f7780)
Location: mm/dmapool.c:320
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff811f7780-ffffffff811f79ca: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81208130)
Location: mm/dmapool.c:320
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81208130-ffffffff8120837a: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81213820)
Location: mm/dmapool.c:320
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81213820-ffffffff81213a5f: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff8122e3a0)
Location: mm/dmapool.c:320
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
```
**Symbols:**

```
ffffffff8122e3a0-ffffffff8122e5e2: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff812511f0)
Location: mm/dmapool.c:320
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff812511f0-ffffffff81251456: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81265600)
Location: mm/dmapool.c:320
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81265600-ffffffff812657cf: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81280520)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81280520-ffffffff812806fb: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff8128ff50)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff8128ff50-ffffffff8129012b: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff812c2c80)
Location: mm/dmapool.c:317
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff812c2c80-ffffffff812c2d8b: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff812ceb20)
Location: mm/dmapool.c:314
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff812ceb20-ffffffff812cec22: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff812d5670)
Location: mm/dmapool.c:315
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff812d5670-ffffffff812d5842: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff8131b490)
Location: mm/dmapool.c:314
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff8131b490-ffffffff8131b6a0: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81386c90)
Location: mm/dmapool.c:314
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81386c90-ffffffff81386e9f: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81404b60)
Location: mm/dmapool.c:314
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81404b60-ffffffff81404d72: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff814380e0)
Location: mm/dmapool.c:404
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff814380e0-ffffffff81438311: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81471a40)
Location: mm/dmapool.c:404
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81471a40-ffffffff81471c8d: dma_pool_alloc (STB_GLOBAL)
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
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffff80001032d2a8)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_create_cb_chain
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffff80001032d2a8-ffff80001032d544: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (c0542e14)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_td
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
c0542e14-c0542fe4: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (c000000000404910)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_td
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
c000000000404910-c000000000404bb4: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffe00022b6d8)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_td
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffe00022b6d8-ffffffe00022b880: dma_pool_alloc (STB_GLOBAL)
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
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81288530)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/nvme/host/lightnvm.c:nvme_nvm_dev_dma_alloc
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81288530-ffffffff8128870b: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff8127a380)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff8127a380-ffffffff8127a55b: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81286340)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81286340-ffffffff8128651b: dma_pool_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *dma_pool_alloc(struct dma_pool *pool, gfp_t mem_flags, dma_addr_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81296140)
Location: mm/dmapool.c:319
Inline: False
Direct callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
**Symbols:**

```
ffffffff81296140-ffffffff81296301: dma_pool_alloc (STB_GLOBAL)
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
