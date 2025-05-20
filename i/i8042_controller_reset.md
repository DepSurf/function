# Function: <code>i8042_controller_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void i8042_controller_reset(bool force_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81665960)
Location: drivers/input/serio/i8042.c:1022
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/serio/i8042.c:i8042_remove
```
**Symbols:**

```
ffffffff81665960-ffffffff816659f5: i8042_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void i8042_controller_reset(bool force_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816c5be0)
Location: drivers/input/serio/i8042.c:1022
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff816c5be0-ffffffff816c5c7c: i8042_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816f3c00)
Location: drivers/input/serio/i8042.c:1052
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff816f3c00-ffffffff816f3c9a: i8042_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817093c0)
Location: drivers/input/serio/i8042.c:1060
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff817093c0-ffffffff8170945c: i8042_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8177a570)
Location: drivers/input/serio/i8042.c:1060
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff8177a570-ffffffff8177a60c: i8042_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1060
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff817bad80-ffffffff817bae08: i8042_controller_reset (STB_LOCAL)
ffffffff817bb951-ffffffff817bb973: i8042_controller_reset.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1063
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff817e21f0-ffffffff817e2278: i8042_controller_reset (STB_LOCAL)
ffffffff817e2dac-ffffffff817e2dce: i8042_controller_reset.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1056
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff81822c80-ffffffff81822d08: i8042_controller_reset (STB_LOCAL)
ffffffff818237de-ffffffff81823800: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1073
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff81854120-ffffffff818541a8: i8042_controller_reset (STB_LOCAL)
ffffffff81854c9a-ffffffff81854cbc: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1075
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff81926360-ffffffff819263eb: i8042_controller_reset (STB_LOCAL)
ffffffff8192713f-ffffffff81927161: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1098
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff8192dee0-ffffffff8192df6b: i8042_controller_reset (STB_LOCAL)
ffffffff81c23006-ffffffff81c23028: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1098
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff819112d0-ffffffff8191135b: i8042_controller_reset (STB_LOCAL)
ffffffff81c1512f-ffffffff81c15151: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1102
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff819b29b0-ffffffff819b2a4b: i8042_controller_reset (STB_LOCAL)
ffffffff81d22c25-ffffffff81d22c5c: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1102
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff81b11c40-ffffffff81b11d5d: i8042_controller_reset (STB_LOCAL)
ffffffff81eee8a6-ffffffff81eee904: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1102
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff81ca2800-ffffffff81ca2943: i8042_controller_reset (STB_LOCAL)
ffffffff820a63f6-ffffffff820a6432: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1102
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff81d09ec0-ffffffff81d0a003: i8042_controller_reset (STB_LOCAL)
ffffffff821277fd-ffffffff82127839: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1102
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff81dbfb50-ffffffff81dbfc93: i8042_controller_reset (STB_LOCAL)
ffffffff8220917e-ffffffff822091ba: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c000000000b71640)
Location: drivers/input/serio/i8042.c:1073
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
c000000000b71640-c000000000b71748: i8042_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1073
Inline: True
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
```
**Symbols:**

```
ffffffff81809350-ffffffff818093c9: i8042_controller_reset.constprop.0 (STB_LOCAL)
ffffffff81809d18-ffffffff81809d3a: i8042_controller_reset.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1073
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff817d08e0-ffffffff817d0968: i8042_controller_reset (STB_LOCAL)
ffffffff817d144a-ffffffff817d146c: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1073
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff818482b0-ffffffff81848338: i8042_controller_reset (STB_LOCAL)
ffffffff81848e2a-ffffffff81848e4c: i8042_controller_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void i8042_controller_reset(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1073
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_remove
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_shutdown
  - drivers/input/serio/i8042.c:i8042_pm_reset
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
**Symbols:**

```
ffffffff81863530-ffffffff818635b8: i8042_controller_reset (STB_LOCAL)
ffffffff8186404a-ffffffff8186406c: i8042_controller_reset.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool s2r_wants_reset</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_reset</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
