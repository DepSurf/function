# Function: <code>dwc2_hcd_qh_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8162dcb0)
Location: drivers/usb/dwc2/hcd_queue.c:625
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_qh_list_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8162dcb0-ffffffff8162dd72: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168e6e0)
Location: drivers/usb/dwc2/hcd_queue.c:1693
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_qh_list_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8168e6e0-ffffffff8168e7eb: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bc7a0)
Location: drivers/usb/dwc2/hcd_queue.c:1696
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_qh_list_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff816bc7a0-ffffffff816bc8a8: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816d0810)
Location: drivers/usb/dwc2/hcd_queue.c:1692
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff816d0810-ffffffff816d08fb: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173ce60)
Location: drivers/usb/dwc2/hcd_queue.c:1692
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8173ce60-ffffffff8173cf4e: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177d7f0)
Location: drivers/usb/dwc2/hcd_queue.c:1766
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8177d7f0-ffffffff8177d8f2: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a3da0)
Location: drivers/usb/dwc2/hcd_queue.c:1771
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff817a3da0-ffffffff817a3ec4: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e2fa9)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff817e343d-ffffffff817e3450: dwc2_hcd_qh_unlink.cold (STB_LOCAL)
ffffffff817e2ed0-ffffffff817e2ff3: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81813dd0)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81813dd0-ffffffff81813efa: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e4e70)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818e4e70-ffffffff818e4f9a: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ee340)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818ee340-ffffffff818ee46a: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1b40)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818d1b40-ffffffff818d1c6d: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81d1e1aa-ffffffff81d1e206: dwc2_hcd_qh_unlink.cold (STB_LOCAL)
ffffffff8196c510-ffffffff8196c684: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81ee9bf1-ffffffff81ee9c67: dwc2_hcd_qh_unlink.cold (STB_LOCAL)
ffffffff81ac69a0-ffffffff81ac6b08: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1743
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff820a4d71-ffffffff820a4de7: dwc2_hcd_qh_unlink.cold (STB_LOCAL)
ffffffff81c50b50-ffffffff81c50cb8: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1743
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff821262a5-ffffffff8212631b: dwc2_hcd_qh_unlink.cold (STB_LOCAL)
ffffffff81cb80d0-ffffffff81cb8238: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1743
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff82207aae-ffffffff82207b24: dwc2_hcd_qh_unlink.cold (STB_LOCAL)
ffffffff81d6ce40-ffffffff81d6cfa8: dwc2_hcd_qh_unlink (STB_GLOBAL)
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
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4cfe8)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffff800010a4cfe8-ffff800010a4d12c: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c0b1f1a8)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
c0b1f1a8-c0b1f2f8: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c000000000b14410)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
c000000000b14410-c000000000b145f8: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000669a8c)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffe000669a8c-ffffffe000669be8: dwc2_hcd_qh_unlink (STB_GLOBAL)
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
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cc1b0)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff817cc1b0-ffffffff817cc2da: dwc2_hcd_qh_unlink (STB_GLOBAL)
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
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81808c50)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81808c50-ffffffff81808d7a: dwc2_hcd_qh_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hcd_qh_unlink(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81822d60)
Location: drivers/usb/dwc2/hcd_queue.c:1773
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81822d60-ffffffff81822e8a: dwc2_hcd_qh_unlink (STB_GLOBAL)
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
