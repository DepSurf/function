# Function: <code>genpd_power_on</code>

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
int genpd_power_on(struct generic_pm_domain *genpd, bool timed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815af1e0)
Location: drivers/base/power/domain.c:105
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweron
```
**Symbols:**

```
ffffffff815af1e0-ffffffff815af2a2: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, bool timed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815de140)
Location: drivers/base/power/domain.c:204
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweron
```
**Symbols:**

```
ffffffff815de140-ffffffff815de200: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f4400)
Location: drivers/base/power/domain.c:383
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff815f4400-ffffffff815f4526: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165c290)
Location: drivers/base/power/domain.c:509
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff8165c290-ffffffff8165c3dc: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81697fe0)
Location: drivers/base/power/domain.c:510
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81697fe0-ffffffff81698129: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b8820)
Location: drivers/base/power/domain.c:589
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816b8820-ffffffff816b8969: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f2850)
Location: drivers/base/power/domain.c:592
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816f2850-ffffffff816f2997: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81717000)
Location: drivers/base/power/domain.c:587
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81717000-ffffffff81717147: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d2d90)
Location: drivers/base/power/domain.c:587
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff817d2d90-ffffffff817d2f4a: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e78c0)
Location: drivers/base/power/domain.c:633
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff817e78c0-ffffffff817e7a76: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817cb9b0)
Location: drivers/base/power/domain.c:665
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff817cb9b0-ffffffff817cbb6f: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81855fb0)
Location: drivers/base/power/domain.c:699
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81855fb0-ffffffff81856191: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199c870)
Location: drivers/base/power/domain.c:713
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff8199c870-ffffffff8199c9f8: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0dac0)
Location: drivers/base/power/domain.c:735
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81b0dac0-ffffffff81b0dc48: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5bb70)
Location: drivers/base/power/domain.c:761
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81b5bb70-ffffffff81b5bcf8: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa3670)
Location: drivers/pmdomain/core.c:768
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:genpd_runtime_resume
  - drivers/pmdomain/core.c:genpd_power_on
```
**Symbols:**

```
ffffffff81aa3670-ffffffff81aa37f8: genpd_power_on (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffff80001090a45c)
Location: drivers/base/power/domain.c:587
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_runtime_resume
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_runtime_resume
```
**Symbols:**

```
ffff8000109092b8-ffff8000109094b8: genpd_power_on.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (c09f3634)
Location: drivers/base/power/domain.c:587
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_runtime_resume
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_runtime_resume
```
**Symbols:**

```
c09f3320-c09f3530: genpd_power_on.part.0 (STB_LOCAL)
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
In drivers/base/power/domain.c (c0000000009aa848)
Location: drivers/base/power/domain.c:587
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_runtime_resume
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_runtime_resume
```
**Symbols:**

```
c0000000009a8ca0-c0000000009a8f68: genpd_power_on.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00059033a)
Location: drivers/base/power/domain.c:587
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_runtime_resume
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:genpd_runtime_resume
```
**Symbols:**

```
ffffffe00058f86c-ffffffe00058fa00: genpd_power_on.part.0 (STB_LOCAL)
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
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dd330)
Location: drivers/base/power/domain.c:587
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816dd330-ffffffff816dd477: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b7ab0)
Location: drivers/base/power/domain.c:587
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff816b7ab0-ffffffff816b7bf7: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170acc0)
Location: drivers/base/power/domain.c:587
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff8170acc0-ffffffff8170ae07: genpd_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int genpd_power_on(struct generic_pm_domain *genpd, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81725c40)
Location: drivers/base/power/domain.c:587
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_power_on
```
**Symbols:**

```
ffffffff81725c40-ffffffff81725d87: genpd_power_on (STB_LOCAL)
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
