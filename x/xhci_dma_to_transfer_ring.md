# Function: <code>xhci_dma_to_transfer_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81653db0)
Location: drivers/usb/host/xhci-mem.c:619
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81653db0-ffffffff81653dd6: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b4840)
Location: drivers/usb/host/xhci-mem.c:631
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816b4840-ffffffff816b4866: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e29f0)
Location: drivers/usb/host/xhci-mem.c:631
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816e29f0-ffffffff816e2a16: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f6af0)
Location: drivers/usb/host/xhci-mem.c:585
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816f6af0-ffffffff816f6b16: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81763560)
Location: drivers/usb/host/xhci-mem.c:572
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81763560-ffffffff81763586: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a37b0)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817a37b0-ffffffff817a37d6: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c9ad0)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817c9ad0-ffffffff817c9af6: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81809ef0)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff81809ef0-ffffffff81809f16: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183ae70)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff8183ae70-ffffffff8183ae96: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190d8c0)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff8190d8c0-ffffffff8190d8e6: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81915460)
Location: drivers/usb/host/xhci-mem.c:585
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81915460-ffffffff81915486: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f8940)
Location: drivers/usb/host/xhci-mem.c:585
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff818f8940-ffffffff818f8967: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819970a0)
Location: drivers/usb/host/xhci-mem.c:585
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff819970a0-ffffffff819970c7: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af3f70)
Location: drivers/usb/host/xhci-mem.c:584
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81af3f70-ffffffff81af3fa7: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c815a0)
Location: drivers/usb/host/xhci-mem.c:584
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81c815a0-ffffffff81c815d7: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce82b0)
Location: drivers/usb/host/xhci-mem.c:570
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81ce82b0-ffffffff81ce82e7: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9dac0)
Location: drivers/usb/host/xhci-mem.c:581
Inline: False
```
**Symbols:**

```
ffffffff81d9dac0-ffffffff81d9daf7: xhci_dma_to_transfer_ring (STB_GLOBAL)
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
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a78a28)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffff800010a78a28-ffff800010a78a78: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4c5d0)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
c0b4c5d0-c0b4c610: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4fe90)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
c000000000b4fe90-c000000000b4fef0: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00069049a)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffe00069049a-ffffffe0006904e6: xhci_dma_to_transfer_ring (STB_GLOBAL)
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
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f3220)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817f3220-ffffffff817f3246: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b83c0)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817b83c0-ffffffff817b83e6: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8182fcf0)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff8182fcf0-ffffffff8182fd16: xhci_dma_to_transfer_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xhci_ring *xhci_dma_to_transfer_ring(struct xhci_virt_ep *ep, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81849e90)
Location: drivers/usb/host/xhci-mem.c:576
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff81849e90-ffffffff81849eb6: xhci_dma_to_transfer_ring (STB_GLOBAL)
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
