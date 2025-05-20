# Function: <code>genpd_sd_counter_dec</code>

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
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815af2b0)
Location: drivers/base/power/domain.c:89
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_poweron
  - drivers/base/power/domain.c:genpd_poweron
```
**Symbols:**

```
ffffffff815af2b0-ffffffff815af2e3: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815de200)
Location: drivers/base/power/domain.c:188
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_poweron
  - drivers/base/power/domain.c:genpd_poweron
```
**Symbols:**

```
ffffffff815de200-ffffffff815de233: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f2d10)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff815f2d10-ffffffff815f2d33: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165a260)
Location: drivers/base/power/domain.c:197
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff8165a260-ffffffff8165a283: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81695d60)
Location: drivers/base/power/domain.c:198
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81695d60-ffffffff81695d83: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b63b0)
Location: drivers/base/power/domain.c:198
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816b63b0-ffffffff816b63d3: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:201
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816f02a0-ffffffff816f02c3: genpd_sd_counter_dec (STB_LOCAL)
ffffffff816f34ac-ffffffff816f34c1: genpd_sd_counter_dec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81714740)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81714740-ffffffff81714763: genpd_sd_counter_dec (STB_LOCAL)
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
In drivers/base/power/domain.c (ffffffff817d1590)
Location: drivers/base/power/domain.c:196
Inline: True
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff817d1590-ffffffff817d15b0: genpd_sd_counter_dec.isra.0 (STB_LOCAL)
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
In drivers/base/power/domain.c (ffffffff817e5d40)
Location: drivers/base/power/domain.c:197
Inline: True
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff817e5d40-ffffffff817e5d60: genpd_sd_counter_dec.isra.0 (STB_LOCAL)
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
In drivers/base/power/domain.c (ffffffff817ca150)
Location: drivers/base/power/domain.c:197
Inline: True
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff817ca150-ffffffff817ca170: genpd_sd_counter_dec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff818558f6)
Location: drivers/base/power/domain.c:197
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199c9c0)
Location: drivers/base/power/domain.c:200
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0dc10)
Location: drivers/base/power/domain.c:200
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5bcc0)
Location: drivers/base/power/domain.c:200
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa37c0)
Location: drivers/pmdomain/core.c:199
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_power_on
  - drivers/pmdomain/core.c:genpd_power_on
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
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010908858)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
```
**Symbols:**

```
ffff800010908858-ffff8000109088cc: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09efa90)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
```
**Symbols:**

```
c09efa90-c09efb00: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a4960)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
```
**Symbols:**

```
c0000000009a4960-c0000000009a49b4: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058d378)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
```
**Symbols:**

```
ffffffe00058d378-ffffffe00058d3c2: genpd_sd_counter_dec (STB_LOCAL)
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
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816daa70)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816daa70-ffffffff816daa93: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b50f0)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816b50f0-ffffffff816b5113: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81708400)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81708400-ffffffff81708423: genpd_sd_counter_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool genpd_sd_counter_dec(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81722e30)
Location: drivers/base/power/domain.c:196
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81722e30-ffffffff81722e53: genpd_sd_counter_dec (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
