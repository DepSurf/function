# Function: <code>dwc2_hs_phy_init</code>

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
In drivers/usb/dwc2/core.c (ffffffff816222a7)
Location: drivers/usb/dwc2/core.c:598
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81685e3e)
Location: drivers/usb/dwc2/hcd.c:176
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff816b4085)
Location: drivers/usb/dwc2/hcd.c:176
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff816c83f7)
Location: drivers/usb/dwc2/hcd.c:192
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff817348d0)
Location: drivers/usb/dwc2/hcd.c:193
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:196
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:196
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/core.c (ffffffff817d3e88)
Location: drivers/usb/dwc2/core.c:1119
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
In drivers/usb/dwc2/core.c (ffffffff81804d58)
Location: drivers/usb/dwc2/core.c:1119
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_hs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1134
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff818d5000-ffffffff818d512c: dwc2_hs_phy_init (STB_LOCAL)
ffffffff818d5b99-ffffffff818d5bd0: dwc2_hs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_hs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1134
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff818df320-ffffffff818df44c: dwc2_hs_phy_init (STB_LOCAL)
ffffffff81c1ec9b-ffffffff81c1ecd2: dwc2_hs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_hs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1078
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff818c2430-ffffffff818c252b: dwc2_hs_phy_init (STB_LOCAL)
ffffffff81c10aab-ffffffff81c10ae2: dwc2_hs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_hs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1078
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81959230-ffffffff81959391: dwc2_hs_phy_init (STB_LOCAL)
ffffffff81d1847d-ffffffff81d18508: dwc2_hs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_hs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1078
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81ab3050-ffffffff81ab31b1: dwc2_hs_phy_init (STB_LOCAL)
ffffffff81ee341f-ffffffff81ee34a8: dwc2_hs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_hs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1048
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81c3b7a0-ffffffff81c3b928: dwc2_hs_phy_init (STB_LOCAL)
ffffffff8209f5cf-ffffffff8209f623: dwc2_hs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_hs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1048
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81ca2b50-ffffffff81ca2cf6: dwc2_hs_phy_init (STB_LOCAL)
ffffffff82120b7f-ffffffff82120bd9: dwc2_hs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_hs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1048
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81d577a0-ffffffff81d57946: dwc2_hs_phy_init (STB_LOCAL)
ffffffff82202356-ffffffff822023b0: dwc2_hs_phy_init.cold (STB_LOCAL)
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
In drivers/usb/dwc2/core.c (ffff800010a3c000)
Location: drivers/usb/dwc2/core.c:1119
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
In drivers/usb/dwc2/core.c (c0b0ef94)
Location: drivers/usb/dwc2/core.c:1119
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
In drivers/usb/dwc2/core.c (c000000000afa850)
Location: drivers/usb/dwc2/core.c:1119
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
In drivers/usb/dwc2/core.c (ffffffe000657780)
Location: drivers/usb/dwc2/core.c:1119
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
In drivers/usb/dwc2/core.c (ffffffff817bd138)
Location: drivers/usb/dwc2/core.c:1119
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
In drivers/usb/dwc2/core.c (ffffffff817f9bd8)
Location: drivers/usb/dwc2/core.c:1119
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
In drivers/usb/dwc2/core.c (ffffffff81813e18)
Location: drivers/usb/dwc2/core.c:1119
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
