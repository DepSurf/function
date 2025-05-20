# Function: <code>xhci_ep_state_string</code>

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
Location: drivers/usb/host/xhci.h:2395
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
Location: drivers/usb/host/xhci.h:2500
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:2500
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
In drivers/usb/host/xhci-trace.c (ffffffff817b1f0f)
Location: drivers/usb/host/xhci.h:2512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b668d)
Location: drivers/usb/host/xhci.h:2512
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
In drivers/usb/host/xhci-trace.c (ffffffff817d854f)
Location: drivers/usb/host/xhci.h:2520
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dcc7d)
Location: drivers/usb/host/xhci.h:2520
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
In drivers/usb/host/xhci-trace.c (ffffffff81818b7d)
Location: drivers/usb/host/xhci.h:2582
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181ce30)
Location: drivers/usb/host/xhci.h:2582
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
In drivers/usb/host/xhci-trace.c (ffffffff81849e0d)
Location: drivers/usb/host/xhci.h:2593
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e1f0)
Location: drivers/usb/host/xhci.h:2593
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
In drivers/usb/host/xhci-trace.c (ffffffff8191c64d)
Location: drivers/usb/host/xhci.h:2654
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819216e1)
Location: drivers/usb/host/xhci.h:2654
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
In drivers/usb/host/xhci-trace.c (ffffffff81923cbd)
Location: drivers/usb/host/xhci.h:2669
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81928d31)
Location: drivers/usb/host/xhci.h:2669
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
In drivers/usb/host/xhci-trace.c (ffffffff819073bf)
Location: drivers/usb/host/xhci.h:2675
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c3be)
Location: drivers/usb/host/xhci.h:2675
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
In drivers/usb/host/xhci-trace.c (ffffffff819a7a32)
Location: drivers/usb/host/xhci.h:2679
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ac34a)
Location: drivers/usb/host/xhci.h:2679
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
In drivers/usb/host/xhci-trace.c (ffffffff81b062ee)
Location: drivers/usb/host/xhci.h:2711
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0a8b5)
Location: drivers/usb/host/xhci.h:2711
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
In drivers/usb/host/xhci-trace.c (ffffffff81c9571e)
Location: drivers/usb/host/xhci.h:2712
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9a7d5)
Location: drivers/usb/host/xhci.h:2712
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
In drivers/usb/host/xhci-trace.c (ffffffff81cfbe7e)
Location: drivers/usb/host/xhci.h:2722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d01b91)
Location: drivers/usb/host/xhci.h:2722
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
In drivers/usb/host/xhci-trace.c (ffffffff81db17fe)
Location: drivers/usb/host/xhci.h:2699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db7211)
Location: drivers/usb/host/xhci.h:2699
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
In drivers/usb/host/xhci-trace.c (ffff800010a88520)
Location: drivers/usb/host/xhci.h:2593
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8ea60)
Location: drivers/usb/host/xhci.h:2593
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
In drivers/usb/host/xhci-trace.c (c0b5bd20)
Location: drivers/usb/host/xhci.h:2593
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61a98)
Location: drivers/usb/host/xhci.h:2593
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
In drivers/usb/host/xhci-trace.c (c000000000b63e34)
Location: drivers/usb/host/xhci.h:2593
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6a0d8)
Location: drivers/usb/host/xhci.h:2593
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
In drivers/usb/host/xhci-trace.c (0)
Location: drivers/usb/host/xhci.h:2593
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:2593
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
In drivers/usb/host/xhci-trace.c (ffffffff818021bd)
Location: drivers/usb/host/xhci.h:2593
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81803fc0)
Location: drivers/usb/host/xhci.h:2593
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
In drivers/usb/host/xhci-trace.c (ffffffff817c735d)
Location: drivers/usb/host/xhci.h:2593
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cb740)
Location: drivers/usb/host/xhci.h:2593
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
In drivers/usb/host/xhci-trace.c (ffffffff8183ec8d)
Location: drivers/usb/host/xhci.h:2593
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81843070)
Location: drivers/usb/host/xhci.h:2593
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
In drivers/usb/host/xhci-trace.c (ffffffff8185915d)
Location: drivers/usb/host/xhci.h:2593
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185d5d0)
Location: drivers/usb/host/xhci.h:2593
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
</details>
</li>
</ul>

## Differences
