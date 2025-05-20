# Function: <code>dpm_suspend_late</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8155ada0)
Location: drivers/base/power/main.c:1246
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff8155ada0-ffffffff8155b09b: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815acdb0)
Location: drivers/base/power/main.c:1251
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff815acdb0-ffffffff815ad09f: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815dbb60)
Location: drivers/base/power/main.c:1309
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff815dbb60-ffffffff815dbe52: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815f0700)
Location: drivers/base/power/main.c:1312
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff815f0700-ffffffff815f09ef: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81657c40)
Location: drivers/base/power/main.c:1404
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81657c40-ffffffff81657f39: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1583
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff816944dd-ffffffff8169452a: dpm_suspend_late.cold.24 (STB_LOCAL)
ffffffff81693750-ffffffff816939c0: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1585
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff816b4b5d-ffffffff816b4baa: dpm_suspend_late.cold.25 (STB_LOCAL)
ffffffff816b3dd0-ffffffff816b4040: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816edbb0)
Location: drivers/base/power/main.c:1568
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff816edbb0-ffffffff816ede61: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81711b90)
Location: drivers/base/power/main.c:1589
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81711b90-ffffffff81711e41: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1467
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff817ce2b5-ffffffff817ce302: dpm_suspend_late.cold (STB_LOCAL)
ffffffff817cd580-ffffffff817cd7f5: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1466
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81c0ee88-ffffffff81c0eed5: dpm_suspend_late.cold (STB_LOCAL)
ffffffff817e1f20-ffffffff817e2171: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1467
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81c01001-ffffffff81c0104e: dpm_suspend_late.cold (STB_LOCAL)
ffffffff817c6320-ffffffff817c656d: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1481
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81d03d93-ffffffff81d03df8: dpm_suspend_late.cold (STB_LOCAL)
ffffffff81850680-ffffffff81850900: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1476
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81ecc60b-ffffffff81ecc670: dpm_suspend_late.cold (STB_LOCAL)
ffffffff81996070-ffffffff8199632c: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b06c50)
Location: drivers/base/power/main.c:1476
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81b06c50-ffffffff81b06f8b: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b54c90)
Location: drivers/base/power/main.c:1476
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81b54c90-ffffffff81b54fd7: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81bad250)
Location: drivers/base/power/main.c:1475
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81bad250-ffffffff81bad597: dpm_suspend_late (STB_GLOBAL)
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
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff800010902558)
Location: drivers/base/power/main.c:1589
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffff800010902558-ffff800010902844: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09ec8a0)
Location: drivers/base/power/main.c:1589
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
c09ec8a0-c09ecbb4: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c0000000009a07a0)
Location: drivers/base/power/main.c:1589
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
c0000000009a07a0-c0000000009a0bc8: dpm_suspend_late (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d7f10)
Location: drivers/base/power/main.c:1589
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff816d7f10-ffffffff816d81c1: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b2570)
Location: drivers/base/power/main.c:1589
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff816b2570-ffffffff816b2821: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81705850)
Location: drivers/base/power/main.c:1589
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81705850-ffffffff81705b01: dpm_suspend_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dpm_suspend_late(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817201e0)
Location: drivers/base/power/main.c:1589
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff817201e0-ffffffff817204be: dpm_suspend_late (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
