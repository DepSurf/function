# Function: <code>dwc2_exit_partial_power_down</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff8176fec0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffff8176fec0-ffffffff8176ffa7: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817946d0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffff817946d0-ffffffff81794821: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffff817d4262-ffffffff817d42a4: dwc2_exit_partial_power_down.cold (STB_LOCAL)
ffffffff817d2fb0-ffffffff817d30cc: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffff81805132-ffffffff81805174: dwc2_exit_partial_power_down.cold (STB_LOCAL)
ffffffff81803e80-ffffffff81803f9c: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_session_req_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffff818d5b18-ffffffff818d5b5a: dwc2_exit_partial_power_down.cold (STB_LOCAL)
ffffffff818d4920-ffffffff818d4a3c: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_session_req_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffff81c1ec1a-ffffffff81c1ec5c: dwc2_exit_partial_power_down.cold (STB_LOCAL)
ffffffff818dec40-ffffffff818ded5c: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, int rem_wakeup, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c1f20)
Location: drivers/usb/dwc2/core.c:137
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff818c1f20-ffffffff818c1f3f: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, int rem_wakeup, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81958a80)
Location: drivers/usb/dwc2/core.c:137
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81958a80-ffffffff81958a9f: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, int rem_wakeup, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ab2920)
Location: drivers/usb/dwc2/core.c:137
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81ab2920-ffffffff81ab2953: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, int rem_wakeup, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81c3b010)
Location: drivers/usb/dwc2/core.c:107
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81c3b010-ffffffff81c3b043: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, int rem_wakeup, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ca23c0)
Location: drivers/usb/dwc2/core.c:107
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81ca23c0-ffffffff81ca23f3: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, int rem_wakeup, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81d57010)
Location: drivers/usb/dwc2/core.c:107
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81d57010-ffffffff81d57043: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3a8c0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffff800010a3a8c0-ffff800010a3aa84: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0dae0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
c0b0dae0-c0b0dc88: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af80e0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
c000000000af80e0-c000000000af8480: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe000655a70)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffe000655a70-ffffffe000655d0c: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffff817bd512-ffffffff817bd554: dwc2_exit_partial_power_down.cold (STB_LOCAL)
ffffffff817bc260-ffffffff817bc37c: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffff817f9fb2-ffffffff817f9ff4: dwc2_exit_partial_power_down.cold (STB_LOCAL)
ffffffff817f8d00-ffffffff817f8e1c: dwc2_exit_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_exit_partial_power_down(struct dwc2_hsotg *hsotg, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:136
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
```
**Symbols:**

```
ffffffff818141f2-ffffffff81814234: dwc2_exit_partial_power_down.cold (STB_LOCAL)
ffffffff81812f40-ffffffff8181305c: dwc2_exit_partial_power_down (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int rem_wakeup</code>
</li>
<li>
<b>Param reordered. </b>
<code>hsotg, restore</code> ➡️ <code>hsotg, rem_wakeup, restore</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
