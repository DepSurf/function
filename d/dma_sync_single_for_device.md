# Function: <code>dma_sync_single_for_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509c8d)
Location: include/asm-generic/dma-mapping-common.h:115
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155bc3b)
Location: include/linux/dma-mapping.h:273
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81687e86)
Location: include/linux/dma-mapping.h:273
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168f902)
Location: include/linux/dma-mapping.h:273
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8158841e)
Location: include/linux/dma-mapping.h:323
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b60b6)
Location: include/linux/dma-mapping.h:323
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bd9b2)
Location: include/linux/dma-mapping.h:323
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c880)
Location: include/linux/dma-mapping.h:366
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816ca3d9)
Location: include/linux/dma-mapping.h:366
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d1a5c)
Location: include/linux/dma-mapping.h:366
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81601b88)
Location: include/linux/dma-mapping.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81736919)
Location: include/linux/dma-mapping.h:364
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173e0dc)
Location: include/linux/dma-mapping.h:364
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163ae3f)
Location: include/linux/dma-mapping.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81776362)
Location: include/linux/dma-mapping.h:364
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177ea20)
Location: include/linux/dma-mapping.h:364
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81659037)
Location: include/linux/dma-mapping.h:394
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179bd32)
Location: include/linux/dma-mapping.h:394
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a5181)
Location: include/linux/dma-mapping.h:394
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e50d)
Location: include/linux/dma-mapping.h:397
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817dae28)
Location: include/linux/dma-mapping.h:397
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4354)
Location: include/linux/dma-mapping.h:397
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0add)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180bd48)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81815214)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763ebd)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818dcc98)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6575)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_fill_host_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
```
In net/core/page_pool.c (ffffffff81a3a5a7)
Location: include/linux/dma-mapping.h:390
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9aba)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138130)
Location: kernel/dma/mapping.c:272
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_fill_host_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff81138130-ffffffff811381f0: dma_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81139200)
Location: kernel/dma/mapping.c:274
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff81139200-ffffffff811392bc: dma_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115c090)
Location: kernel/dma/mapping.c:339
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff8115c090-ffffffff8115c143: dma_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185d20)
Location: kernel/dma/mapping.c:335
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff81185d20-ffffffff81185e1a: dma_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c1700)
Location: kernel/dma/mapping.c:342
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff811c1700-ffffffff811c17fd: dma_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d4180)
Location: kernel/dma/mapping.c:346
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff811d4180-ffffffff811d427d: dma_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/mapping.c:346
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_dma_sync_single_range_for_device
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_unrefed_page
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff821b472e-ffffffff821b4749: dma_sync_single_for_device.cold (STB_LOCAL)
ffffffff811e8df0-ffffffff811e8f2e: dma_sync_single_for_device (STB_GLOBAL)
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
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bf38)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb154)
Location: include/linux/dma-mapping.h:390
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d93c0)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e3078)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6fa0)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a442e8)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e454)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (c0989924)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/iommu/io-pgtable-arm.c (c09bfd60)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_sync_pte
```
```
In drivers/iommu/omap-iommu.c (c09c4170)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:_omap_iommu_detach_dev
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopte_alloc_large
  - drivers/iommu/omap-iommu.c:iopte_alloc_page
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c6dcc)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/iommu/tegra-smmu.c (c09c85b4)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pte
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde
```
```
In drivers/iommu/exynos-iommu.c (c09caeb4)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acbcf0)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad7120)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
```
```
In drivers/usb/dwc2/hcd.c (c0b16b34)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b20378)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
```
In drivers/mmc/host/sdhci.c (c0c22930)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer
```
```
In drivers/firmware/tegra/ivc.c (c0c43fd8)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/firmware/tegra/ivc.c:tegra_ivc_notified
  - drivers/firmware/tegra/ivc.c:tegra_ivc_notified
  - drivers/firmware/tegra/ivc.c:tegra_ivc_reset
  - drivers/firmware/tegra/ivc.c:tegra_ivc_read_advance
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5c18c)
Location: include/linux/dma-mapping.h:390
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (c000000000934a5c)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (c000000000b07068)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15e48)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (ffffffe0005557ee)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffe00066097a)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066ae14)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b38e)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_command_send
```
</details>
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8167654d)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c4128)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cd5f4)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8165562d)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a491d)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81800bc8)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8180a094)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff816bed7d)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181acd8)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818241a4)
Location: include/linux/dma-mapping.h:390
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
