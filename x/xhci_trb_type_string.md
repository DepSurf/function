# Function: <code>xhci_trb_type_string</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (0)
Location: drivers/usb/host/xhci.h:1391
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
In drivers/usb/host/xhci-trace.c (0)
Location: drivers/usb/host/xhci.h:1393
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:1393
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
In drivers/usb/host/xhci-trace.c (ffffffff817b164c)
Location: drivers/usb/host/xhci.h:1399
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b58ec)
Location: drivers/usb/host/xhci.h:1399
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
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
In drivers/usb/host/xhci-trace.c (ffffffff817d7de7)
Location: drivers/usb/host/xhci.h:1407
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dc037)
Location: drivers/usb/host/xhci.h:1407
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
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
In drivers/usb/host/xhci-trace.c (ffffffff8181822b)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181d564)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
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
In drivers/usb/host/xhci-trace.c (ffffffff818494ab)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e93a)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8191bceb)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8192079b)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
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
In drivers/usb/host/xhci-trace.c (ffffffff8192335b)
Location: drivers/usb/host/xhci.h:1424
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81927d4b)
Location: drivers/usb/host/xhci.h:1424
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
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
In drivers/usb/host/xhci-trace.c (ffffffff81906a4e)
Location: drivers/usb/host/xhci.h:1428
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190b3ce)
Location: drivers/usb/host/xhci.h:1428
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_trb
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
In drivers/usb/host/xhci-trace.c (ffffffff819a7e2f)
Location: drivers/usb/host/xhci.h:1431
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ac8af)
Location: drivers/usb/host/xhci.h:1431
Inline: True
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
In drivers/usb/host/xhci-trace.c (ffffffff81b0695f)
Location: drivers/usb/host/xhci.h:1432
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0af3f)
Location: drivers/usb/host/xhci.h:1432
Inline: True
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
In drivers/usb/host/xhci-trace.c (ffffffff81c9614f)
Location: drivers/usb/host/xhci.h:1433
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9ae8f)
Location: drivers/usb/host/xhci.h:1433
Inline: True
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
In drivers/usb/host/xhci-trace.c (ffffffff81cfc9d5)
Location: drivers/usb/host/xhci.h:1436
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d02325)
Location: drivers/usb/host/xhci.h:1436
Inline: True
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
In drivers/usb/host/xhci-trace.c (ffffffff81db23a5)
Location: drivers/usb/host/xhci.h:1411
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db7e55)
Location: drivers/usb/host/xhci.h:1411
Inline: True
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
In drivers/usb/host/xhci-trace.c (ffff800010a87c68)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8ee38)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
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
In drivers/usb/host/xhci-trace.c (c0b5b4b8)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (c0b60ce4)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
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
In drivers/usb/host/xhci-trace.c (c000000000b6311c)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6a928)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
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
In drivers/usb/host/xhci-trace.c (0)
Location: drivers/usb/host/xhci.h:1420
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:1420
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
In drivers/usb/host/xhci-trace.c (ffffffff8180185b)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8180470a)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
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
In drivers/usb/host/xhci-trace.c (ffffffff817c69fb)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cbe8a)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8183e32b)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818437ba)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
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
In drivers/usb/host/xhci-trace.c (ffffffff818587fb)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185dd1a)
Location: drivers/usb/host/xhci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
</ul>

## Differences
