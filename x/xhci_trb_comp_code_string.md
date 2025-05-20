# Function: <code>xhci_trb_comp_code_string</code>

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
Location: drivers/usb/host/xhci.h:1098
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
Location: drivers/usb/host/xhci.h:1100
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:1100
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
Location: drivers/usb/host/xhci.h:1106
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b58ec)
Location: drivers/usb/host/xhci.h:1106
Inline: True
Inline callers:
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
Location: drivers/usb/host/xhci.h:1114
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dc037)
Location: drivers/usb/host/xhci.h:1114
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (ffffffff8181849c)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181d78c)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (ffffffff8184971c)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184eb62)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (ffffffff8191bf5b)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81920a0b)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (ffffffff819235cb)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81927fbb)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (ffffffff81906cce)
Location: drivers/usb/host/xhci.h:1129
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190b64e)
Location: drivers/usb/host/xhci.h:1129
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (ffffffff819a80b1)
Location: drivers/usb/host/xhci.h:1132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819acb31)
Location: drivers/usb/host/xhci.h:1132
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
In drivers/usb/host/xhci-trace.c (ffffffff81b06a42)
Location: drivers/usb/host/xhci.h:1133
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0b022)
Location: drivers/usb/host/xhci.h:1133
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
In drivers/usb/host/xhci.c (ffffffff81c7d925)
Location: drivers/usb/host/xhci.h:1134
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81c96232)
Location: drivers/usb/host/xhci.h:1134
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9af72)
Location: drivers/usb/host/xhci.h:1134
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
In drivers/usb/host/xhci.c (ffffffff81ce4b95)
Location: drivers/usb/host/xhci.h:1137
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81cfc9d5)
Location: drivers/usb/host/xhci.h:1137
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d02325)
Location: drivers/usb/host/xhci.h:1137
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
In drivers/usb/host/xhci.c (ffffffff81d99c05)
Location: drivers/usb/host/xhci.h:1112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81db23a5)
Location: drivers/usb/host/xhci.h:1112
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db7e55)
Location: drivers/usb/host/xhci.h:1112
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
In drivers/usb/host/xhci-trace.c (ffff800010a87cc4)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8eee0)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (c0b5b45c)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (c0b60c90)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (c000000000b630ec)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6a8fc)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
Location: drivers/usb/host/xhci.h:1125
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:1125
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
In drivers/usb/host/xhci-trace.c (ffffffff81801acc)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81804932)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (ffffffff817c6c6c)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cc0b2)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (ffffffff8183e59c)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818439e2)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
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
In drivers/usb/host/xhci-trace.c (ffffffff81858a6c)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185df42)
Location: drivers/usb/host/xhci.h:1125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
</ul>

## Differences
