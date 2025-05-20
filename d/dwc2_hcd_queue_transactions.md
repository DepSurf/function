# Function: <code>dwc2_hcd_queue_transactions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81628e90)
Location: drivers/usb/dwc2/hcd.c:1323
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81628e90-ffffffff816291e8: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81688ca0)
Location: drivers/usb/dwc2/hcd.c:3159
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81688ca0-ffffffff81688fb6: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b6ec0)
Location: drivers/usb/dwc2/hcd.c:3190
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff816b6ec0-ffffffff816b71ce: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816cb220)
Location: drivers/usb/dwc2/hcd.c:3203
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff816cb220-ffffffff816cb4fc: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81737780)
Location: drivers/usb/dwc2/hcd.c:3209
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81737780-ffffffff81737a6e: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81777750)
Location: drivers/usb/dwc2/hcd.c:3326
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81777750-ffffffff81777a43: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179d510)
Location: drivers/usb/dwc2/hcd.c:3316
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8179d510-ffffffff8179d891: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817dc110)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff817dc110-ffffffff817dc491: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8180d030)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8180d030-ffffffff8180d3b1: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818de190)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818de190-ffffffff818de210: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e8000)
Location: drivers/usb/dwc2/hcd.c:3137
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818e8000-ffffffff818e8080: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c9ee0)
Location: drivers/usb/dwc2/hcd.c:3135
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818c9ee0-ffffffff818c9f63: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81962f85)
Location: drivers/usb/dwc2/hcd.c:3135
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81d1ba3d-ffffffff81d1ba85: dwc2_hcd_queue_transactions.cold (STB_LOCAL)
ffffffff81962e50-ffffffff81962f18: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81abd461)
Location: drivers/usb/dwc2/hcd.c:3131
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81ee6dba-ffffffff81ee6e1c: dwc2_hcd_queue_transactions.cold (STB_LOCAL)
ffffffff81abd320-ffffffff81abd3ea: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c46b31)
Location: drivers/usb/dwc2/hcd.c:3102
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff820a25c1-ffffffff820a2623: dwc2_hcd_queue_transactions.cold (STB_LOCAL)
ffffffff81c469e0-ffffffff81c46aaa: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81cae0f1)
Location: drivers/usb/dwc2/hcd.c:3102
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff82123b81-ffffffff82123be3: dwc2_hcd_queue_transactions.cold (STB_LOCAL)
ffffffff81cadfa0-ffffffff81cae06a: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81d62da1)
Location: drivers/usb/dwc2/hcd.c:3102
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff82205358-ffffffff822053ba: dwc2_hcd_queue_transactions.cold (STB_LOCAL)
ffffffff81d62c50-ffffffff81d62d1a: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a45928)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffff800010a45928-ffff800010a45d50: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b18160)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
c0b18160-c0b1851c: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b09580)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
c000000000b09580-c000000000b09e4c: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00066234e)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffe00066234e-ffffffe000662808: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c5410)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff817c5410-ffffffff817c5791: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81801eb0)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81801eb0-ffffffff81802231: dwc2_hcd_queue_transactions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_queue_transactions(struct dwc2_hsotg *hsotg, enum dwc2_transaction_type tr_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8181bfc0)
Location: drivers/usb/dwc2/hcd.c:3136
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8181bfc0-ffffffff8181c341: dwc2_hcd_queue_transactions (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
