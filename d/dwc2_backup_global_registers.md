# Function: <code>dwc2_backup_global_registers</code>

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
In drivers/usb/dwc2/core.c (ffffffff81622016)
Location: drivers/usb/dwc2/core.c:249
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
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
In drivers/usb/dwc2/core.c (ffffffff81681e74)
Location: drivers/usb/dwc2/core.c:66
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
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
In drivers/usb/dwc2/core.c (ffffffff816afca3)
Location: drivers/usb/dwc2/core.c:66
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
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
In drivers/usb/dwc2/core.c (ffffffff816c4e5a)
Location: drivers/usb/dwc2/core.c:66
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
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
In drivers/usb/dwc2/core.c (ffffffff8173113a)
Location: drivers/usb/dwc2/core.c:67
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff8176fcd0)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff8176fcd0-ffffffff8176fda4: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81794380)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81794380-ffffffff817944cd: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817d2c70)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817d2c70-ffffffff817d2dbd: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81803b40)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81803b40-ffffffff81803c8d: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d45e0)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff818d45e0-ffffffff818d4730: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818de900)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff818de900-ffffffff818dea50: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c1bb0)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff818c1bb0-ffffffff818c1d1c: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81d17f36-ffffffff81d1801d: dwc2_backup_global_registers.cold (STB_LOCAL)
ffffffff81958540-ffffffff8195877c: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81ee2ddd-ffffffff81ee2ec4: dwc2_backup_global_registers.cold (STB_LOCAL)
ffffffff81ab23d0-ffffffff81ab2618: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:37
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff8209efbe-ffffffff8209f0a5: dwc2_backup_global_registers.cold (STB_LOCAL)
ffffffff81c3aa80-ffffffff81c3acc8: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:37
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff8212056e-ffffffff82120655: dwc2_backup_global_registers.cold (STB_LOCAL)
ffffffff81ca1e30-ffffffff81ca2078: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:37
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff82201d45-ffffffff82201e2c: dwc2_backup_global_registers.cold (STB_LOCAL)
ffffffff81d56a80-ffffffff81d56cc8: dwc2_backup_global_registers (STB_GLOBAL)
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
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3a328)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffff800010a3a328-ffff800010a3a594: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0d5e0)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
c0b0d5e0-c0b0d770: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af75d0)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
c000000000af75d0-c000000000af7c78: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe000655268)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffe000655268-ffffffe000655592: dwc2_backup_global_registers (STB_GLOBAL)
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
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817bbf20)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817bbf20-ffffffff817bc06d: dwc2_backup_global_registers (STB_GLOBAL)
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
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817f89c0)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff817f89c0-ffffffff817f8b0d: dwc2_backup_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dwc2_backup_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81812c00)
Location: drivers/usb/dwc2/core.c:67
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
```
**Symbols:**

```
ffffffff81812c00-ffffffff81812d4d: dwc2_backup_global_registers (STB_GLOBAL)
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
