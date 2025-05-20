# Function: <code>pm_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810ce9e0)
Location: kernel/power/suspend.c:528
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810ce9e0-ffffffff810cedd7: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810d34f0)
Location: kernel/power/suspend.c:529
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810d34f0-ffffffff810d3880: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810da080)
Location: kernel/power/suspend.c:552
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810da080-ffffffff810da410: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810d9160)
Location: kernel/power/suspend.c:575
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810d9160-ffffffff810d9500: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810e12c0)
Location: kernel/power/suspend.c:599
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810e12c0-ffffffff810e166b: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:604
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810e9959-ffffffff810e9ce2: pm_suspend.cold.6 (STB_LOCAL)
ffffffff810e9810-ffffffff810e9863: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff810f4f79)
Location: kernel/power/suspend.c:610
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810f4f79-ffffffff810f5302: pm_suspend.cold.7 (STB_LOCAL)
ffffffff810f4e30-ffffffff810f4e83: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff810fd495)
Location: kernel/power/suspend.c:615
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810fd495-ffffffff810fd7f8: pm_suspend.cold (STB_LOCAL)
ffffffff810fd350-ffffffff810fd3a5: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff811098e1)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff811098e1-ffffffff81109c44: pm_suspend.cold (STB_LOCAL)
ffffffff81109770-ffffffff811097c5: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff8111476e)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff8111476e-ffffffff811147db: pm_suspend.cold (STB_LOCAL)
ffffffff811143a0-ffffffff811143c6: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff81bdefff)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81bdefff-ffffffff81bdf06c: pm_suspend.cold (STB_LOCAL)
ffffffff81110fe0-ffffffff81111006: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff81bd1152)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81bd1152-ffffffff81bd11bf: pm_suspend.cold (STB_LOCAL)
ffffffff81111a40-ffffffff81111a66: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff8113191c)
Location: kernel/power/suspend.c:603
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81ca9cfc-ffffffff81ca9d08: pm_suspend.cold (STB_LOCAL)
ffffffff811318f0-ffffffff811319a9: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff81153505)
Location: kernel/power/suspend.c:604
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81e59cde-ffffffff81e59cea: pm_suspend.cold (STB_LOCAL)
ffffffff811534d0-ffffffff81153595: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81182900)
Location: kernel/power/suspend.c:611
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81182900-ffffffff811829d3: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff811937b0)
Location: kernel/power/suspend.c:611
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff811937b0-ffffffff81193883: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff811a21a0)
Location: kernel/power/suspend.c:611
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff811a21a0-ffffffff811a2273: pm_suspend (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffff800010171008)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
  - drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_isr
```
**Symbols:**

```
ffff800010171008-ffff800010171404: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (c03bbb20)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
c03bbb20-c03bbf4c: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (c0000000001c9490)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:state_store
```
**Symbols:**

```
c0000000001c9490-c0000000001c99c0: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (0)
Location: include/linux/suspend.h:344
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (0)
Location: include/linux/suspend.h:344
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff810f2dce)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810f2dce-ffffffff810f3131: pm_suspend.cold (STB_LOCAL)
ffffffff810f2c50-ffffffff810f2ca5: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff810ffdb1)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff810ffdb1-ffffffff81100114: pm_suspend.cold (STB_LOCAL)
ffffffff810ffc40-ffffffff810ffc95: pm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pm_suspend(suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (ffffffff8110b151)
Location: kernel/power/suspend.c:605
Inline: True
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff8110b151-ffffffff8110b4b4: pm_suspend.cold (STB_LOCAL)
ffffffff8110afe0-ffffffff8110b035: pm_suspend (STB_GLOBAL)
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
