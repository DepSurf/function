# Function: <code>dwc2_restore_host_registers</code>

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
In drivers/usb/dwc2/core.c (ffffffff81621daa)
Location: drivers/usb/dwc2/core.c:95
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8168ab60)
Location: drivers/usb/dwc2/hcd.c:5270
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff8168ab60-ffffffff8168ac4b: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b8c80)
Location: drivers/usb/dwc2/hcd.c:5269
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff816b8c80-ffffffff816b8d63: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816ccfc0)
Location: drivers/usb/dwc2/hcd.c:5362
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff816ccfc0-ffffffff816cd0a5: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817395b0)
Location: drivers/usb/dwc2/hcd.c:5376
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
**Symbols:**

```
ffffffff817395b0-ffffffff8173969b: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81779680)
Location: drivers/usb/dwc2/hcd.c:5460
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81779680-ffffffff81779776: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179f480)
Location: drivers/usb/dwc2/hcd.c:5479
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff8179f480-ffffffff8179f5e5: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817dedb6-ffffffff817dedd6: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff817ddff0-ffffffff817de13f: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff8180fca8-ffffffff8180fcc8: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff8180ef40-ffffffff8180f08f: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff818e0993-ffffffff818e09b3: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff818dfc40-ffffffff818dfd92: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5337
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81c1fa0a-ffffffff81c1fa2a: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff818e9aa0-ffffffff818e9bf2: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5454
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81c11658-ffffffff81c11678: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff818cb590-ffffffff818cb6d9: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5459
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81d1bfe7-ffffffff81d1c09a: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff81964950-ffffffff81964b6a: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5455
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81ee742a-ffffffff81ee74dd: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff81abee60-ffffffff81abf086: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5428
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff820a2b77-ffffffff820a2c0a: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff81c486f0-ffffffff81c4893a: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5428
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff82124131-ffffffff821241be: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff81cafcd0-ffffffff81caff18: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5428
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff82205905-ffffffff82205992: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff81d649e0-ffffffff81d64c28: dwc2_restore_host_registers (STB_GLOBAL)
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
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a47ab0)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffff800010a47ab0-ffff800010a47cb4: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b1a1e8)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
c0b1a1e8-c0b1a408: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b0c910)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
c000000000b0c910-c000000000b0cbec: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe0006645bc)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffe0006645bc-ffffffe0006648ca: dwc2_restore_host_registers (STB_GLOBAL)
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
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817c8088-ffffffff817c80a8: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff817c7320-ffffffff817c746f: dwc2_restore_host_registers (STB_GLOBAL)
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
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81804b28-ffffffff81804b48: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff81803dc0-ffffffff81803f0f: dwc2_restore_host_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_host_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:5335
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff8181ec38-ffffffff8181ec58: dwc2_restore_host_registers.cold (STB_LOCAL)
ffffffff8181ded0-ffffffff8181e01f: dwc2_restore_host_registers (STB_GLOBAL)
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
