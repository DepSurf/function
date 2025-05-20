# Function: <code>xhci_urb_suitable_for_idt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81800cb5)
Location: drivers/usb/host/xhci.h:2173
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81810327)
Location: drivers/usb/host/xhci.h:2173
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff81831d65)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81841517)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff819043a5)
Location: drivers/usb/host/xhci.h:2186
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff819156f1)
Location: drivers/usb/host/xhci.h:2186
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff8190cc32)
Location: drivers/usb/host/xhci.h:2201
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191cce1)
Location: drivers/usb/host/xhci.h:2201
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff818f01a2)
Location: drivers/usb/host/xhci.h:2207
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81901155)
Location: drivers/usb/host/xhci.h:2207
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff8198ce42)
Location: drivers/usb/host/xhci.h:2214
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff819a0981)
Location: drivers/usb/host/xhci.h:2214
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff81ae9073)
Location: drivers/usb/host/xhci.h:2241
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afe1b3)
Location: drivers/usb/host/xhci.h:2241
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff81c75333)
Location: drivers/usb/host/xhci.h:2242
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8cf53)
Location: drivers/usb/host/xhci.h:2242
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff81cdc9f3)
Location: drivers/usb/host/xhci.h:2252
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cf3ad3)
Location: drivers/usb/host/xhci.h:2252
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff81d91a13)
Location: drivers/usb/host/xhci.h:2229
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da9413)
Location: drivers/usb/host/xhci.h:2229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffff800010a6e25c)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a8025c)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (c0b428a4)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (c0b53558)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (c000000000b42880)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (c000000000b58f44)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffe000687784)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffe0006969ea)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff817ea145)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f98c7)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817af255)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bea67)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81826be5)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81836397)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff81840ac5)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8185078e)
Location: drivers/usb/host/xhci.h:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
</ul>

## Differences
