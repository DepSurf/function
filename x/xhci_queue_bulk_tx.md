# Function: <code>xhci_queue_bulk_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816585e0)
Location: drivers/usb/host/xhci-ring.c:3255
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff816585e0-ffffffff81658f20: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816b8ff0)
Location: drivers/usb/host/xhci-ring.c:3192
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff816b8ff0-ffffffff816b98e5: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e7270)
Location: drivers/usb/host/xhci-ring.c:3093
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff816e7270-ffffffff816e7b59: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fb320)
Location: drivers/usb/host/xhci-ring.c:3193
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff816fb320-ffffffff816fbc97: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81767e90)
Location: drivers/usb/host/xhci-ring.c:3197
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81767e90-ffffffff81768801: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817a9170)
Location: drivers/usb/host/xhci-ring.c:3116
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff817a9170-ffffffff817a9aaa: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817cf0e0)
Location: drivers/usb/host/xhci-ring.c:3180
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff817cf0e0-ffffffff817cfa60: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3231
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff818134cf-ffffffff8181357b: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff8180f4a0-ffffffff8180ff02: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3258
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff818446f9-ffffffff8184477d: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff818405b0-ffffffff818410f4: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3304
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81917480-ffffffff819174ca: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff81914ef0-ffffffff8191549c: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3318
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81c22393-ffffffff81c223dd: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff8191c4c0-ffffffff8191ca85: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3507
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81c146f6-ffffffff81c14740: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff819008c0-ffffffff81900ee5: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3577
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81d2186e-ffffffff81d218b8: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff819a0060-ffffffff819a06e5: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3512
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81eed4b4-ffffffff81eed506: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff81afd720-ffffffff81afde54: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8c440)
Location: drivers/usb/host/xhci-ring.c:3519
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81c8c440-ffffffff81c8cbdd: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf2fd0)
Location: drivers/usb/host/xhci-ring.c:3539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81cf2fd0-ffffffff81cf3760: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da8910)
Location: drivers/usb/host/xhci-ring.c:3582
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81da8910-ffffffff81da90a0: xhci_queue_bulk_tx (STB_GLOBAL)
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
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7f378)
Location: drivers/usb/host/xhci-ring.c:3258
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffff800010a7f378-ffff800010a7fe1c: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b526fc)
Location: drivers/usb/host/xhci-ring.c:3258
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
c0b526fc-c0b53244: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b57f60)
Location: drivers/usb/host/xhci-ring.c:3258
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
c000000000b57f60-c000000000b58b3c: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000695ee2)
Location: drivers/usb/host/xhci-ring.c:3258
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffe000695ee2-ffffffe000696828: xhci_queue_bulk_tx (STB_GLOBAL)
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
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3258
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff817fcaa9-ffffffff817fcb2d: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff817f8960-ffffffff817f94a4: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3258
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff817c1c49-ffffffff817c1ccd: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff817bdb00-ffffffff817be644: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3258
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff81839579-ffffffff818395fd: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff81835430-ffffffff81835f74: xhci_queue_bulk_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_queue_bulk_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3258
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx
```
**Symbols:**

```
ffffffff818539cc-ffffffff81853a50: xhci_queue_bulk_tx.cold (STB_LOCAL)
ffffffff8184f750-ffffffff818502c3: xhci_queue_bulk_tx (STB_GLOBAL)
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
