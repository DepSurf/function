# Function: <code>dwc2_restore_global_registers</code>

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
In drivers/usb/dwc2/core.c (ffffffff81621db2)
Location: drivers/usb/dwc2/core.c:279
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
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
In drivers/usb/dwc2/core.c (ffffffff81681d06)
Location: drivers/usb/dwc2/core.c:96
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
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
In drivers/usb/dwc2/core.c (ffffffff816afb35)
Location: drivers/usb/dwc2/core.c:96
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
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
In drivers/usb/dwc2/core.c (ffffffff816c4cdf)
Location: drivers/usb/dwc2/core.c:96
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
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
In drivers/usb/dwc2/core.c (ffffffff81730fbf)
Location: drivers/usb/dwc2/core.c:97
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff8176fdb0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff8176fdb0-ffffffff8176feba: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817944d0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817944d0-ffffffff817946cd: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817d4242-ffffffff817d4262: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff817d2dc0-ffffffff817d2fab: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81805112-ffffffff81805132: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff81803c90-ffffffff81803e7b: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff818d5af8-ffffffff818d5b18: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff818d4730-ffffffff818d4913: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81c1ebfa-ffffffff81c1ec1a: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff818dea50-ffffffff818dec33: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81c10a8b-ffffffff81c10aab: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff818c1d20-ffffffff818c1f12: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81d1801d-ffffffff81d1814e: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff81958780-ffffffff81958a71: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff81ee2ec4-ffffffff81ee2ff5: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff81ab2620-ffffffff81ab2913: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:69
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff8209f0a5-ffffffff8209f1b6: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff81c3ace0-ffffffff81c3aff6: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:69
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff82120655-ffffffff82120766: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff81ca2090-ffffffff81ca23a6: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:69
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff82201e2c-ffffffff82201f3d: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff81d56ce0-ffffffff81d56ff6: dwc2_restore_global_registers (STB_GLOBAL)
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
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3a598)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffff800010a3a598-ffff800010a3a8c0: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0d770)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
c0b0d770-c0b0dae0: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000af7c80)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
c000000000af7c80-c000000000af80dc: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe000655592)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffe000655592-ffffffe000655a70: dwc2_restore_global_registers (STB_GLOBAL)
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
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817bd4f2-ffffffff817bd512: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff817bc070-ffffffff817bc25b: dwc2_restore_global_registers (STB_GLOBAL)
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
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff817f9f92-ffffffff817f9fb2: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff817f8b10-ffffffff817f8cfb: dwc2_restore_global_registers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_restore_global_registers(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:99
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
```
**Symbols:**

```
ffffffff818141d2-ffffffff818141f2: dwc2_restore_global_registers.cold (STB_LOCAL)
ffffffff81812d50-ffffffff81812f3b: dwc2_restore_global_registers (STB_GLOBAL)
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
