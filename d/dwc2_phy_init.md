# Function: <code>dwc2_phy_init</code>

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
In drivers/usb/dwc2/core.c (ffffffff81622299)
Location: drivers/usb/dwc2/core.c:647
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
In drivers/usb/dwc2/hcd.c (ffffffff81685cb1)
Location: drivers/usb/dwc2/hcd.c:228
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
In drivers/usb/dwc2/hcd.c (ffffffff816b3f02)
Location: drivers/usb/dwc2/hcd.c:228
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
In drivers/usb/dwc2/hcd.c (ffffffff816c82b4)
Location: drivers/usb/dwc2/hcd.c:244
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
In drivers/usb/dwc2/hcd.c (ffffffff81734784)
Location: drivers/usb/dwc2/hcd.c:250
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
In drivers/usb/dwc2/hcd.c (ffffffff817765b6)
Location: drivers/usb/dwc2/hcd.c:253
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
In drivers/usb/dwc2/hcd.c (ffffffff8179c03e)
Location: drivers/usb/dwc2/hcd.c:253
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1185
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff817d43d4-ffffffff817d442a: dwc2_phy_init.cold (STB_LOCAL)
ffffffff817d3e60-ffffffff817d4212: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1185
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff8180527e-ffffffff818052d4: dwc2_phy_init.cold (STB_LOCAL)
ffffffff81804d30-ffffffff818050e2: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d5a00)
Location: drivers/usb/dwc2/core.c:1200
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818d5a00-ffffffff818d5ac8: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818dfd20)
Location: drivers/usb/dwc2/core.c:1200
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818dfd20-ffffffff818dfde8: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c2ec0)
Location: drivers/usb/dwc2/core.c:1153
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818c2ec0-ffffffff818c3010: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1153
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff81d18984-ffffffff81d18a68: dwc2_phy_init.cold (STB_LOCAL)
ffffffff8195a160-ffffffff8195a399: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1153
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff81ee39d9-ffffffff81ee3b39: dwc2_phy_init.cold (STB_LOCAL)
ffffffff81ab3fe0-ffffffff81ab4231: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff8209fb18-ffffffff8209fc78: dwc2_phy_init.cold (STB_LOCAL)
ffffffff81c3c890-ffffffff81c3cae1: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff821210ce-ffffffff8212122e: dwc2_phy_init.cold (STB_LOCAL)
ffffffff81ca3c90-ffffffff81ca3ee1: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff822028a5-ffffffff82202a05: dwc2_phy_init.cold (STB_LOCAL)
ffffffff81d588e0-ffffffff81d58b31: dwc2_phy_init (STB_GLOBAL)
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
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3bfc8)
Location: drivers/usb/dwc2/core.c:1185
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffff800010a3bfc8-ffff800010a3c56c: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0ef60)
Location: drivers/usb/dwc2/core.c:1185
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
c0b0ef60-c0b0f488: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000afa810)
Location: drivers/usb/dwc2/core.c:1185
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
c000000000afa810-c000000000afb18c: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe000657748)
Location: drivers/usb/dwc2/core.c:1185
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffe000657748-ffffffe000657f04: dwc2_phy_init (STB_GLOBAL)
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
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1185
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff817bd65e-ffffffff817bd6b4: dwc2_phy_init.cold (STB_LOCAL)
ffffffff817bd110-ffffffff817bd4c2: dwc2_phy_init (STB_GLOBAL)
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
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1185
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff817fa0fe-ffffffff817fa154: dwc2_phy_init.cold (STB_LOCAL)
ffffffff817f9bb0-ffffffff817f9f62: dwc2_phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1185
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff8181433e-ffffffff81814394: dwc2_phy_init.cold (STB_LOCAL)
ffffffff81813df0-ffffffff818141a2: dwc2_phy_init (STB_GLOBAL)
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
