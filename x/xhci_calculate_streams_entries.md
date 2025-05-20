# Function: <code>xhci_calculate_streams_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81650769)
Location: drivers/usb/host/xhci.c:3035
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff816b1076)
Location: drivers/usb/host/xhci.c:3014
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff816df226)
Location: drivers/usb/host/xhci.c:3003
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff816f3a71)
Location: drivers/usb/host/xhci.c:2943
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff8175fd3d)
Location: drivers/usb/host/xhci.c:2959
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff817a06ec)
Location: drivers/usb/host/xhci.c:3154
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff817c69ac)
Location: drivers/usb/host/xhci.c:3171
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81805ddf)
Location: drivers/usb/host/xhci.c:3212
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81836c8f)
Location: drivers/usb/host/xhci.c:3282
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_calculate_streams_entries(struct xhci_hcd *xhci, unsigned int *num_streams, unsigned int *num_stream_ctxs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81903a30)
Location: drivers/usb/host/xhci.c:3286
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81903a30-ffffffff81903aa8: xhci_calculate_streams_entries (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81911bc9)
Location: drivers/usb/host/xhci.c:3420
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff818f51d4)
Location: drivers/usb/host/xhci.c:3347
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81992ebb)
Location: drivers/usb/host/xhci.c:3364
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81aef988)
Location: drivers/usb/host/xhci.c:3398
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81c7c6d8)
Location: drivers/usb/host/xhci.c:3396
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81ce3948)
Location: drivers/usb/host/xhci.c:3236
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81d98aa8)
Location: drivers/usb/host/xhci.c:3287
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffff800010a74b50)
Location: drivers/usb/host/xhci.c:3282
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (c0b485d4)
Location: drivers/usb/host/xhci.c:3282
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (c000000000b4ac88)
Location: drivers/usb/host/xhci.c:3282
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffe00068cc8a)
Location: drivers/usb/host/xhci.c:3282
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff817ef03f)
Location: drivers/usb/host/xhci.c:3282
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff817b414f)
Location: drivers/usb/host/xhci.c:3282
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff8182bb0f)
Location: drivers/usb/host/xhci.c:3282
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
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
In drivers/usb/host/xhci.c (ffffffff81845adf)
Location: drivers/usb/host/xhci.c:3282
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
