# Function: <code>xhci_td_remainder</code>

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
In drivers/usb/host/xhci-ring.c (ffffffff81657590)
Location: drivers/usb/host/xhci-ring.c:3062
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff81657590-ffffffff816575d7: xhci_td_remainder.isra.20.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816b7d60)
Location: drivers/usb/host/xhci-ring.c:3104
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff816b7d60-ffffffff816b7dca: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e6010)
Location: drivers/usb/host/xhci-ring.c:3005
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff816e6010-ffffffff816e607a: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816f9d30)
Location: drivers/usb/host/xhci-ring.c:3105
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff816f9d30-ffffffff816f9d96: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817662a0)
Location: drivers/usb/host/xhci-ring.c:3109
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff817662a0-ffffffff81766312: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817a6fe0)
Location: drivers/usb/host/xhci-ring.c:3028
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff817a6fe0-ffffffff817a7052: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817cce90)
Location: drivers/usb/host/xhci-ring.c:3092
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff817cce90-ffffffff817ccf02: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8180cc00)
Location: drivers/usb/host/xhci-ring.c:3138
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8180cc00-ffffffff8180cc74: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8183dc50)
Location: drivers/usb/host/xhci-ring.c:3165
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8183dc50-ffffffff8183dcc4: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81910450)
Location: drivers/usb/host/xhci-ring.c:3211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81910450-ffffffff819104c4: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81917cd0)
Location: drivers/usb/host/xhci-ring.c:3221
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81917cd0-ffffffff81917d44: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fb160)
Location: drivers/usb/host/xhci-ring.c:3410
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff818fb160-ffffffff818fb1d7: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81999fd0)
Location: drivers/usb/host/xhci-ring.c:3480
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81999fd0-ffffffff8199a047: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81af7000)
Location: drivers/usb/host/xhci-ring.c:3415
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81af7000-ffffffff81af70a7: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c84aa0)
Location: drivers/usb/host/xhci-ring.c:3422
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81c84aa0-ffffffff81c84b47: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81ceb760)
Location: drivers/usb/host/xhci-ring.c:3442
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81ceb760-ffffffff81ceb807: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da0d80)
Location: drivers/usb/host/xhci-ring.c:3485
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81da0d80-ffffffff81da0e27: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7c100)
Location: drivers/usb/host/xhci-ring.c:3165
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffff800010a7c100-ffff800010a7c1d4: xhci_td_remainder.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b4f170)
Location: drivers/usb/host/xhci-ring.c:3165
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
c0b4f170-c0b4f228: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b54200)
Location: drivers/usb/host/xhci-ring.c:3165
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
c000000000b54200-c000000000b5429c: xhci_td_remainder.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000693384)
Location: drivers/usb/host/xhci-ring.c:3165
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffe000693384-ffffffe00069343c: xhci_td_remainder.isra.0 (STB_LOCAL)
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
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817f6000)
Location: drivers/usb/host/xhci-ring.c:3165
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff817f6000-ffffffff817f6074: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bb1a0)
Location: drivers/usb/host/xhci-ring.c:3165
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff817bb1a0-ffffffff817bb214: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81832ad0)
Location: drivers/usb/host/xhci-ring.c:3165
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81832ad0-ffffffff81832b44: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd *xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb *urb, bool more_trbs_coming);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8184ccb0)
Location: drivers/usb/host/xhci-ring.c:3165
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8184ccb0-ffffffff8184cd24: xhci_td_remainder (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
