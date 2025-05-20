# Function: <code>xhci_endpoint_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81654c60)
Location: drivers/usb/host/xhci-mem.c:1589
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff81654c60-ffffffff81654cdc: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b5670)
Location: drivers/usb/host/xhci-mem.c:1605
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff816b5670-ffffffff816b56d0: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e3820)
Location: drivers/usb/host/xhci-mem.c:1638
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff816e3820-ffffffff816e3880: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f7860)
Location: drivers/usb/host/xhci-mem.c:1590
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff816f7860-ffffffff816f78c0: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817645a0)
Location: drivers/usb/host/xhci-mem.c:1592
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff817645a0-ffffffff81764600: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a4810)
Location: drivers/usb/host/xhci-mem.c:1601
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff817a4810-ffffffff817a488a: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817caba0)
Location: drivers/usb/host/xhci-mem.c:1601
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff817caba0-ffffffff817cac1a: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180af90)
Location: drivers/usb/host/xhci-mem.c:1601
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff8180af90-ffffffff8180b006: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183bf50)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff8183bf50-ffffffff8183bfc6: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190ed20)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff8190ed20-ffffffff8190ed96: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81916880)
Location: drivers/usb/host/xhci-mem.c:1615
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff81916880-ffffffff819168f6: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f9d00)
Location: drivers/usb/host/xhci-mem.c:1602
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff818f9d00-ffffffff818f9d76: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81998990)
Location: drivers/usb/host/xhci-mem.c:1602
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff81998990-ffffffff81998a06: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af5960)
Location: drivers/usb/host/xhci-mem.c:1593
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff81af5960-ffffffff81af59eb: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c83210)
Location: drivers/usb/host/xhci-mem.c:1602
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff81c83210-ffffffff81c8329b: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce9f50)
Location: drivers/usb/host/xhci-mem.c:1583
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff81ce9f50-ffffffff81ce9fdb: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9f780)
Location: drivers/usb/host/xhci-mem.c:1591
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
```
**Symbols:**

```
ffffffff81d9f780-ffffffff81d9f80b: xhci_endpoint_copy (STB_GLOBAL)
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
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a79ca8)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffff800010a79ca8-ffff800010a79d60: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4d6b8)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
c0b4d6b8-c0b4d758: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b51400)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
c000000000b51400-c000000000b514b0: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe000691482)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffe000691482-ffffffe000691528: xhci_endpoint_copy (STB_GLOBAL)
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
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f4300)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff817f4300-ffffffff817f4376: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b94a0)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff817b94a0-ffffffff817b9516: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81830dd0)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81830dd0-ffffffff81830e46: xhci_endpoint_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xhci_endpoint_copy(struct xhci_hcd *xhci, struct xhci_container_ctx *in_ctx, struct xhci_container_ctx *out_ctx, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184afa0)
Location: drivers/usb/host/xhci-mem.c:1607
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff8184afa0-ffffffff8184b016: xhci_endpoint_copy (STB_GLOBAL)
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
