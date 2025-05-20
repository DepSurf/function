# Function: <code>dwc2_hib_restore_common</code>

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
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817700b0)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817700b0-ffffffff8177031d: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81794ea0)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81794ea0-ffffffff8179529a: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817d3710)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817d3710-ffffffff817d3b16: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818045e0)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff818045e0-ffffffff818049e6: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d4b90)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff818d4b90-ffffffff818d4da4: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818deeb0)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff818deeb0-ffffffff818df0c4: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c1f70)
Location: drivers/usb/dwc2/core.c:244
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff818c1f70-ffffffff818c21dc: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:244
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81d18162-ffffffff81d1835a: dwc2_hib_restore_common.cold (STB_LOCAL)
ffffffff81958b00-ffffffff81958f08: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:244
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81ee300a-ffffffff81ee32b0: dwc2_hib_restore_common.cold (STB_LOCAL)
ffffffff81ab29d0-ffffffff81ab2d4a: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:214
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff8209f1cb-ffffffff8209f471: dwc2_hib_restore_common.cold (STB_LOCAL)
ffffffff81c3b0e0-ffffffff81c3b45a: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:214
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff8212077b-ffffffff82120a21: dwc2_hib_restore_common.cold (STB_LOCAL)
ffffffff81ca2490-ffffffff81ca280a: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:214
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff82201f52-ffffffff822021f8: dwc2_hib_restore_common.cold (STB_LOCAL)
ffffffff81d570e0-ffffffff81d5745a: dwc2_hib_restore_common (STB_GLOBAL)
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
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3b498)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffff800010a3b498-ffff800010a3bae4: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0de38)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
c0b0de38-c0b0e390: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af96d0)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
c000000000af96d0-c000000000af9fe0: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe00065693e)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffe00065693e-ffffffe0006571c6: dwc2_hib_restore_common (STB_GLOBAL)
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
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817bc9c0)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817bc9c0-ffffffff817bcdc6: dwc2_hib_restore_common (STB_GLOBAL)
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
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817f9460)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817f9460-ffffffff817f9866: dwc2_hib_restore_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dwc2_hib_restore_common(struct dwc2_hsotg *hsotg, int rem_wakeup, int is_host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818136a0)
Location: drivers/usb/dwc2/core.c:319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff818136a0-ffffffff81813aa6: dwc2_hib_restore_common (STB_GLOBAL)
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
