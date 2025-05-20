# Function: <code>dma_pool_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff811d91f0)
Location: mm/dmapool.c:131
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff811d91f0-ffffffff811d9409: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff811f73a0)
Location: mm/dmapool.c:131
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff811f73a0-ffffffff811f75ce: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81207d50)
Location: mm/dmapool.c:131
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81207d50-ffffffff81207f7e: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81213480)
Location: mm/dmapool.c:131
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81213480-ffffffff8121367b: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff8122e000)
Location: mm/dmapool.c:131
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8122e000-ffffffff8122e1fb: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81250e50)
Location: mm/dmapool.c:131
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81250e50-ffffffff81251051: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81265330)
Location: mm/dmapool.c:131
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81265330-ffffffff81265531: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81280300)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81280300-ffffffff8128051d: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff8128fd30)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8128fd30-ffffffff8128ff4d: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff812c2990)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff812c2990-ffffffff812c2b8b: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff812ce6d0)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff812ce6d0-ffffffff812ce95d: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:131
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81bda915-ffffffff81bda92d: dma_pool_create.cold (STB_LOCAL)
ffffffff812d5360-ffffffff812d5595: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81cbf09e-ffffffff81cbf0b6: dma_pool_create.cold (STB_LOCAL)
ffffffff8131b180-ffffffff8131b3b5: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/dmapool.c (0)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81e712b6-ffffffff81e712ce: dma_pool_create.cold (STB_LOCAL)
ffffffff81386980-ffffffff81386ba8: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff814047c0)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff814047c0-ffffffff81404a00: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81438390)
Location: mm/dmapool.c:224
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81438390-ffffffff814385e1: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81471d00)
Location: mm/dmapool.c:224
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/dma/lgm/lgm-dma.c:ldma_alloc_chan_resources
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81471d00-ffffffff81471f80: dma_pool_create (STB_GLOBAL)
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
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffff80001032caf0)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_alloc_chan_resources
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffff80001032caf0-ffff80001032cce8: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (c0542c34)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
c0542c34-c0542e14: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (c000000000404620)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
c000000000404620-c00000000040490c: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffe00022b504)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffe00022b504-ffffffe00022b6d8: dma_pool_create (STB_GLOBAL)
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
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81288310)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/nvme/host/lightnvm.c:nvme_nvm_create_dma_pool
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81288310-ffffffff8128852d: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff8127a160)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8127a160-ffffffff8127a37d: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81286120)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81286120-ffffffff8128633d: dma_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dma_pool *dma_pool_create(const char *name, struct device *dev, size_t size, size_t align, size_t boundary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/dmapool.c (ffffffff81295f20)
Location: mm/dmapool.c:130
Inline: False
Direct callers:
  - mm/dmapool.c:dmam_pool_create
  - drivers/usb/core/buffer.c:hcd_buffer_create
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81295f20-ffffffff8129613d: dma_pool_create (STB_GLOBAL)
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
