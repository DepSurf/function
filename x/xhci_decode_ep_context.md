# Function: <code>xhci_decode_ep_context</code>

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
In drivers/usb/host/xhci-trace.c (ffffffff81704a87)
Location: drivers/usb/host/xhci.h:2435
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
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
In drivers/usb/host/xhci-trace.c (ffffffff81771a41)
Location: drivers/usb/host/xhci.h:2540
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817753a6)
Location: drivers/usb/host/xhci.h:2540
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff817b1e7c)
Location: drivers/usb/host/xhci.h:2552
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b6615)
Location: drivers/usb/host/xhci.h:2552
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff817d84bc)
Location: drivers/usb/host/xhci.h:2560
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dcc05)
Location: drivers/usb/host/xhci.h:2560
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81818b09)
Location: drivers/usb/host/xhci.h:2622
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181cdb2)
Location: drivers/usb/host/xhci.h:2622
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81849d99)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e172)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8191c5d9)
Location: drivers/usb/host/xhci.h:2694
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8192165c)
Location: drivers/usb/host/xhci.h:2694
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81923c49)
Location: drivers/usb/host/xhci.h:2709
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81928cb0)
Location: drivers/usb/host/xhci.h:2709
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81907345)
Location: drivers/usb/host/xhci.h:2715
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c340)
Location: drivers/usb/host/xhci.h:2715
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff819a79d3)
Location: drivers/usb/host/xhci.h:2719
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ac2d5)
Location: drivers/usb/host/xhci.h:2719
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81b0628a)
Location: drivers/usb/host/xhci.h:2751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0a82c)
Location: drivers/usb/host/xhci.h:2751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81c956ba)
Location: drivers/usb/host/xhci.h:2752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9a74c)
Location: drivers/usb/host/xhci.h:2752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81cfbe17)
Location: drivers/usb/host/xhci.h:2762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d01b09)
Location: drivers/usb/host/xhci.h:2762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81db1797)
Location: drivers/usb/host/xhci.h:2739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db7189)
Location: drivers/usb/host/xhci.h:2739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffff800010a884e8)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8ea24)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (c0b5bc94)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61a4c)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (c000000000b63de0)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6a088)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffe00069e072)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a2320)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81802149)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81803f42)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff817c72e9)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cb6c2)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8183ec19)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81842ff2)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff818590e9)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185d552)
Location: drivers/usb/host/xhci.h:2633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
</details>
</li>
</ul>

## Differences
