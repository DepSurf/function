# Function: <code>xhci_portsc_link_state_string</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81771dcf)
Location: drivers/usb/host/xhci.h:2419
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
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
In drivers/usb/host/xhci-trace.c (ffffffff817b2226)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b608e)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (ffffffff817d8866)
Location: drivers/usb/host/xhci.h:2439
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dc67e)
Location: drivers/usb/host/xhci.h:2439
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81818e91)
Location: drivers/usb/host/xhci.h:2501
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181c807)
Location: drivers/usb/host/xhci.h:2501
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8184a121)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184dbc7)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8191c930)
Location: drivers/usb/host/xhci.h:2515
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81921080)
Location: drivers/usb/host/xhci.h:2515
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_portsc
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
In drivers/usb/host/xhci-trace.c (ffffffff81923fa0)
Location: drivers/usb/host/xhci.h:2530
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81928630)
Location: drivers/usb/host/xhci.h:2530
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_portsc
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
In drivers/usb/host/xhci-trace.c (ffffffff81907690)
Location: drivers/usb/host/xhci.h:2536
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190bcc0)
Location: drivers/usb/host/xhci.h:2536
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_portsc
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
In drivers/usb/host/xhci-trace.c (ffffffff819a7324)
Location: drivers/usb/host/xhci.h:2543
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819abc44)
Location: drivers/usb/host/xhci.h:2543
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_portsc
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
In drivers/usb/host/xhci-trace.c (ffffffff81b05c84)
Location: drivers/usb/host/xhci.h:2572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0a284)
Location: drivers/usb/host/xhci.h:2572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_portsc
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
In drivers/usb/host/xhci-trace.c (ffffffff81c95084)
Location: drivers/usb/host/xhci.h:2573
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9a184)
Location: drivers/usb/host/xhci.h:2573
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_portsc
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
In drivers/usb/host/xhci-trace.c (ffffffff81cfb7b4)
Location: drivers/usb/host/xhci.h:2583
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d01544)
Location: drivers/usb/host/xhci.h:2583
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_portsc
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
In drivers/usb/host/xhci-trace.c (ffffffff81db1124)
Location: drivers/usb/host/xhci.h:2560
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db7384)
Location: drivers/usb/host/xhci.h:2560
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_decode_portsc
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
In drivers/usb/host/xhci-trace.c (ffff800010a888b4)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8f6b4)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (c0b5c04c)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61454)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (c000000000b642f0)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6b3c4)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (ffffffe00069e434)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a1cee)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (ffffffff818024d1)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81803997)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (ffffffff817c7671)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cb117)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8183efa1)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81842a47)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81859471)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185cfa7)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
</details>
</li>
</ul>

## Differences
