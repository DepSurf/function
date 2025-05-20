# Function: <code>xhci_decode_ctrl_ctx</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81819325)
Location: drivers/usb/host/xhci.h:2420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
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
In drivers/usb/host/xhci-trace.c (ffffffff8184a6c5)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *xhci_decode_ctrl_ctx(long unsigned int drop, long unsigned int add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff8191cfd0)
Location: drivers/usb/host/xhci.h:2434
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
**Symbols:**

```
ffffffff8191cfd0-ffffffff8191d14e: xhci_decode_ctrl_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *xhci_decode_ctrl_ctx(long unsigned int drop, long unsigned int add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81924630)
Location: drivers/usb/host/xhci.h:2449
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
**Symbols:**

```
ffffffff81924630-ffffffff819247ae: xhci_decode_ctrl_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *xhci_decode_ctrl_ctx(long unsigned int drop, long unsigned int add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81907f40)
Location: drivers/usb/host/xhci.h:2455
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
**Symbols:**

```
ffffffff81907f40-ffffffff819080c9: xhci_decode_ctrl_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *xhci_decode_ctrl_ctx(char *str, long unsigned int drop, long unsigned int add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff819a8770)
Location: drivers/usb/host/xhci.h:2464
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
**Symbols:**

```
ffffffff819a8770-ffffffff819a88e1: xhci_decode_ctrl_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *xhci_decode_ctrl_ctx(char *str, long unsigned int drop, long unsigned int add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81b07280)
Location: drivers/usb/host/xhci.h:2491
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
**Symbols:**

```
ffffffff81b07280-ffffffff81b07404: xhci_decode_ctrl_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *xhci_decode_ctrl_ctx(char *str, long unsigned int drop, long unsigned int add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81c96b20)
Location: drivers/usb/host/xhci.h:2492
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
**Symbols:**

```
ffffffff81c96b20-ffffffff81c96c9e: xhci_decode_ctrl_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *xhci_decode_ctrl_ctx(char *str, long unsigned int drop, long unsigned int add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81cfd8e0)
Location: drivers/usb/host/xhci.h:2502
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
**Symbols:**

```
ffffffff81cfd8e0-ffffffff81cfda5e: xhci_decode_ctrl_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *xhci_decode_ctrl_ctx(char *str, long unsigned int drop, long unsigned int add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81db3240)
Location: drivers/usb/host/xhci.h:2479
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
**Symbols:**

```
ffffffff81db3240-ffffffff81db33be: xhci_decode_ctrl_ctx (STB_LOCAL)
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
In drivers/usb/host/xhci-trace.c (ffff800010a88df0)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
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
In drivers/usb/host/xhci-trace.c (c0b5c5bc)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
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
In drivers/usb/host/xhci-trace.c (c000000000b64a3c)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
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
In drivers/usb/host/xhci-trace.c (ffffffe00069eaa6)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
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
In drivers/usb/host/xhci-trace.c (ffffffff81802a75)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
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
In drivers/usb/host/xhci-trace.c (ffffffff817c7c15)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
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
In drivers/usb/host/xhci-trace.c (ffffffff8183f545)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
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
In drivers/usb/host/xhci-trace.c (ffffffff81859a15)
Location: drivers/usb/host/xhci.h:2431
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *str</code>
</li>
<li>
<b>Param reordered. </b>
<code>drop, add</code> ➡️ <code>str, drop, add</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
