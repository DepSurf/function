# Function: <code>dwc2_handle_usb_suspend_intr</code>

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
In drivers/usb/dwc2/core_intr.c (ffffffff81625ae5)
Location: drivers/usb/dwc2/core_intr.c:417
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff81683f23)
Location: drivers/usb/dwc2/core_intr.c:415
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff816b04b6)
Location: drivers/usb/dwc2/core_intr.c:415
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff816c577b)
Location: drivers/usb/dwc2/core_intr.c:414
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff81731a5b)
Location: drivers/usb/dwc2/core_intr.c:415
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff81770ccd)
Location: drivers/usb/dwc2/core_intr.c:471
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
In drivers/usb/dwc2/core_intr.c (ffffffff817959d8)
Location: drivers/usb/dwc2/core_intr.c:471
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff817d5383)
Location: drivers/usb/dwc2/core_intr.c:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff81806233)
Location: drivers/usb/dwc2/core_intr.c:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_handle_usb_suspend_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff818d67a0)
Location: drivers/usb/dwc2/core_intr.c:481
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818d67a0-ffffffff818d6911: dwc2_handle_usb_suspend_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_handle_usb_suspend_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff818e0980)
Location: drivers/usb/dwc2/core_intr.c:481
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818e0980-ffffffff818e0af1: dwc2_handle_usb_suspend_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_handle_usb_suspend_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff818c3880)
Location: drivers/usb/dwc2/core_intr.c:505
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818c3880-ffffffff818c39f8: dwc2_handle_usb_suspend_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_usb_suspend_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:505
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff8195a9a0-ffffffff8195ab49: dwc2_handle_usb_suspend_intr (STB_LOCAL)
ffffffff81d18cae-ffffffff81d18ced: dwc2_handle_usb_suspend_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_usb_suspend_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:505
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81ab47c0-ffffffff81ab49c1: dwc2_handle_usb_suspend_intr (STB_LOCAL)
ffffffff81ee3e53-ffffffff81ee3e92: dwc2_handle_usb_suspend_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_usb_suspend_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:475
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81c3d000-ffffffff81c3d204: dwc2_handle_usb_suspend_intr (STB_LOCAL)
ffffffff8209ff4e-ffffffff8209ff8d: dwc2_handle_usb_suspend_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_usb_suspend_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:475
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81ca43e0-ffffffff81ca45e4: dwc2_handle_usb_suspend_intr (STB_LOCAL)
ffffffff82121504-ffffffff82121543: dwc2_handle_usb_suspend_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_usb_suspend_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:475
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81d59030-ffffffff81d59234: dwc2_handle_usb_suspend_intr (STB_LOCAL)
ffffffff82202cdb-ffffffff82202d1a: dwc2_handle_usb_suspend_intr.cold (STB_LOCAL)
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
In drivers/usb/dwc2/core_intr.c (ffff800010a3da78)
Location: drivers/usb/dwc2/core_intr.c:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (c0b105a8)
Location: drivers/usb/dwc2/core_intr.c:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (c000000000afd500)
Location: drivers/usb/dwc2/core_intr.c:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffe000659722)
Location: drivers/usb/dwc2/core_intr.c:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff817be613)
Location: drivers/usb/dwc2/core_intr.c:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff817fb0b3)
Location: drivers/usb/dwc2/core_intr.c:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff818152aa)
Location: drivers/usb/dwc2/core_intr.c:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
