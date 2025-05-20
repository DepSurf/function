# Function: <code>xhci_ep_type_string</code>

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
Location: drivers/usb/host/xhci.h:2413
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
Location: drivers/usb/host/xhci.h:2518
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:2518
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
In drivers/usb/host/xhci-trace.c (ffffffff817b1f8c)
Location: drivers/usb/host/xhci.h:2530
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b6713)
Location: drivers/usb/host/xhci.h:2530
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
In drivers/usb/host/xhci-trace.c (ffffffff817d85cc)
Location: drivers/usb/host/xhci.h:2538
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dcd03)
Location: drivers/usb/host/xhci.h:2538
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
In drivers/usb/host/xhci-trace.c (ffffffff81818bfd)
Location: drivers/usb/host/xhci.h:2600
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181cebf)
Location: drivers/usb/host/xhci.h:2600
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
In drivers/usb/host/xhci-trace.c (ffffffff81849e8d)
Location: drivers/usb/host/xhci.h:2611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e27f)
Location: drivers/usb/host/xhci.h:2611
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
In drivers/usb/host/xhci-trace.c (ffffffff8191c6cd)
Location: drivers/usb/host/xhci.h:2672
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81921770)
Location: drivers/usb/host/xhci.h:2672
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
In drivers/usb/host/xhci-trace.c (ffffffff81923d3d)
Location: drivers/usb/host/xhci.h:2687
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81928dc0)
Location: drivers/usb/host/xhci.h:2687
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
In drivers/usb/host/xhci-trace.c (ffffffff8190743b)
Location: drivers/usb/host/xhci.h:2693
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c449)
Location: drivers/usb/host/xhci.h:2693
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
In drivers/usb/host/xhci-trace.c (ffffffff819a7ac6)
Location: drivers/usb/host/xhci.h:2697
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ac404)
Location: drivers/usb/host/xhci.h:2697
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
In drivers/usb/host/xhci-trace.c (ffffffff81b0636e)
Location: drivers/usb/host/xhci.h:2729
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0a948)
Location: drivers/usb/host/xhci.h:2729
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
In drivers/usb/host/xhci-trace.c (ffffffff81c9579e)
Location: drivers/usb/host/xhci.h:2730
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9a868)
Location: drivers/usb/host/xhci.h:2730
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
In drivers/usb/host/xhci-trace.c (ffffffff81cfbf09)
Location: drivers/usb/host/xhci.h:2740
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d01c24)
Location: drivers/usb/host/xhci.h:2740
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
In drivers/usb/host/xhci-trace.c (ffffffff81db1889)
Location: drivers/usb/host/xhci.h:2717
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db72a4)
Location: drivers/usb/host/xhci.h:2717
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
In drivers/usb/host/xhci-trace.c (ffff800010a885b8)
Location: drivers/usb/host/xhci.h:2611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8e970)
Location: drivers/usb/host/xhci.h:2611
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
In drivers/usb/host/xhci-trace.c (c0b5bd98)
Location: drivers/usb/host/xhci.h:2611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61b34)
Location: drivers/usb/host/xhci.h:2611
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
In drivers/usb/host/xhci-trace.c (c000000000b63ec4)
Location: drivers/usb/host/xhci.h:2611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6a160)
Location: drivers/usb/host/xhci.h:2611
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
Location: drivers/usb/host/xhci.h:2611
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:2611
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
In drivers/usb/host/xhci-trace.c (ffffffff8180223d)
Location: drivers/usb/host/xhci.h:2611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8180404f)
Location: drivers/usb/host/xhci.h:2611
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
In drivers/usb/host/xhci-trace.c (ffffffff817c73dd)
Location: drivers/usb/host/xhci.h:2611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cb7cf)
Location: drivers/usb/host/xhci.h:2611
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
In drivers/usb/host/xhci-trace.c (ffffffff8183ed0d)
Location: drivers/usb/host/xhci.h:2611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818430ff)
Location: drivers/usb/host/xhci.h:2611
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
In drivers/usb/host/xhci-trace.c (ffffffff818591dd)
Location: drivers/usb/host/xhci.h:2611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185d65f)
Location: drivers/usb/host/xhci.h:2611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show
```
</details>
</li>
</ul>

## Differences
