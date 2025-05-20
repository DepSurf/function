# Function: <code>xhci_decode_portsc</code>

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
Location: drivers/usb/host/xhci.h:2454
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
In drivers/usb/host/xhci-trace.c (ffffffff817b2210)
Location: drivers/usb/host/xhci.h:2466
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b6078)
Location: drivers/usb/host/xhci.h:2466
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
In drivers/usb/host/xhci-trace.c (ffffffff817d8850)
Location: drivers/usb/host/xhci.h:2474
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dc668)
Location: drivers/usb/host/xhci.h:2474
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
In drivers/usb/host/xhci-trace.c (ffffffff81818e80)
Location: drivers/usb/host/xhci.h:2536
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181c7f8)
Location: drivers/usb/host/xhci.h:2536
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
In drivers/usb/host/xhci-trace.c (ffffffff8184a110)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184dbb8)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_portsc(u32 portsc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff8191c920)
Location: drivers/usb/host/xhci.h:2550
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81921070)
Location: drivers/usb/host/xhci.h:2550
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
**Symbols:**

```
ffffffff8191c920-ffffffff8191cd25: xhci_decode_portsc (STB_LOCAL)
ffffffff81921070-ffffffff81921475: xhci_decode_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_portsc(u32 portsc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81923f90)
Location: drivers/usb/host/xhci.h:2565
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81928620)
Location: drivers/usb/host/xhci.h:2565
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
**Symbols:**

```
ffffffff81923f90-ffffffff81924390: xhci_decode_portsc (STB_LOCAL)
ffffffff81928620-ffffffff81928a20: xhci_decode_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_portsc(u32 portsc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81907680)
Location: drivers/usb/host/xhci.h:2571
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190bcb0)
Location: drivers/usb/host/xhci.h:2571
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
**Symbols:**

```
ffffffff81907680-ffffffff81907a7d: xhci_decode_portsc (STB_LOCAL)
ffffffff8190bcb0-ffffffff8190c0ad: xhci_decode_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_portsc(char *str, u32 portsc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff819a7310)
Location: drivers/usb/host/xhci.h:2578
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819abc30)
Location: drivers/usb/host/xhci.h:2578
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
**Symbols:**

```
ffffffff819a7310-ffffffff819a76c8: xhci_decode_portsc (STB_LOCAL)
ffffffff819abc30-ffffffff819abfe8: xhci_decode_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_portsc(char *str, u32 portsc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81b05c70)
Location: drivers/usb/host/xhci.h:2607
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0a270)
Location: drivers/usb/host/xhci.h:2607
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
**Symbols:**

```
ffffffff81b05c70-ffffffff81b06049: xhci_decode_portsc (STB_LOCAL)
ffffffff81b0a270-ffffffff81b0a649: xhci_decode_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_portsc(char *str, u32 portsc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81c95070)
Location: drivers/usb/host/xhci.h:2608
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9a170)
Location: drivers/usb/host/xhci.h:2608
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
**Symbols:**

```
ffffffff81c95070-ffffffff81c95449: xhci_decode_portsc (STB_LOCAL)
ffffffff81c9a170-ffffffff81c9a549: xhci_decode_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_portsc(char *str, u32 portsc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81cfb7a0)
Location: drivers/usb/host/xhci.h:2618
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d01530)
Location: drivers/usb/host/xhci.h:2618
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
**Symbols:**

```
ffffffff81cfb7a0-ffffffff81cfbb77: xhci_decode_portsc (STB_LOCAL)
ffffffff81d01530-ffffffff81d01907: xhci_decode_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_portsc(char *str, u32 portsc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81db1110)
Location: drivers/usb/host/xhci.h:2595
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db7370)
Location: drivers/usb/host/xhci.h:2595
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
```
**Symbols:**

```
ffffffff81db1110-ffffffff81db14e7: xhci_decode_portsc (STB_LOCAL)
ffffffff81db7370-ffffffff81db7747: xhci_decode_portsc (STB_LOCAL)
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
In drivers/usb/host/xhci-trace.c (ffff800010a88874)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8f668)
Location: drivers/usb/host/xhci.h:2547
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
In drivers/usb/host/xhci-trace.c (c0b5c000)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61408)
Location: drivers/usb/host/xhci.h:2547
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
In drivers/usb/host/xhci-trace.c (c000000000b642c4)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6b37c)
Location: drivers/usb/host/xhci.h:2547
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
In drivers/usb/host/xhci-trace.c (ffffffe00069e400)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a1cac)
Location: drivers/usb/host/xhci.h:2547
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
In drivers/usb/host/xhci-trace.c (ffffffff818024c0)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81803988)
Location: drivers/usb/host/xhci.h:2547
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
In drivers/usb/host/xhci-trace.c (ffffffff817c7660)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cb108)
Location: drivers/usb/host/xhci.h:2547
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
In drivers/usb/host/xhci-trace.c (ffffffff8183ef90)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81842a38)
Location: drivers/usb/host/xhci.h:2547
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
In drivers/usb/host/xhci-trace.c (ffffffff81859460)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185cf98)
Location: drivers/usb/host/xhci.h:2547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
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
<code>portsc</code> ➡️ <code>str, portsc</code>
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
