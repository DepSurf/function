# Function: <code>dwc2_hcd_qtd_unlink_and_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81627c06)
Location: drivers/usb/dwc2/hcd.h:480
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
  - drivers/usb/dwc2/hcd.c:dwc2_qh_list_free
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162abe5)
Location: drivers/usb/dwc2/hcd.h:480
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162efbd)
Location: drivers/usb/dwc2/hcd.h:480
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff81687691)
Location: drivers/usb/dwc2/hcd.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_qh_list_free
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168acb1)
Location: drivers/usb/dwc2/hcd.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8169039c)
Location: drivers/usb/dwc2/hcd.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff816b58c1)
Location: drivers/usb/dwc2/hcd.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_qh_list_free
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816b8dd1)
Location: drivers/usb/dwc2/hcd.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816be44c)
Location: drivers/usb/dwc2/hcd.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff816c9bdc)
Location: drivers/usb/dwc2/hcd.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816cd127)
Location: drivers/usb/dwc2/hcd.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d2398)
Location: drivers/usb/dwc2/hcd.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff817360fc)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173971d)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173ea1d)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff8177478a)
Location: drivers/usb/dwc2/hcd.h:571
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81779e03)
Location: drivers/usb/dwc2/hcd.h:571
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177f4d8)
Location: drivers/usb/dwc2/hcd.h:571
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff8179a7da)
Location: drivers/usb/dwc2/hcd.h:571
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8179feb9)
Location: drivers/usb/dwc2/hcd.h:571
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a5cd8)
Location: drivers/usb/dwc2/hcd.h:571
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff817d8ce0)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817df047)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4e7e)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff81809b70)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8180ff37)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81815d3e)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff818de6a2)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e1245)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6ea1)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e850f)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818eaa95)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818eff61)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c75a1)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818cdfd7)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d3711)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8195ee61)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff819682b1)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196e211)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ab92c3)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81ac247c)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac88f3)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c42523)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81c4c19c)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c52ca3)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ca9af3)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81cb380a)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cba26c)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81d5e7a3)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81d6853a)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6efdc)
Location: drivers/usb/dwc2/hcd.h:550
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffff800010a40f00)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a49024)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4ee48)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (c0b13170)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1b42c)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b20f1c)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (c000000000b00fe0)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b0ec70)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b16964)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffe00065c338)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000665dbc)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066b548)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff817c1f50)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817c8317)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817ce11e)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817fe9f0)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81804db7)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8180abbe)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff81818b00)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_kill_urbs_in_qh_list
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8181eec7)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81824cce)
Location: drivers/usb/dwc2/hcd.h:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
</ul>

## Differences
