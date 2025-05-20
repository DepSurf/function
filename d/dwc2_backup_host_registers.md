# Function: <code>dwc2_backup_host_registers</code>

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
In drivers/usb/dwc2/core.c (ffffffff816220dc)
Location: drivers/usb/dwc2/core.c:67
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8168aaa0)
Location: drivers/usb/dwc2/hcd.c:5242
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff8168aaa0-ffffffff8168ab5b: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b8bc0)
Location: drivers/usb/dwc2/hcd.c:5241
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff816b8bc0-ffffffff816b8c73: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816ccf00)
Location: drivers/usb/dwc2/hcd.c:5334
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff816ccf00-ffffffff816ccfb5: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817394f0)
Location: drivers/usb/dwc2/hcd.c:5348
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
**Symbols:**

```
ffffffff817394f0-ffffffff817395ab: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817795b0)
Location: drivers/usb/dwc2/hcd.c:5431
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817795b0-ffffffff81779676: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179f370)
Location: drivers/usb/dwc2/hcd.c:5450
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff8179f370-ffffffff8179f478: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817ddee0)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817ddee0-ffffffff817ddfe8: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8180ee30)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff8180ee30-ffffffff8180ef38: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818dfb30)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff818dfb30-ffffffff818dfc3b: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e9990)
Location: drivers/usb/dwc2/hcd.c:5308
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff818e9990-ffffffff818e9a9b: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818cb470)
Location: drivers/usb/dwc2/hcd.c:5425
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff818cb470-ffffffff818cb585: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5430
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81d1bf69-ffffffff81d1bfe7: dwc2_backup_host_registers.cold (STB_LOCAL)
ffffffff81964790-ffffffff8196494d: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5426
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81ee73ac-ffffffff81ee742a: dwc2_backup_host_registers.cold (STB_LOCAL)
ffffffff81abec90-ffffffff81abee59: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5399
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff820a2af9-ffffffff820a2b77: dwc2_backup_host_registers.cold (STB_LOCAL)
ffffffff81c48510-ffffffff81c486d9: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5399
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff821240b9-ffffffff82124131: dwc2_backup_host_registers.cold (STB_LOCAL)
ffffffff81cafae0-ffffffff81cafcb6: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5399
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff8220588d-ffffffff82205905: dwc2_backup_host_registers.cold (STB_LOCAL)
ffffffff81d647f0-ffffffff81d649c6: dwc2_backup_host_registers (STB_GLOBAL)
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
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a478f8)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffff800010a478f8-ffff800010a47ab0: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b1a0a8)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
c0b1a0a8-c0b1a1e8: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b0c560)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
c000000000b0c560-c000000000b0c908: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe0006643aa)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffe0006643aa-ffffffe0006645bc: dwc2_backup_host_registers (STB_GLOBAL)
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
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c7210)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817c7210-ffffffff817c7318: dwc2_backup_host_registers (STB_GLOBAL)
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
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81803cb0)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81803cb0-ffffffff81803db8: dwc2_backup_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dwc2_backup_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8181ddc0)
Location: drivers/usb/dwc2/hcd.c:5306
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff8181ddc0-ffffffff8181dec8: dwc2_backup_host_registers (STB_GLOBAL)
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
