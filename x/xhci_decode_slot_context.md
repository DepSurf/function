# Function: <code>xhci_decode_slot_context</code>

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
In drivers/usb/host/xhci-trace.c (ffffffff81704c29)
Location: drivers/usb/host/xhci.h:2344
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
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
In drivers/usb/host/xhci-trace.c (ffffffff81771c29)
Location: drivers/usb/host/xhci.h:2367
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817755df)
Location: drivers/usb/host/xhci.h:2367
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff817b2069)
Location: drivers/usb/host/xhci.h:2379
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b681a)
Location: drivers/usb/host/xhci.h:2379
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff817d86a9)
Location: drivers/usb/host/xhci.h:2387
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dce0a)
Location: drivers/usb/host/xhci.h:2387
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81818cd7)
Location: drivers/usb/host/xhci.h:2449
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181cfb8)
Location: drivers/usb/host/xhci.h:2449
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81849f67)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e378)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8191c7a7)
Location: drivers/usb/host/xhci.h:2463
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8192187a)
Location: drivers/usb/host/xhci.h:2463
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81923e2d)
Location: drivers/usb/host/xhci.h:2478
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81928eca)
Location: drivers/usb/host/xhci.h:2478
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8190751d)
Location: drivers/usb/host/xhci.h:2484
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c55b)
Location: drivers/usb/host/xhci.h:2484
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff819a71bb)
Location: drivers/usb/host/xhci.h:2492
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ac53f)
Location: drivers/usb/host/xhci.h:2492
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81b05b03)
Location: drivers/usb/host/xhci.h:2521
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0aaaf)
Location: drivers/usb/host/xhci.h:2521
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81c94ef3)
Location: drivers/usb/host/xhci.h:2522
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9a9df)
Location: drivers/usb/host/xhci.h:2522
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81cfb610)
Location: drivers/usb/host/xhci.h:2532
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d01d9f)
Location: drivers/usb/host/xhci.h:2532
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81db0f80)
Location: drivers/usb/host/xhci.h:2509
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db78cf)
Location: drivers/usb/host/xhci.h:2509
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffff800010a886c0)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8eb18)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (c0b5be64)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61c3c)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (c000000000b6407c)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6a2e4)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffe00069e244)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a254a)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff81802317)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81804148)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff817c74b7)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cb8c8)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff8183ede7)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818431f8)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
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
In drivers/usb/host/xhci-trace.c (ffffffff818592b7)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185d758)
Location: drivers/usb/host/xhci.h:2460
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
</details>
</li>
</ul>

## Differences
