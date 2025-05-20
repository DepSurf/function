# Function: <code>xhci_free_container_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81652bb0)
Location: drivers/usb/host/xhci-mem.c:529
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_free_command
```
**Symbols:**

```
ffffffff81652bb0-ffffffff81652bde: xhci_free_container_ctx.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b3490)
Location: drivers/usb/host/xhci-mem.c:541
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
**Symbols:**

```
ffffffff816b3490-ffffffff816b34be: xhci_free_container_ctx.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e1640)
Location: drivers/usb/host/xhci-mem.c:541
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
**Symbols:**

```
ffffffff816e1640-ffffffff816e166e: xhci_free_container_ctx.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f7a70)
Location: drivers/usb/host/xhci-mem.c:495
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
**Symbols:**

```
ffffffff816f57a0-ffffffff816f57c8: xhci_free_container_ctx.isra.26.part.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817647a0)
Location: drivers/usb/host/xhci-mem.c:482
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff81762590-ffffffff817625bc: xhci_free_container_ctx.part.35 (STB_LOCAL)
ffffffff817634c0-ffffffff817634d7: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a4a60)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817a2f40-ffffffff817a2f6c: xhci_free_container_ctx.part.38 (STB_LOCAL)
ffffffff817a3710-ffffffff817a3726: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cae30)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817c9230-ffffffff817c925c: xhci_free_container_ctx.part.36 (STB_LOCAL)
ffffffff817c9a30-ffffffff817c9a46: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180b1f1)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffff81808fb0-ffffffff81808fde: xhci_free_container_ctx.part.0 (STB_LOCAL)
ffffffff81809e50-ffffffff81809e66: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183c1b1)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff81839e70-ffffffff81839e9e: xhci_free_container_ctx.part.0 (STB_LOCAL)
ffffffff8183add0-ffffffff8183ade6: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190f4dc)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffff8190d800-ffffffff8190d836: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8191703c)
Location: drivers/usb/host/xhci-mem.c:495
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff819153a0-ffffffff819153d6: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818fa4bc)
Location: drivers/usb/host/xhci-mem.c:495
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff818f88b0-ffffffff818f88e6: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8199923c)
Location: drivers/usb/host/xhci-mem.c:495
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81997010-ffffffff81997046: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af4954)
Location: drivers/usb/host/xhci-mem.c:494
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81af3ec0-ffffffff81af3f09: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c820a1)
Location: drivers/usb/host/xhci-mem.c:494
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81c814c0-ffffffff81c81509: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce8db1)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81ce81d0-ffffffff81ce8219: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9e5e9)
Location: drivers/usb/host/xhci-mem.c:497
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81d9d9e0-ffffffff81d9da29: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a79fb8)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffff800010a77948-ffff800010a77984: xhci_free_container_ctx.part.0 (STB_LOCAL)
ffff800010a788f8-ffff800010a78930: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4d934)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
c0b4b4ec-c0b4b520: xhci_free_container_ctx.part.0 (STB_LOCAL)
c0b4c504-c0b4c528: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b51788)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
c000000000b4e550-c000000000b4e5a8: xhci_free_container_ctx.part.0 (STB_LOCAL)
c000000000b4fd90-c000000000b4fdac: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00069170c)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffe00068f504-ffffffe00068f548: xhci_free_container_ctx.part.0 (STB_LOCAL)
ffffffe00069039c-ffffffe0006903d0: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f4561)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff817f2220-ffffffff817f224e: xhci_free_container_ctx.part.0 (STB_LOCAL)
ffffffff817f3180-ffffffff817f3196: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b9701)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff817b73c0-ffffffff817b73ee: xhci_free_container_ctx.part.0 (STB_LOCAL)
ffffffff817b8320-ffffffff817b8336: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81831031)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff8182ecf0-ffffffff8182ed1e: xhci_free_container_ctx.part.0 (STB_LOCAL)
ffffffff8182fc50-ffffffff8182fc66: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184b201)
Location: drivers/usb/host/xhci-mem.c:486
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff81848e60-ffffffff81848e8e: xhci_free_container_ctx.part.0 (STB_LOCAL)
ffffffff81849df0-ffffffff81849e06: xhci_free_container_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
