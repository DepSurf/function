# Function: <code>xhci_decode_trb</code>

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
In drivers/usb/host/xhci-trace.c (ffffffff8170422b)
Location: drivers/usb/host/xhci.h:2125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
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
In drivers/usb/host/xhci-trace.c (ffffffff817711eb)
Location: drivers/usb/host/xhci.h:2148
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817757a7)
Location: drivers/usb/host/xhci.h:2148
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff817b15d0)
Location: drivers/usb/host/xhci.h:2160
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b5870)
Location: drivers/usb/host/xhci.h:2160
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff817b15d0-ffffffff817b1dbb: xhci_decode_trb (STB_LOCAL)
ffffffff817b5870-ffffffff817b605b: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff817d7b50)
Location: drivers/usb/host/xhci.h:2168
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dbda0)
Location: drivers/usb/host/xhci.h:2168
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff817d7b50-ffffffff817d8400: xhci_decode_trb (STB_LOCAL)
ffffffff817dbda0-ffffffff817dc650: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81818170)
Location: drivers/usb/host/xhci.h:2201
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181d48b)
Location: drivers/usb/host/xhci.h:2201
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff81818170-ffffffff81818a25: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff818493f0)
Location: drivers/usb/host/xhci.h:2211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e84d)
Location: drivers/usb/host/xhci.h:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff818493f0-ffffffff81849cb8: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff8191bc30)
Location: drivers/usb/host/xhci.h:2214
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819206e0)
Location: drivers/usb/host/xhci.h:2214
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff8191bc30-ffffffff8191c4f6: xhci_decode_trb (STB_LOCAL)
ffffffff819206e0-ffffffff81920fa6: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff819232a0)
Location: drivers/usb/host/xhci.h:2229
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81927c90)
Location: drivers/usb/host/xhci.h:2229
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff819232a0-ffffffff81923b66: xhci_decode_trb (STB_LOCAL)
ffffffff81927c90-ffffffff81928556: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81906990)
Location: drivers/usb/host/xhci.h:2235
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190b310)
Location: drivers/usb/host/xhci.h:2235
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff81906990-ffffffff81907269: xhci_decode_trb (STB_LOCAL)
ffffffff8190b310-ffffffff8190bbe9: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff819a7d70)
Location: drivers/usb/host/xhci.h:2242
Inline: True
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ac7f0)
Location: drivers/usb/host/xhci.h:2242
Inline: True
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment
```
**Symbols:**

```
ffffffff819a7d70-ffffffff819a8645: xhci_decode_trb.constprop.0 (STB_LOCAL)
ffffffff819ac7f0-ffffffff819ad0c5: xhci_decode_trb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81b067d0)
Location: drivers/usb/host/xhci.h:2269
Inline: True
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0adb0)
Location: drivers/usb/host/xhci.h:2269
Inline: True
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment
```
**Symbols:**

```
ffffffff81b067d0-ffffffff81b070a9: xhci_decode_trb.constprop.0 (STB_LOCAL)
ffffffff81b0adb0-ffffffff81b0b689: xhci_decode_trb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81c95fc0)
Location: drivers/usb/host/xhci.h:2270
Inline: True
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9ad00)
Location: drivers/usb/host/xhci.h:2270
Inline: True
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment
```
**Symbols:**

```
ffffffff81c95fc0-ffffffff81c96899: xhci_decode_trb.constprop.0 (STB_LOCAL)
ffffffff81c9ad00-ffffffff81c9b5d9: xhci_decode_trb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81cfc760)
Location: drivers/usb/host/xhci.h:2280
Inline: True
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d020b0)
Location: drivers/usb/host/xhci.h:2280
Inline: True
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment
```
**Symbols:**

```
ffffffff81cfc760-ffffffff81cfd063: xhci_decode_trb.constprop.0 (STB_LOCAL)
ffffffff81d020b0-ffffffff81d029b3: xhci_decode_trb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81db2130)
Location: drivers/usb/host/xhci.h:2257
Inline: True
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db7be0)
Location: drivers/usb/host/xhci.h:2257
Inline: True
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment
```
**Symbols:**

```
ffffffff81db2130-ffffffff81db2a33: xhci_decode_trb.constprop.0 (STB_LOCAL)
ffffffff81db7be0-ffffffff81db84e3: xhci_decode_trb.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffff800010a87c38)
Location: drivers/usb/host/xhci.h:2211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8eea8)
Location: drivers/usb/host/xhci.h:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffff800010a87c38-ffff800010a8840c: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (c0b5b388)
Location: drivers/usb/host/xhci.h:2211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (c0b60bcc)
Location: drivers/usb/host/xhci.h:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
c0b5b388-c0b5bbd4: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (c000000000b62ff0)
Location: drivers/usb/host/xhci.h:2211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6a818)
Location: drivers/usb/host/xhci.h:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
c000000000b62ff0-c000000000b63c44: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffe00069d7a0)
Location: drivers/usb/host/xhci.h:2211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a2900)
Location: drivers/usb/host/xhci.h:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffe00069d7a0-ffffffe00069df74: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff818017a0)
Location: drivers/usb/host/xhci.h:2211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8180461d)
Location: drivers/usb/host/xhci.h:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff818017a0-ffffffff81802068: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff817c6940)
Location: drivers/usb/host/xhci.h:2211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cbd9d)
Location: drivers/usb/host/xhci.h:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff817c6940-ffffffff817c7208: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff8183e270)
Location: drivers/usb/host/xhci.h:2211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818436cd)
Location: drivers/usb/host/xhci.h:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff8183e270-ffffffff8183eb38: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81858740)
Location: drivers/usb/host/xhci.h:2211
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185dc2d)
Location: drivers/usb/host/xhci.h:2211
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff81858740-ffffffff81859008: xhci_decode_trb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
