# Function: <code>dwc2_host_exit_clock_gating</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_host_exit_clock_gating(struct dwc2_hsotg *hsotg, int rem_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818cc6d0)
Location: drivers/usb/dwc2/hcd.c:5939
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
```
**Symbols:**

```
ffffffff818cc6d0-ffffffff818cc850: dwc2_host_exit_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_host_exit_clock_gating(struct dwc2_hsotg *hsotg, int rem_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5944
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
```
**Symbols:**

```
ffffffff81d1cb6e-ffffffff81d1cc86: dwc2_host_exit_clock_gating.cold (STB_LOCAL)
ffffffff81966260-ffffffff819664ef: dwc2_host_exit_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_host_exit_clock_gating(struct dwc2_hsotg *hsotg, int rem_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5940
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
```
**Symbols:**

```
ffffffff81ee82c6-ffffffff81ee8489: dwc2_host_exit_clock_gating.cold (STB_LOCAL)
ffffffff81ac0460-ffffffff81ac067d: dwc2_host_exit_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_host_exit_clock_gating(struct dwc2_hsotg *hsotg, int rem_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5913
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
```
**Symbols:**

```
ffffffff820a3867-ffffffff820a3a2a: dwc2_host_exit_clock_gating.cold (STB_LOCAL)
ffffffff81c49f10-ffffffff81c4a12d: dwc2_host_exit_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_host_exit_clock_gating(struct dwc2_hsotg *hsotg, int rem_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5913
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
```
**Symbols:**

```
ffffffff82124e1b-ffffffff82124fde: dwc2_host_exit_clock_gating.cold (STB_LOCAL)
ffffffff81cb1510-ffffffff81cb172d: dwc2_host_exit_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_host_exit_clock_gating(struct dwc2_hsotg *hsotg, int rem_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5913
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
```
**Symbols:**

```
ffffffff822065ef-ffffffff822067b2: dwc2_host_exit_clock_gating.cold (STB_LOCAL)
ffffffff81d66220-ffffffff81d6643d: dwc2_host_exit_clock_gating (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
