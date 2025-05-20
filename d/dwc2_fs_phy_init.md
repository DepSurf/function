# Function: <code>dwc2_fs_phy_init</code>

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
In drivers/usb/dwc2/core.c (ffffffff81622335)
Location: drivers/usb/dwc2/core.c:545
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
In drivers/usb/dwc2/hcd.c (ffffffff81685faa)
Location: drivers/usb/dwc2/hcd.c:119
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
In drivers/usb/dwc2/hcd.c (ffffffff816b41e5)
Location: drivers/usb/dwc2/hcd.c:119
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
In drivers/usb/dwc2/hcd.c (ffffffff816c852e)
Location: drivers/usb/dwc2/hcd.c:122
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
In drivers/usb/dwc2/hcd.c (ffffffff81734a18)
Location: drivers/usb/dwc2/hcd.c:123
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
Location: drivers/usb/dwc2/hcd.c:126
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
Location: drivers/usb/dwc2/hcd.c:126
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
In drivers/usb/dwc2/core.c (ffffffff817d3fa2)
Location: drivers/usb/dwc2/core.c:1049
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
In drivers/usb/dwc2/core.c (ffffffff81804e72)
Location: drivers/usb/dwc2/core.c:1049
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
int dwc2_fs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1064
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff818d5800-ffffffff818d5a00: dwc2_fs_phy_init (STB_LOCAL)
ffffffff818d5beb-ffffffff818d5c0c: dwc2_fs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_fs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1064
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff818dfb20-ffffffff818dfd1b: dwc2_fs_phy_init (STB_LOCAL)
ffffffff81c1eced-ffffffff81c1ed0e: dwc2_fs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_fs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1008
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff818c2cb0-ffffffff818c2ebd: dwc2_fs_phy_init (STB_LOCAL)
ffffffff81c10afd-ffffffff81c10b1e: dwc2_fs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_fs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1008
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81959e30-ffffffff8195a153: dwc2_fs_phy_init (STB_LOCAL)
ffffffff81d1882d-ffffffff81d18984: dwc2_fs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_fs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:1008
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81ab3cf0-ffffffff81ab3fd6: dwc2_fs_phy_init (STB_LOCAL)
ffffffff81ee3831-ffffffff81ee39d9: dwc2_fs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_fs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:978
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81c3c570-ffffffff81c3c876: dwc2_fs_phy_init (STB_LOCAL)
ffffffff8209f991-ffffffff8209fb18: dwc2_fs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_fs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:978
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81ca3970-ffffffff81ca3c76: dwc2_fs_phy_init (STB_LOCAL)
ffffffff82120f47-ffffffff821210ce: dwc2_fs_phy_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_fs_phy_init(struct dwc2_hsotg *hsotg, bool select_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:978
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
```
**Symbols:**

```
ffffffff81d585c0-ffffffff81d588c6: dwc2_fs_phy_init (STB_LOCAL)
ffffffff8220271e-ffffffff822028a5: dwc2_fs_phy_init.cold (STB_LOCAL)
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
In drivers/usb/dwc2/core.c (ffff800010a3c1e8)
Location: drivers/usb/dwc2/core.c:1049
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
In drivers/usb/dwc2/core.c (c0b0f140)
Location: drivers/usb/dwc2/core.c:1049
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
In drivers/usb/dwc2/core.c (c000000000afaadc)
Location: drivers/usb/dwc2/core.c:1049
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
In drivers/usb/dwc2/core.c (ffffffe0006579e8)
Location: drivers/usb/dwc2/core.c:1049
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
In drivers/usb/dwc2/core.c (ffffffff817bd252)
Location: drivers/usb/dwc2/core.c:1049
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
In drivers/usb/dwc2/core.c (ffffffff817f9cf2)
Location: drivers/usb/dwc2/core.c:1049
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
In drivers/usb/dwc2/core.c (ffffffff81813f32)
Location: drivers/usb/dwc2/core.c:1049
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
