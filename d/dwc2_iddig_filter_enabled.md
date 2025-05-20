# Function: <code>dwc2_iddig_filter_enabled</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816af950)
Location: drivers/usb/dwc2/core.c:284
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff816af950-ffffffff816af99b: dwc2_iddig_filter_enabled.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816c4b40)
Location: drivers/usb/dwc2/core.c:284
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff816c4b40-ffffffff816c4b8b: dwc2_iddig_filter_enabled.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81730e20)
Location: drivers/usb/dwc2/core.c:285
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81730e20-ffffffff81730e6b: dwc2_iddig_filter_enabled.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff8176fc80)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff8176fc80-ffffffff8176fccb: dwc2_iddig_filter_enabled.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81794300)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81794300-ffffffff8179437b: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817d2b80)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff817d2b80-ffffffff817d2bfb: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81803ac0)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81803ac0-ffffffff81803b3b: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d44d0)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff818d44d0-ffffffff818d454b: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818de7f0)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff818de7f0-ffffffff818de86b: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c1b20)
Location: drivers/usb/dwc2/core.c:356
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff818c1b20-ffffffff818c1ba4: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff8195850b)
Location: drivers/usb/dwc2/core.c:356
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81958460-ffffffff8195853c: dwc2_iddig_filter_enabled (STB_LOCAL)
ffffffff81d17ee3-ffffffff81d17f36: dwc2_iddig_filter_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:356
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81ab22e0-ffffffff81ab23c6: dwc2_iddig_filter_enabled (STB_LOCAL)
ffffffff81ee2d8a-ffffffff81ee2ddd: dwc2_iddig_filter_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:326
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81c3a980-ffffffff81c3aa66: dwc2_iddig_filter_enabled (STB_LOCAL)
ffffffff8209ef6b-ffffffff8209efbe: dwc2_iddig_filter_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:326
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81ca1d30-ffffffff81ca1e16: dwc2_iddig_filter_enabled (STB_LOCAL)
ffffffff8212051b-ffffffff8212056e: dwc2_iddig_filter_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:326
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81d56980-ffffffff81d56a66: dwc2_iddig_filter_enabled (STB_LOCAL)
ffffffff82201cf2-ffffffff82201d45: dwc2_iddig_filter_enabled.cold (STB_LOCAL)
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
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3a220)
Location: drivers/usb/dwc2/core.c:425
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffff800010a3a220-ffff800010a3a324: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0d3f0)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
c0b0d3f0-c0b0d4a4: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af7320)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
c000000000af7320-c000000000af75c8: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe00065512a)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffe00065512a-ffffffe000655268: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817bbea0)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff817bbea0-ffffffff817bbf1b: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817f8940)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff817f8940-ffffffff817f89bb: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool dwc2_iddig_filter_enabled(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81812b80)
Location: drivers/usb/dwc2/core.c:425
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81812b80-ffffffff81812bfb: dwc2_iddig_filter_enabled (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
