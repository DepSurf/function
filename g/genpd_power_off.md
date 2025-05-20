# Function: <code>genpd_power_off</code>

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
int genpd_power_off(struct generic_pm_domain *genpd, bool timed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815af100)
Location: drivers/base/power/domain.c:135
Inline: False
```
**Symbols:**

```
ffffffff815af100-ffffffff815af1d1: genpd_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool timed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815de070)
Location: drivers/base/power/domain.c:234
Inline: False
```
**Symbols:**

```
ffffffff815de070-ffffffff815de13d: genpd_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f4220)
Location: drivers/base/power/domain.c:295
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff815f4220-ffffffff815f43f6: genpd_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165c0a0)
Location: drivers/base/power/domain.c:422
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff8165c0a0-ffffffff8165c28c: genpd_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81697df0)
Location: drivers/base/power/domain.c:423
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81697df0-ffffffff81697fe0: genpd_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b8600)
Location: drivers/base/power/domain.c:498
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816b8600-ffffffff816b8811: genpd_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f26a8)
Location: drivers/base/power/domain.c:499
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816f2640-ffffffff816f2841: genpd_power_off (STB_LOCAL)
ffffffff816f3563-ffffffff816f3582: genpd_power_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81716b78)
Location: drivers/base/power/domain.c:494
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81716b10-ffffffff81716d11: genpd_power_off (STB_LOCAL)
ffffffff81717968-ffffffff81717987: genpd_power_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d30f2)
Location: drivers/base/power/domain.c:494
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff817d2b60-ffffffff817d2d88: genpd_power_off.part.0.isra.0 (STB_LOCAL)
ffffffff817d3535-ffffffff817d3555: genpd_power_off.part.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e7c22)
Location: drivers/base/power/domain.c:547
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff817e7670-ffffffff817e78b2: genpd_power_off.part.0.isra.0 (STB_LOCAL)
ffffffff81c0f053-ffffffff81c0f073: genpd_power_off.part.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817cbd12)
Location: drivers/base/power/domain.c:579
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff817cb760-ffffffff817cb9a2: genpd_power_off.part.0.isra.0 (STB_LOCAL)
ffffffff81c011bd-ffffffff81c011dd: genpd_power_off.part.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81856391)
Location: drivers/base/power/domain.c:613
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81855d40-ffffffff81855faa: genpd_power_off.part.0.isra.0 (STB_LOCAL)
ffffffff81d04024-ffffffff81d0406a: genpd_power_off.part.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:621
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff8199c2f0-ffffffff8199c586: genpd_power_off.isra.0 (STB_LOCAL)
ffffffff81ecc8f5-ffffffff81ecc952: genpd_power_off.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:643
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81b0d4d0-ffffffff81b0d792: genpd_power_off.isra.0 (STB_LOCAL)
ffffffff82098a02-ffffffff82098a2d: genpd_power_off.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:669
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81b5b580-ffffffff81b5b842: genpd_power_off.isra.0 (STB_LOCAL)
ffffffff821199b9-ffffffff821199e4: genpd_power_off.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pmdomain/core.c (0)
Location: drivers/pmdomain/core.c:676
Inline: True
Direct callers:
  - drivers/pmdomain/core.c:genpd_runtime_resume
  - drivers/pmdomain/core.c:genpd_runtime_suspend
  - drivers/pmdomain/core.c:genpd_power_off_work_fn
  - drivers/pmdomain/core.c:genpd_power_on
```
**Symbols:**

```
ffffffff81aa3080-ffffffff81aa3342: genpd_power_off.isra.0 (STB_LOCAL)
ffffffff821f20ca-ffffffff821f20f5: genpd_power_off.isra.0.cold (STB_LOCAL)
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
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff8000109088d0)
Location: drivers/base/power/domain.c:494
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
```
**Symbols:**

```
ffff8000109088d0-ffff800010908b48: genpd_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f2d44)
Location: drivers/base/power/domain.c:494
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
```
**Symbols:**

```
c09f2d44-c09f2fe4: genpd_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a9690)
Location: drivers/base/power/domain.c:494
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
```
**Symbols:**

```
c0000000009a8470-c0000000009a87e4: genpd_power_off.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058f438)
Location: drivers/base/power/domain.c:494
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
```
**Symbols:**

```
ffffffe00058f438-ffffffe00058f64a: genpd_power_off (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dcea8)
Location: drivers/base/power/domain.c:494
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816dce40-ffffffff816dd041: genpd_power_off (STB_LOCAL)
ffffffff816ddc98-ffffffff816ddcb7: genpd_power_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b7628)
Location: drivers/base/power/domain.c:494
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816b75c0-ffffffff816b77c1: genpd_power_off (STB_LOCAL)
ffffffff816b82fc-ffffffff816b831b: genpd_power_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170a838)
Location: drivers/base/power/domain.c:494
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff8170a7d0-ffffffff8170a9d1: genpd_power_off (STB_LOCAL)
ffffffff8170b628-ffffffff8170b647: genpd_power_off.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genpd_power_off(struct generic_pm_domain *genpd, bool one_dev_on, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817257b8)
Location: drivers/base/power/domain.c:494
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off_work_fn
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81725750-ffffffff81725951: genpd_power_off (STB_LOCAL)
ffffffff81726015-ffffffff81726034: genpd_power_off.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool one_dev_on</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int depth</code>
</li>
<li>
<b>Param removed. </b>
<code>bool timed</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
