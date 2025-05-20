# Function: <code>dwc2_hcd_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8162a2f0)
Location: drivers/usb/dwc2/hcd.c:2990
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff8162a2f0-ffffffff8162a98d: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8168a200)
Location: drivers/usb/dwc2/hcd.c:4970
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff8168a200-ffffffff8168a989: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b8370)
Location: drivers/usb/dwc2/hcd.c:4970
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff816b8370-ffffffff816b8aa4: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816cc630)
Location: drivers/usb/dwc2/hcd.c:5052
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff816cc630-ffffffff816ccde5: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81738bb0)
Location: drivers/usb/dwc2/hcd.c:5067
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81738bb0-ffffffff817393dd: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81778c00)
Location: drivers/usb/dwc2/hcd.c:5133
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81778c00-ffffffff8177948b: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179eba0)
Location: drivers/usb/dwc2/hcd.c:5152
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff8179eba0-ffffffff8179f25f: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff817decf2-ffffffff817dedb6: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff817dd7a0-ffffffff817dddc9: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff8180fbe4-ffffffff8180fca8: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff8180e6d0-ffffffff8180ed15: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff818e08cf-ffffffff818e0993: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff818df370-ffffffff818df9e3: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5011
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81c1f946-ffffffff81c1fa0a: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff818e91d0-ffffffff818e9843: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5128
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81c11594-ffffffff81c11658: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff818cacb0-ffffffff818cb31f: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5129
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81d1bd96-ffffffff81d1bf21: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff81963f20-ffffffff81964602: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5125
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81ee71b2-ffffffff81ee7345: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff81abe410-ffffffff81abeb18: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5096
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff820a29c0-ffffffff820a2a92: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff81c47b90-ffffffff81c48373: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5096
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff82123f80-ffffffff82124052: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff81caf170-ffffffff81caf944: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5096
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff82205757-ffffffff82205826: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff81d63e20-ffffffff81d6465f: dwc2_hcd_init (STB_GLOBAL)
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
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a47220)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffff800010a47220-ffff800010a477e8: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b19924)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
c0b19924-c0b19f78: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b0bc30)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
c000000000b0bc30-c000000000b0c3f0: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe000663cae)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffe000663cae-ffffffe000664286: dwc2_hcd_init (STB_GLOBAL)
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
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff817c7fc4-ffffffff817c8088: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff817c6ab0-ffffffff817c70f5: dwc2_hcd_init (STB_GLOBAL)
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
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81804a64-ffffffff81804b28: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff81803550-ffffffff81803b95: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5009
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff8181eb74-ffffffff8181ec38: dwc2_hcd_init.cold (STB_LOCAL)
ffffffff8181d660-ffffffff8181dca5: dwc2_hcd_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int irq</code>
</li>
</ul>
</details>
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
