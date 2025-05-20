# Function: <code>dwc2_host_enter_clock_gating</code>

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
void dwc2_host_enter_clock_gating(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818cc230)
Location: drivers/usb/dwc2/hcd.c:5903
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff818cc230-ffffffff818cc336: dwc2_host_enter_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_host_enter_clock_gating(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5908
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff81d1c922-ffffffff81d1c9f4: dwc2_host_enter_clock_gating.cold (STB_LOCAL)
ffffffff81965c30-ffffffff81965df6: dwc2_host_enter_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_host_enter_clock_gating(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5904
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff81ee7fe9-ffffffff81ee8135: dwc2_host_enter_clock_gating.cold (STB_LOCAL)
ffffffff81abfee0-ffffffff81ac004c: dwc2_host_enter_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_host_enter_clock_gating(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5877
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff820a35da-ffffffff820a3726: dwc2_host_enter_clock_gating.cold (STB_LOCAL)
ffffffff81c49930-ffffffff81c49a9c: dwc2_host_enter_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_host_enter_clock_gating(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5877
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff82124b8e-ffffffff82124cda: dwc2_host_enter_clock_gating.cold (STB_LOCAL)
ffffffff81cb0f10-ffffffff81cb107c: dwc2_host_enter_clock_gating (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_host_enter_clock_gating(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5877
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff82206362-ffffffff822064ae: dwc2_host_enter_clock_gating.cold (STB_LOCAL)
ffffffff81d65c20-ffffffff81d65d8c: dwc2_host_enter_clock_gating (STB_GLOBAL)
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
