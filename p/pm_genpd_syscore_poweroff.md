# Function: <code>pm_genpd_syscore_poweroff</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815b0070)
Location: drivers/base/power/domain.c:972
Inline: False
```
**Symbols:**

```
ffffffff815b0070-ffffffff815b0085: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815defa0)
Location: drivers/base/power/domain.c:1082
Inline: False
```
**Symbols:**

```
ffffffff815defa0-ffffffff815defb5: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f3bb0)
Location: drivers/base/power/domain.c:1164
Inline: False
```
**Symbols:**

```
ffffffff815f3bb0-ffffffff815f3bc5: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165b9e0)
Location: drivers/base/power/domain.c:1287
Inline: False
```
**Symbols:**

```
ffffffff8165b9e0-ffffffff8165b9f5: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816976c0)
Location: drivers/base/power/domain.c:1293
Inline: False
```
**Symbols:**

```
ffffffff816976c0-ffffffff816976d5: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b83a0)
Location: drivers/base/power/domain.c:1372
Inline: False
```
**Symbols:**

```
ffffffff816b83a0-ffffffff816b83b5: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f20f0)
Location: drivers/base/power/domain.c:1375
Inline: False
```
**Symbols:**

```
ffffffff816f20f0-ffffffff816f2105: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81716870)
Location: drivers/base/power/domain.c:1370
Inline: False
```
**Symbols:**

```
ffffffff81716870-ffffffff81716885: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d25d0)
Location: drivers/base/power/domain.c:1359
Inline: False
```
**Symbols:**

```
ffffffff817d25d0-ffffffff817d262a: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010909028)
Location: drivers/base/power/domain.c:1370
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_suspend
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_suspend
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_suspend
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_suspend
```
**Symbols:**

```
ffff800010909028-ffff800010909058: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f2b24)
Location: drivers/base/power/domain.c:1370
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_suspend
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_suspend
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_suspend
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_suspend
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_suspend
```
**Symbols:**

```
c09f2b24-c09f2b44: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a7f70)
Location: drivers/base/power/domain.c:1370
Inline: False
```
**Symbols:**

```
c0000000009a7f70-c0000000009a7f88: pm_genpd_syscore_poweroff (STB_GLOBAL)
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
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dcba0)
Location: drivers/base/power/domain.c:1370
Inline: False
```
**Symbols:**

```
ffffffff816dcba0-ffffffff816dcbb5: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b7220)
Location: drivers/base/power/domain.c:1370
Inline: False
```
**Symbols:**

```
ffffffff816b7220-ffffffff816b7235: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170a530)
Location: drivers/base/power/domain.c:1370
Inline: False
```
**Symbols:**

```
ffffffff8170a530-ffffffff8170a545: pm_genpd_syscore_poweroff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_genpd_syscore_poweroff(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81725230)
Location: drivers/base/power/domain.c:1370
Inline: False
```
**Symbols:**

```
ffffffff81725230-ffffffff81725245: pm_genpd_syscore_poweroff (STB_GLOBAL)
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
