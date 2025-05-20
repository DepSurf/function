# Function: <code>dwc2_handle_gpwrdn_intr</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff8177117e)
Location: drivers/usb/dwc2/core_intr.c:651
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff81795df0)
Location: drivers/usb/dwc2/core_intr.c:651
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff817d4430)
Location: drivers/usb/dwc2/core_intr.c:663
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff817d4430-ffffffff817d4885: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff818052e0)
Location: drivers/usb/dwc2/core_intr.c:663
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818052e0-ffffffff81805735: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff818d5cb0)
Location: drivers/usb/dwc2/core_intr.c:661
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818d5cb0-ffffffff818d6105: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff818dfe90)
Location: drivers/usb/dwc2/core_intr.c:661
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818dfe90-ffffffff818e02e5: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:753
Inline: True
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818c33b0-ffffffff818c35ae: dwc2_handle_gpwrdn_intr.isra.0 (STB_LOCAL)
ffffffff81c10b32-ffffffff81c10b47: dwc2_handle_gpwrdn_intr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:753
Inline: True
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff8195a770-ffffffff8195a99c: dwc2_handle_gpwrdn_intr.isra.0 (STB_LOCAL)
ffffffff81d18c56-ffffffff81d18cae: dwc2_handle_gpwrdn_intr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:753
Inline: True
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81ab4580-ffffffff81ab47b8: dwc2_handle_gpwrdn_intr.isra.0 (STB_LOCAL)
ffffffff81ee3de4-ffffffff81ee3e53: dwc2_handle_gpwrdn_intr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:723
Inline: True
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81c3cda0-ffffffff81c3cfec: dwc2_handle_gpwrdn_intr.isra.0 (STB_LOCAL)
ffffffff8209fef4-ffffffff8209ff4e: dwc2_handle_gpwrdn_intr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:723
Inline: True
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81ca41a0-ffffffff81ca43d0: dwc2_handle_gpwrdn_intr.isra.0 (STB_LOCAL)
ffffffff821214aa-ffffffff82121504: dwc2_handle_gpwrdn_intr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:723
Inline: True
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81d58df0-ffffffff81d59020: dwc2_handle_gpwrdn_intr.isra.0 (STB_LOCAL)
ffffffff82202c81-ffffffff82202cdb: dwc2_handle_gpwrdn_intr.isra.0.cold (STB_LOCAL)
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
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffff800010a3c570)
Location: drivers/usb/dwc2/core_intr.c:663
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffff800010a3c570-ffff800010a3ca58: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (c0b0f848)
Location: drivers/usb/dwc2/core_intr.c:663
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
c0b0f848-c0b0fd00: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (c000000000afb190)
Location: drivers/usb/dwc2/core_intr.c:663
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
c000000000afb190-c000000000afb91c: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffe000657f04)
Location: drivers/usb/dwc2/core_intr.c:663
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffe000657f04-ffffffe0006585be: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff817bd6c0)
Location: drivers/usb/dwc2/core_intr.c:663
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff817bd6c0-ffffffff817bdb15: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff817fa160)
Location: drivers/usb/dwc2/core_intr.c:663
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff817fa160-ffffffff817fa5b5: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dwc2_handle_gpwrdn_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff818143a0)
Location: drivers/usb/dwc2/core_intr.c:663
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818143a0-ffffffff818147f5: dwc2_handle_gpwrdn_intr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
