# Function: <code>dwc2_process_non_periodic_channels</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8162906e)
Location: drivers/usb/dwc2/hcd.c:1199
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81688cec)
Location: drivers/usb/dwc2/hcd.c:3035
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b6f0c)
Location: drivers/usb/dwc2/hcd.c:3066
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816cb3a4)
Location: drivers/usb/dwc2/hcd.c:3079
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8173790a)
Location: drivers/usb/dwc2/hcd.c:3085
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817777a6)
Location: drivers/usb/dwc2/hcd.c:3202
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179d566)
Location: drivers/usb/dwc2/hcd.c:3192
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817dc166)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff8180d086)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_process_non_periodic_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818de010)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: False
```
**Symbols:**

```
ffffffff818de010-ffffffff818de183: dwc2_process_non_periodic_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_process_non_periodic_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e7e80)
Location: drivers/usb/dwc2/hcd.c:3013
Inline: False
```
**Symbols:**

```
ffffffff818e7e80-ffffffff818e7ff3: dwc2_process_non_periodic_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_process_non_periodic_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c9d60)
Location: drivers/usb/dwc2/hcd.c:3011
Inline: False
```
**Symbols:**

```
ffffffff818c9d60-ffffffff818c9edb: dwc2_process_non_periodic_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_process_non_periodic_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3011
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81962bf0-ffffffff81962e4d: dwc2_process_non_periodic_channels (STB_LOCAL)
ffffffff81d1b934-ffffffff81d1ba3d: dwc2_process_non_periodic_channels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_process_non_periodic_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:3007
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81abd0c0-ffffffff81abd31e: dwc2_process_non_periodic_channels (STB_LOCAL)
ffffffff81ee6c99-ffffffff81ee6dba: dwc2_process_non_periodic_channels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_process_non_periodic_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2978
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81c46770-ffffffff81c469ce: dwc2_process_non_periodic_channels (STB_LOCAL)
ffffffff820a24a0-ffffffff820a25c1: dwc2_process_non_periodic_channels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_process_non_periodic_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2978
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81cadd30-ffffffff81cadf8c: dwc2_process_non_periodic_channels (STB_LOCAL)
ffffffff82123a66-ffffffff82123b81: dwc2_process_non_periodic_channels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_process_non_periodic_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2978
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81d629e0-ffffffff81d62c3c: dwc2_process_non_periodic_channels (STB_LOCAL)
ffffffff8220523d-ffffffff82205358: dwc2_process_non_periodic_channels.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffff800010a4598c)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: True
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
In drivers/usb/dwc2/hcd.c (c0b181a8)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: True
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
In drivers/usb/dwc2/hcd.c (c000000000b0982c)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffe0006624f2)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff817c5466)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81801f06)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff8181c016)
Location: drivers/usb/dwc2/hcd.c:3012
Inline: True
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
