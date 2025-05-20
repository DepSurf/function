# Function: <code>dpm_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8155b100)
Location: drivers/base/power/main.c:1496
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff8155b100-ffffffff8155b3dc: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ad110)
Location: drivers/base/power/main.c:1502
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff815ad110-ffffffff815ad3e5: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815dbed0)
Location: drivers/base/power/main.c:1577
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff815dbed0-ffffffff815dc1a8: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815f0a50)
Location: drivers/base/power/main.c:1580
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff815f0a50-ffffffff815f0d28: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81657fa0)
Location: drivers/base/power/main.c:1667
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81657fa0-ffffffff8165827e: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1844
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff8169452a-ffffffff81694577: dpm_suspend.cold.25 (STB_LOCAL)
ffffffff81693a20-ffffffff81693c84: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1849
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff816b4baa-ffffffff816b4bf7: dpm_suspend.cold.26 (STB_LOCAL)
ffffffff816b40a0-ffffffff816b4309: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816edef0)
Location: drivers/base/power/main.c:1836
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff816edef0-ffffffff816ee1a4: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81711ed0)
Location: drivers/base/power/main.c:1857
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81711ed0-ffffffff81712184: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1739
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff817ce302-ffffffff817ce34f: dpm_suspend.cold (STB_LOCAL)
ffffffff817cd900-ffffffff817cdb36: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1738
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81c0eed5-ffffffff81c0ef22: dpm_suspend.cold (STB_LOCAL)
ffffffff817e2280-ffffffff817e2492: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1739
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81c0104e-ffffffff81c0109b: dpm_suspend.cold (STB_LOCAL)
ffffffff817c6660-ffffffff817c6872: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1758
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81d03df8-ffffffff81d03e5d: dpm_suspend.cold (STB_LOCAL)
ffffffff818509f0-ffffffff81850c2f: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1754
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81ecc670-ffffffff81ecc6d5: dpm_suspend.cold (STB_LOCAL)
ffffffff81996420-ffffffff81996696: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b070a0)
Location: drivers/base/power/main.c:1754
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81b070a0-ffffffff81b0738f: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b550f0)
Location: drivers/base/power/main.c:1754
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81b550f0-ffffffff81b553df: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81bad6b0)
Location: drivers/base/power/main.c:1753
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81bad6b0-ffffffff81bad99f: dpm_suspend (STB_GLOBAL)
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
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000109028e0)
Location: drivers/base/power/main.c:1857
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffff8000109028e0-ffff800010902bbc: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09ecc4c)
Location: drivers/base/power/main.c:1857
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
c09ecc4c-c09ecf50: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c0000000009a0cd0)
Location: drivers/base/power/main.c:1857
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
c0000000009a0cd0-c0000000009a10f8: dpm_suspend (STB_GLOBAL)
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
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d8250)
Location: drivers/base/power/main.c:1857
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff816d8250-ffffffff816d8504: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b28b0)
Location: drivers/base/power/main.c:1857
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff816b28b0-ffffffff816b2b64: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81705b90)
Location: drivers/base/power/main.c:1857
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81705b90-ffffffff81705e44: dpm_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dpm_suspend(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81720540)
Location: drivers/base/power/main.c:1857
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/power/main.c:dpm_suspend_start
```
**Symbols:**

```
ffffffff81720540-ffffffff8172081c: dpm_suspend (STB_GLOBAL)
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
