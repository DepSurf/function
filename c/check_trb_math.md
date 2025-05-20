# Function: <code>check_trb_math</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void check_trb_math(struct urb *urb, int num_trbs, int running_total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81656e10)
Location: drivers/usb/host/xhci-ring.c:2973
Inline: False
```
**Symbols:**

```
ffffffff81656e10-ffffffff81656e9c: check_trb_math (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff816b92e8)
Location: drivers/usb/host/xhci-ring.c:3009
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff816e7568)
Location: drivers/usb/host/xhci-ring.c:2910
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff816fb6a6)
Location: drivers/usb/host/xhci-ring.c:3010
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff81768217)
Location: drivers/usb/host/xhci-ring.c:3014
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff817a94d6)
Location: drivers/usb/host/xhci-ring.c:2933
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff817cf45b)
Location: drivers/usb/host/xhci-ring.c:2997
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff8180f832)
Location: drivers/usb/host/xhci-ring.c:3043
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff8184093f)
Location: drivers/usb/host/xhci-ring.c:3070
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff8191525c)
Location: drivers/usb/host/xhci-ring.c:3116
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff8191c82c)
Location: drivers/usb/host/xhci-ring.c:3126
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff81900c68)
Location: drivers/usb/host/xhci-ring.c:3315
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff819a041c)
Location: drivers/usb/host/xhci-ring.c:3385
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff81afdb52)
Location: drivers/usb/host/xhci-ring.c:3320
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8c8cd)
Location: drivers/usb/host/xhci-ring.c:3327
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf3442)
Location: drivers/usb/host/xhci-ring.c:3347
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da8d82)
Location: drivers/usb/host/xhci-ring.c:3390
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffff800010a7f738)
Location: drivers/usb/host/xhci-ring.c:3070
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (c0b52b10)
Location: drivers/usb/host/xhci-ring.c:3070
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (c000000000b584f8)
Location: drivers/usb/host/xhci-ring.c:3070
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffe0006963ba)
Location: drivers/usb/host/xhci-ring.c:3070
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff817f8cef)
Location: drivers/usb/host/xhci-ring.c:3070
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff817bde8f)
Location: drivers/usb/host/xhci-ring.c:3070
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff818357bf)
Location: drivers/usb/host/xhci-ring.c:3070
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci-ring.c (ffffffff8184faf5)
Location: drivers/usb/host/xhci-ring.c:3070
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
