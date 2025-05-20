# Function: <code>xhci_slot_state_string</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (0)
Location: drivers/usb/host/xhci.h:2109
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: drivers/usb/host/xhci.h:2109
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
In drivers/usb/host/xhci-dbg.c (0)
Location: drivers/usb/host/xhci.h:2132
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: drivers/usb/host/xhci.h:2132
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:2132
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
In drivers/usb/host/xhci-dbg.c (ffffffff817b05cb)
Location: drivers/usb/host/xhci.h:2144
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817b2122)
Location: drivers/usb/host/xhci.h:2144
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b68c9)
Location: drivers/usb/host/xhci.h:2144
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
In drivers/usb/host/xhci-dbg.c (ffffffff817d6b4b)
Location: drivers/usb/host/xhci.h:2152
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817d8762)
Location: drivers/usb/host/xhci.h:2152
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dceb9)
Location: drivers/usb/host/xhci.h:2152
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
In drivers/usb/host/xhci-dbg.c (ffffffff818170fd)
Location: drivers/usb/host/xhci.h:2185
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81818d87)
Location: drivers/usb/host/xhci.h:2185
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181d061)
Location: drivers/usb/host/xhci.h:2185
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
In drivers/usb/host/xhci-dbg.c (ffffffff8184843d)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8184a017)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e421)
Location: drivers/usb/host/xhci.h:2195
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
In drivers/usb/host/xhci-dbg.c (ffffffff8191ab2d)
Location: drivers/usb/host/xhci.h:2198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8191c857)
Location: drivers/usb/host/xhci.h:2198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81921910)
Location: drivers/usb/host/xhci.h:2198
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
In drivers/usb/host/xhci-dbg.c (ffffffff8192137d)
Location: drivers/usb/host/xhci.h:2213
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81923ec7)
Location: drivers/usb/host/xhci.h:2213
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81928f60)
Location: drivers/usb/host/xhci.h:2213
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
In drivers/usb/host/xhci-dbg.c (ffffffff81904a8d)
Location: drivers/usb/host/xhci.h:2219
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819075b7)
Location: drivers/usb/host/xhci.h:2219
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c5f1)
Location: drivers/usb/host/xhci.h:2219
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
In drivers/usb/host/xhci-dbg.c (ffffffff819a528d)
Location: drivers/usb/host/xhci.h:2226
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819a7243)
Location: drivers/usb/host/xhci.h:2226
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ac5d5)
Location: drivers/usb/host/xhci.h:2226
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
In drivers/usb/host/xhci-dbg.c (ffffffff81b02c8d)
Location: drivers/usb/host/xhci.h:2253
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81b05b8b)
Location: drivers/usb/host/xhci.h:2253
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0ab4b)
Location: drivers/usb/host/xhci.h:2253
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
In drivers/usb/host/xhci-dbg.c (ffffffff81c91d4d)
Location: drivers/usb/host/xhci.h:2254
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81c94f7b)
Location: drivers/usb/host/xhci.h:2254
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9aa7b)
Location: drivers/usb/host/xhci.h:2254
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
In drivers/usb/host/xhci-dbg.c (ffffffff81cf843d)
Location: drivers/usb/host/xhci.h:2264
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81cfb6b5)
Location: drivers/usb/host/xhci.h:2264
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d01e3d)
Location: drivers/usb/host/xhci.h:2264
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
In drivers/usb/host/xhci-dbg.c (ffffffff81dadd6d)
Location: drivers/usb/host/xhci.h:2241
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81db1025)
Location: drivers/usb/host/xhci.h:2241
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db796d)
Location: drivers/usb/host/xhci.h:2241
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
In drivers/usb/host/xhci-dbg.c (ffff800010a87630)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffff800010a88758)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8ebb0)
Location: drivers/usb/host/xhci.h:2195
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
In drivers/usb/host/xhci-dbg.c (c0b5a2e4)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (c0b5bf1c)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61cf4)
Location: drivers/usb/host/xhci.h:2195
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
In drivers/usb/host/xhci-dbg.c (c000000000b6180c)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (c000000000b6413c)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6a3b8)
Location: drivers/usb/host/xhci.h:2195
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
In drivers/usb/host/xhci-dbg.c (0)
Location: drivers/usb/host/xhci.h:2195
Inline: True
```
```
In drivers/usb/host/xhci-trace.c (0)
Location: drivers/usb/host/xhci.h:2195
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci.h:2195
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
In drivers/usb/host/xhci-dbg.c (ffffffff818007ed)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff818023c7)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818041f1)
Location: drivers/usb/host/xhci.h:2195
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
In drivers/usb/host/xhci-dbg.c (ffffffff817c598d)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff817c7567)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cb971)
Location: drivers/usb/host/xhci.h:2195
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
In drivers/usb/host/xhci-dbg.c (ffffffff8183d2bd)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff8183ee97)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818432a1)
Location: drivers/usb/host/xhci.h:2195
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
In drivers/usb/host/xhci-dbg.c (ffffffff8185778d)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81859367)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185d801)
Location: drivers/usb/host/xhci.h:2195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
</details>
</li>
</ul>

## Differences
