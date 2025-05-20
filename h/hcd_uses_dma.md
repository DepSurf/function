# Function: <code>hcd_uses_dma</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817ed78a)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff817f885d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180d550)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff818bcd95)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff818c89bd)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/core/devio.c (ffffffff818cb68d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818de3a0)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff818c9a87)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff818d3b0d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/core/devio.c (ffffffff818d677d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e820d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff818acb08)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff818b706d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/core/devio.c (ffffffff818b9c0d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818ccf11)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff81941b59)
Location: include/linux/usb/hcd.h:429
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff8194cb4d)
Location: include/linux/usb/hcd.h:429
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/core/devio.c (ffffffff8194f89d)
Location: include/linux/usb/hcd.h:429
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81966ce9)
Location: include/linux/usb/hcd.h:429
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff81a9b188)
Location: include/linux/usb/hcd.h:432
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff81aa5721)
Location: include/linux/usb/hcd.h:432
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/core/devio.c (ffffffff81aaad85)
Location: include/linux/usb/hcd.h:432
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ac0e97)
Location: include/linux/usb/hcd.h:432
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff81c1ffd8)
Location: include/linux/usb/hcd.h:421
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff81c2c191)
Location: include/linux/usb/hcd.h:421
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/core/devio.c (ffffffff81c321d2)
Location: include/linux/usb/hcd.h:421
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c4aa8b)
Location: include/linux/usb/hcd.h:421
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff81c86f58)
Location: include/linux/usb/hcd.h:421
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff81c93314)
Location: include/linux/usb/hcd.h:421
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_alloc_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb2047)
Location: include/linux/usb/hcd.h:421
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff81d3b9b8)
Location: include/linux/usb/hcd.h:420
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff81d47dc4)
Location: include/linux/usb/hcd.h:420
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_alloc_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d66d57)
Location: include/linux/usb/hcd.h:420
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffff800010a1c810)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffff800010a295fc)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (c0af5790)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (c0aff560)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (c0b1866c)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (c000000000ad7ca0)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (c000000000ae5b50)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0a01c)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffe000641574)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffe00064b012)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000662918)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff817a5b6a)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff817b0c3d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c5930)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff8179809a)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff817a266d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
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
In drivers/usb/core/hcd.c (ffffffff817e260a)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff817ed6dd)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818023d0)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff817fd35a)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/buffer.c (ffffffff8180791d)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181c4e0)
Location: include/linux/usb/hcd.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
</details>
</li>
</ul>

## Differences
