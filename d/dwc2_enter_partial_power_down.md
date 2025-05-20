# Function: <code>dwc2_enter_partial_power_down</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff8176ffb0)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffff8176ffb0-ffffffff817700b0: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81794830)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffff81794830-ffffffff817949b5: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffff817d42a4-ffffffff817d42e3: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff817d30d0-ffffffff817d3212: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffff81805174-ffffffff818051b3: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff81803fa0-ffffffff818040e2: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffff818d5b5a-ffffffff818d5b99: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff818d4a40-ffffffff818d4b82: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffff81c1ec5c-ffffffff81c1ec9b: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff818ded60-ffffffff818deea2: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c1f40)
Location: drivers/usb/dwc2/core.c:161
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff818c1f40-ffffffff818c1f6a: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:161
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff81d1814e-ffffffff81d18162: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff81958aa0-ffffffff81958af2: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:161
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff81ee2ff5-ffffffff81ee300a: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff81ab2960-ffffffff81ab29c9: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:131
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff8209f1b6-ffffffff8209f1cb: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff81c3b060-ffffffff81c3b0c9: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:131
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff82120766-ffffffff8212077b: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff81ca2410-ffffffff81ca2479: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:131
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
```
**Symbols:**

```
ffffffff82201f3d-ffffffff82201f52: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff81d57060-ffffffff81d570c9: dwc2_enter_partial_power_down (STB_GLOBAL)
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
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3aa88)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffff800010a3aa88-ffff800010a3ac70: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0dc88)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
c0b0dc88-c0b0de38: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af8480)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
c000000000af8480-c000000000af8764: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe000655d0c)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffe000655d0c-ffffffe000655f70: dwc2_enter_partial_power_down (STB_GLOBAL)
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
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffff817bd554-ffffffff817bd593: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff817bc380-ffffffff817bc4c2: dwc2_enter_partial_power_down (STB_GLOBAL)
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
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffff817f9ff4-ffffffff817fa033: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff817f8e20-ffffffff817f8f62: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_enter_partial_power_down(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:189
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
**Symbols:**

```
ffffffff81814234-ffffffff81814273: dwc2_enter_partial_power_down.cold (STB_LOCAL)
ffffffff81813060-ffffffff818131a2: dwc2_enter_partial_power_down (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
