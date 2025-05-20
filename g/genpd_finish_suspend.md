# Function: <code>genpd_finish_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f38e0)
Location: drivers/base/power/domain.c:913
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_poweroff_noirq
  - drivers/base/power/domain.c:pm_genpd_poweroff_noirq
  - drivers/base/power/domain.c:pm_genpd_suspend_noirq
  - drivers/base/power/domain.c:pm_genpd_suspend_noirq
```
**Symbols:**

```
ffffffff815f38e0-ffffffff815f39b4: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165b6e0)
Location: drivers/base/power/domain.c:1032
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff8165b6e0-ffffffff8165b7d1: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81697390)
Location: drivers/base/power/domain.c:1033
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff81697390-ffffffff816974aa: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b8070)
Location: drivers/base/power/domain.c:1112
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff816b8070-ffffffff816b818a: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f1db0)
Location: drivers/base/power/domain.c:1115
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff816f1db0-ffffffff816f1ed4: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81716530)
Location: drivers/base/power/domain.c:1110
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff81716530-ffffffff81716654: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d1850)
Location: drivers/base/power/domain.c:1099
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff817d1850-ffffffff817d1974: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e6010)
Location: drivers/base/power/domain.c:1144
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff817e6010-ffffffff817e6134: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817ca420)
Location: drivers/base/power/domain.c:1139
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff817ca420-ffffffff817ca540: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81855b80)
Location: drivers/base/power/domain.c:1179
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff81855b80-ffffffff81855ca0: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199ab50)
Location: drivers/base/power/domain.c:1197
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff8199ab50-ffffffff8199ac82: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, int (*suspend_noirq)(struct device *), int (*resume_noirq)(struct device *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0e170)
Location: drivers/base/power/domain.c:1219
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff81b0e170-ffffffff81b0e287: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, int (*suspend_noirq)(struct device *), int (*resume_noirq)(struct device *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5c220)
Location: drivers/base/power/domain.c:1245
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff81b5c220-ffffffff81b5c337: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, int (*suspend_noirq)(struct device *), int (*resume_noirq)(struct device *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa3d20)
Location: drivers/pmdomain/core.c:1252
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:genpd_poweroff_noirq
  - drivers/pmdomain/core.c:genpd_freeze_noirq
  - drivers/pmdomain/core.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff81aa3d20-ffffffff81aa3e37: genpd_finish_suspend (STB_LOCAL)
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
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010909088)
Location: drivers/base/power/domain.c:1110
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffff800010909088-ffff8000109091c8: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f2b64)
Location: drivers/base/power/domain.c:1110
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
c09f2b64-c09f2c84: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a7fb0)
Location: drivers/base/power/domain.c:1110
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
c0000000009a7fb0-c0000000009a81b8: genpd_finish_suspend (STB_LOCAL)
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
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dc860)
Location: drivers/base/power/domain.c:1110
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff816dc860-ffffffff816dc984: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b6ee0)
Location: drivers/base/power/domain.c:1110
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff816b6ee0-ffffffff816b7004: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170a1f0)
Location: drivers/base/power/domain.c:1110
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff8170a1f0-ffffffff8170a314: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int genpd_finish_suspend(struct device *dev, bool poweroff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81724ef0)
Location: drivers/base/power/domain.c:1110
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_poweroff_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
  - drivers/base/power/domain.c:genpd_suspend_noirq
```
**Symbols:**

```
ffffffff81724ef0-ffffffff81725014: genpd_finish_suspend (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int (*suspend_noirq)(struct device *)</code>
</li>
<li>
<b>Param added. </b>
<code>int (*resume_noirq)(struct device *)</code>
</li>
<li>
<b>Param removed. </b>
<code>bool poweroff</code>
</li>
</ul>
</details>
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
