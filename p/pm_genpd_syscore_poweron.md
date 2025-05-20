# Function: <code>pm_genpd_syscore_poweron</code>

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
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815b0090)
Location: drivers/base/power/domain.c:978
Inline: False
```
**Symbols:**

```
ffffffff815b0090-ffffffff815b00a2: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815defc0)
Location: drivers/base/power/domain.c:1088
Inline: False
```
**Symbols:**

```
ffffffff815defc0-ffffffff815defd2: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f3bd0)
Location: drivers/base/power/domain.c:1170
Inline: False
```
**Symbols:**

```
ffffffff815f3bd0-ffffffff815f3be2: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165ba00)
Location: drivers/base/power/domain.c:1293
Inline: False
```
**Symbols:**

```
ffffffff8165ba00-ffffffff8165ba12: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816976e0)
Location: drivers/base/power/domain.c:1299
Inline: False
```
**Symbols:**

```
ffffffff816976e0-ffffffff816976f2: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b83c0)
Location: drivers/base/power/domain.c:1378
Inline: False
```
**Symbols:**

```
ffffffff816b83c0-ffffffff816b83d2: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f2110)
Location: drivers/base/power/domain.c:1381
Inline: False
```
**Symbols:**

```
ffffffff816f2110-ffffffff816f2122: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81716890)
Location: drivers/base/power/domain.c:1376
Inline: False
```
**Symbols:**

```
ffffffff81716890-ffffffff817168a2: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d2560)
Location: drivers/base/power/domain.c:1365
Inline: False
```
**Symbols:**

```
ffffffff817d2560-ffffffff817d25ce: pm_genpd_syscore_poweron (STB_GLOBAL)
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
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010909058)
Location: drivers/base/power/domain.c:1376
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_resume
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_resume
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_resume
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_resume
```
**Symbols:**

```
ffff800010909058-ffff800010909088: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f2b44)
Location: drivers/base/power/domain.c:1376
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_resume
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_resume
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_resume
  - drivers/clocksource/sh_tmu.c:sh_tmu_clock_event_resume
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_resume
```
**Symbols:**

```
c09f2b44-c09f2b64: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a7f90)
Location: drivers/base/power/domain.c:1376
Inline: False
```
**Symbols:**

```
c0000000009a7f90-c0000000009a7fa8: pm_genpd_syscore_poweron (STB_GLOBAL)
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
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dcbc0)
Location: drivers/base/power/domain.c:1376
Inline: False
```
**Symbols:**

```
ffffffff816dcbc0-ffffffff816dcbd2: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b7240)
Location: drivers/base/power/domain.c:1376
Inline: False
```
**Symbols:**

```
ffffffff816b7240-ffffffff816b7252: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170a550)
Location: drivers/base/power/domain.c:1376
Inline: False
```
**Symbols:**

```
ffffffff8170a550-ffffffff8170a562: pm_genpd_syscore_poweron (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_genpd_syscore_poweron(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81725250)
Location: drivers/base/power/domain.c:1376
Inline: False
```
**Symbols:**

```
ffffffff81725250-ffffffff81725262: pm_genpd_syscore_poweron (STB_GLOBAL)
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
