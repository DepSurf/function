# Function: <code>dwc2_wait_for_mode</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816af8b0)
Location: drivers/usb/dwc2/core.c:246
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff816af8b0-ffffffff816af944: dwc2_wait_for_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816c4aa0)
Location: drivers/usb/dwc2/core.c:246
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff816c4aa0-ffffffff816c4b34: dwc2_wait_for_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81730d80)
Location: drivers/usb/dwc2/core.c:247
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81730d80-ffffffff81730e14: dwc2_wait_for_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff8176fbe0)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff8176fbe0-ffffffff8176fc74: dwc2_wait_for_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81794260)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81794260-ffffffff817942f9: dwc2_wait_for_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817d4212)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff817d2c00-ffffffff817d2c6a: dwc2_wait_for_mode (STB_LOCAL)
ffffffff817d4212-ffffffff817d4242: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818050e2)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81803a50-ffffffff81803aba: dwc2_wait_for_mode (STB_LOCAL)
ffffffff818050e2-ffffffff81805112: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:385
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff818d4460-ffffffff818d44ca: dwc2_wait_for_mode (STB_LOCAL)
ffffffff818d5ac8-ffffffff818d5af8: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:385
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff818de780-ffffffff818de7ea: dwc2_wait_for_mode (STB_LOCAL)
ffffffff81c1ebca-ffffffff81c1ebfa: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:316
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff818c1ab0-ffffffff818c1b1d: dwc2_wait_for_mode (STB_LOCAL)
ffffffff81c10a5b-ffffffff81c10a8b: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81d17dc0)
Location: drivers/usb/dwc2/core.c:316
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff819580c0-ffffffff8195814d: dwc2_wait_for_mode (STB_LOCAL)
ffffffff81d17da5-ffffffff81d17df0: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ee2c67)
Location: drivers/usb/dwc2/core.c:316
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81ab1f20-ffffffff81ab1fbb: dwc2_wait_for_mode (STB_LOCAL)
ffffffff81ee2c4c-ffffffff81ee2c97: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81c3a5f7)
Location: drivers/usb/dwc2/core.c:286
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81c3a560-ffffffff81c3a63f: dwc2_wait_for_mode (STB_LOCAL)
ffffffff8209ee5d-ffffffff8209ee78: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ca19a7)
Location: drivers/usb/dwc2/core.c:286
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81ca1910-ffffffff81ca19ef: dwc2_wait_for_mode (STB_LOCAL)
ffffffff8212040d-ffffffff82120428: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81d565f7)
Location: drivers/usb/dwc2/core.c:286
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81d56560-ffffffff81d5663f: dwc2_wait_for_mode (STB_LOCAL)
ffffffff82201be4-ffffffff82201bff: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3a150)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffff800010a3a150-ffff800010a3a21c: dwc2_wait_for_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0d4a4)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
c0b0d4a4-c0b0d5e0: dwc2_wait_for_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af71c0)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
c000000000af71c0-c000000000af731c: dwc2_wait_for_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe000655040)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffe000655040-ffffffe00065512a: dwc2_wait_for_mode (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817bd4c2)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff817bbe30-ffffffff817bbe9a: dwc2_wait_for_mode (STB_LOCAL)
ffffffff817bd4c2-ffffffff817bd4f2: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817f9f62)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff817f88d0-ffffffff817f893a: dwc2_wait_for_mode (STB_LOCAL)
ffffffff817f9f62-ffffffff817f9f92: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_wait_for_mode(struct dwc2_hsotg *hsotg, bool host_mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818141a2)
Location: drivers/usb/dwc2/core.c:385
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_core_reset
```
**Symbols:**

```
ffffffff81812b10-ffffffff81812b7a: dwc2_wait_for_mode (STB_LOCAL)
ffffffff818141a2-ffffffff818141d2: dwc2_wait_for_mode.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
