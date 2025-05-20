# Function: <code>dwc2_host_exit_hibernation</code>

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
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817799d0)
Location: drivers/usb/dwc2/hcd.c:5605
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff817799d0-ffffffff81779c97: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179f950)
Location: drivers/usb/dwc2/hcd.c:5624
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff8179f950-ffffffff8179fcfe: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff817dee20-ffffffff817dee58: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff817de430-ffffffff817de7a0: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff8180fd12-ffffffff8180fd4a: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff8180f380-ffffffff8180f6f0: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff818e09fd-ffffffff818e0a35: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff818e0090-ffffffff818e0400: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5482
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff81c1fa74-ffffffff81c1faac: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff818e9ef0-ffffffff818ea260: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5599
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff81c116c2-ffffffff81c116fa: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff818cb9f0-ffffffff818cbd66: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5604
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff81d1c3f1-ffffffff81d1c611: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff81965090-ffffffff81965550: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5600
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff81ee793b-ffffffff81ee7ba7: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff81abf4a0-ffffffff81abf91e: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5573
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff820a3009-ffffffff820a323d: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff81c48dd0-ffffffff81c49289: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5573
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff821245bd-ffffffff821247f1: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff81cb03b0-ffffffff81cb0869: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5573
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff82205d91-ffffffff82205fc5: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff81d650c0-ffffffff81d65579: dwc2_host_exit_hibernation (STB_GLOBAL)
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a48120)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffff800010a48120-ffff800010a485a8: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b1a850)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
c0b1a850-c0b1acc8: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b0d430)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
c000000000b0d430-c000000000b0db04: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe000664f96)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffe000664f96-ffffffe0006655d2: dwc2_host_exit_hibernation (STB_GLOBAL)
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff817c80f2-ffffffff817c812a: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff817c7760-ffffffff817c7ad0: dwc2_host_exit_hibernation (STB_GLOBAL)
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
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff81804b92-ffffffff81804bca: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff81804200-ffffffff81804570: dwc2_host_exit_hibernation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_host_exit_hibernation(struct dwc2_hsotg *hsotg, int rem_wakeup, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5480
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff8181eca2-ffffffff8181ecda: dwc2_host_exit_hibernation.cold (STB_LOCAL)
ffffffff8181e310-ffffffff8181e680: dwc2_host_exit_hibernation (STB_GLOBAL)
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
