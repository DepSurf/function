# Function: <code>dwc2_frame_num_inc</code>

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
In drivers/usb/dwc2/hcd_queue.c (ffffffff8162ddcc)
Location: drivers/usb/dwc2/hcd.h:562
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e484)
Location: drivers/usb/dwc2/hcd.h:562
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff8168853e)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168c0d8)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168e85a)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168eac4)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff816b675e)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816ba1d8)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bc91a)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bcb84)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff816caabe)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816ce47c)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816d097c)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d0be4)
Location: drivers/usb/dwc2/hcd.h:645
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff8173700e)
Location: drivers/usb/dwc2/hcd.h:646
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173aa9c)
Location: drivers/usb/dwc2/hcd.h:646
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173cfcc)
Location: drivers/usb/dwc2/hcd.h:646
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173d234)
Location: drivers/usb/dwc2/hcd.h:646
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff81776fd8)
Location: drivers/usb/dwc2/hcd.h:667
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177b19f)
Location: drivers/usb/dwc2/hcd.h:667
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177d95c)
Location: drivers/usb/dwc2/hcd.h:667
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177dbe4)
Location: drivers/usb/dwc2/hcd.h:667
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff8179cc9c)
Location: drivers/usb/dwc2/hcd.h:667
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a141a)
Location: drivers/usb/dwc2/hcd.h:667
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a3f2e)
Location: drivers/usb/dwc2/hcd.h:667
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a41c4)
Location: drivers/usb/dwc2/hcd.h:667
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff817db86c)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e03c3)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e3067)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e34a4)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff8180c78c)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818112b3)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81813f67)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814284)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff818dd552)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e26d4)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e5009)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6cc1)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff818e73a2)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818ebf34)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ee4d9)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818efd81)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff818c928b)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818cf6c4)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1cd9)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d3531)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff81961eef)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81969ac7)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196c6f9)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196e040)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff81abc36f)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81ac3d3c)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac6b72)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac867f)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff81c4599f)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81c4dc6c)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50d32)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c52a1f)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff81cacf6f)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81cb52cc)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb82a9)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb9fdf)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffffffff81d61c1f)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81d69ffc)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6d019)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6ed4f)
Location: drivers/usb/dwc2/hcd.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd.c (ffff800010a44ffc)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4a4e4)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4d1a4)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4d4d8)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
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
In drivers/usb/dwc2/hcd.c (c0b177a8)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1c788)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1f360)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b1f5d0)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_calc_starting_frame
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_calc_starting_frame
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
In drivers/usb/dwc2/hcd.c (c000000000b08574)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b10624)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b146cc)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b149ec)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffe0006618e6)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe00066726a)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000669c76)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe000669f20)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff817c4b6c)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817c9693)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cc347)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cc664)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff8180160c)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81806133)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81808de7)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809104)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff8181b71c)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81820243)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81822ef7)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_pick_first_frame
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823214)
Location: drivers/usb/dwc2/hcd.h:668
Inline: True
```
</details>
</li>
</ul>

## Differences
