# Function: <code>xhci_free_stream_ctx</code>

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
In drivers/usb/host/xhci-mem.c (ffffffff8165532d)
Location: drivers/usb/host/xhci-mem.c:573
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b5d3d)
Location: drivers/usb/host/xhci-mem.c:585
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e3eed)
Location: drivers/usb/host/xhci-mem.c:585
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f7eae)
Location: drivers/usb/host/xhci-mem.c:539
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81764bce)
Location: drivers/usb/host/xhci-mem.c:526
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a4f08)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cb228)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180b608)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183c5c8)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190c8c7)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81914297)
Location: drivers/usb/host/xhci-mem.c:539
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f7aa5)
Location: drivers/usb/host/xhci-mem.c:539
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81996075)
Location: drivers/usb/host/xhci-mem.c:539
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af2d64)
Location: drivers/usb/host/xhci-mem.c:538
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_stream_ctx(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, struct xhci_stream_ctx *stream_ctx, dma_addr_t dma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c7f950)
Location: drivers/usb/host/xhci-mem.c:538
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81c7f950-ffffffff81c7f9f5: xhci_free_stream_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_stream_ctx(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, struct xhci_stream_ctx *stream_ctx, dma_addr_t dma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce6630)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81ce6630-ffffffff81ce66d5: xhci_free_stream_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_stream_ctx(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, struct xhci_stream_ctx *stream_ctx, dma_addr_t dma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9b890)
Location: drivers/usb/host/xhci-mem.c:541
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81d9b890-ffffffff81d9b935: xhci_free_stream_ctx (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a7a3b0)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4dd1c)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b51cc0)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe000691a90)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f4978)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
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
In drivers/usb/host/xhci-mem.c (ffffffff817b9b18)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81831448)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184b618)
Location: drivers/usb/host/xhci-mem.c:530
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
