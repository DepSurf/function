# Function: <code>dwc2_hc_n_intr</code>

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
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162c757)
Location: drivers/usb/dwc2/hcd_intr.c:1971
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168c3c0)
Location: drivers/usb/dwc2/hcd_intr.c:1977
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff8168c3c0-ffffffff8168cdbf: dwc2_hc_n_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816ba4c0)
Location: drivers/usb/dwc2/hcd_intr.c:1982
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff816ba4c0-ffffffff816baea9: dwc2_hc_n_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816ce760)
Location: drivers/usb/dwc2/hcd_intr.c:1986
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff816ce760-ffffffff816cf047: dwc2_hc_n_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173ad90)
Location: drivers/usb/dwc2/hcd_intr.c:1987
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff8173ad90-ffffffff8173b68f: dwc2_hc_n_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177b4a0)
Location: drivers/usb/dwc2/hcd_intr.c:2031
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff8177b4a0-ffffffff8177be5a: dwc2_hc_n_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a1760)
Location: drivers/usb/dwc2/hcd_intr.c:2031
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff817a1760-ffffffff817a21c8: dwc2_hc_n_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff817e0940-ffffffff817e0eea: dwc2_hc_n_intr (STB_LOCAL)
ffffffff817e18e6-ffffffff817e1965: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81811830-ffffffff81811dde: dwc2_hc_n_intr (STB_LOCAL)
ffffffff818127d6-ffffffff81812836: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr
```
**Symbols:**

```
ffffffff818e2ce0-ffffffff818e328d: dwc2_hc_n_intr (STB_LOCAL)
ffffffff818e3847-ffffffff818e38ab: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2044
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr
```
**Symbols:**

```
ffffffff818ec540-ffffffff818ecaed: dwc2_hc_n_intr (STB_LOCAL)
ffffffff81c1fd90-ffffffff81c1fdf4: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2044
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff818cfca0-ffffffff818d024d: dwc2_hc_n_intr (STB_LOCAL)
ffffffff81c11d4f-ffffffff81c11db3: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2044
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff8196a1b0-ffffffff8196a816: dwc2_hc_n_intr (STB_LOCAL)
ffffffff81d1dc14-ffffffff81d1ddf2: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2044
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81ac4480-ffffffff81ac4b85: dwc2_hc_n_intr (STB_LOCAL)
ffffffff81ee95c4-ffffffff81ee9819: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2014
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81c4e4a0-ffffffff81c4ebaf: dwc2_hc_n_intr (STB_LOCAL)
ffffffff820a4825-ffffffff820a4a38: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2014
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81cb5b00-ffffffff81cb617f: dwc2_hc_n_intr (STB_LOCAL)
ffffffff82125de2-ffffffff82125f9e: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2014
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff81d6a830-ffffffff81d6aecd: dwc2_hc_n_intr (STB_LOCAL)
ffffffff822075b6-ffffffff822077a7: dwc2_hc_n_intr.cold (STB_LOCAL)
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
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4ab68)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffff800010a4ab68-ffff800010a4b0f8: dwc2_hc_n_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (c0b1ce24)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
c0b1ce24-c0b1d3e0: dwc2_hc_n_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (c000000000b11100)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
c000000000b11100-c000000000b1196c: dwc2_hc_n_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (ffffffe00066787e)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffe00066787e-ffffffe000667e08: dwc2_hc_n_intr (STB_LOCAL)
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
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff817c9c10-ffffffff817ca1be: dwc2_hc_n_intr (STB_LOCAL)
ffffffff817cabb6-ffffffff817cac16: dwc2_hc_n_intr.cold (STB_LOCAL)
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
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff818066b0-ffffffff81806c5e: dwc2_hc_n_intr (STB_LOCAL)
ffffffff81807656-ffffffff818076b6: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_n_intr(struct dwc2_hsotg *hsotg, int chnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd_intr.c:2032
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
**Symbols:**

```
ffffffff818207c0-ffffffff81820d6e: dwc2_hc_n_intr (STB_LOCAL)
ffffffff81821762-ffffffff818217c2: dwc2_hc_n_intr.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
