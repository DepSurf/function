# Function: <code>genpd_switch_state</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void genpd_switch_state(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e72a0)
Location: drivers/base/power/domain.c:1381
Inline: False
Direct callers:
  - drivers/base/power/domain.c:dev_pm_genpd_resume
  - drivers/base/power/domain.c:dev_pm_genpd_suspend
```
**Symbols:**

```
ffffffff817e72a0-ffffffff817e7383: genpd_switch_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void genpd_switch_state(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817cb1b0)
Location: drivers/base/power/domain.c:1376
Inline: False
Direct callers:
  - drivers/base/power/domain.c:dev_pm_genpd_resume
  - drivers/base/power/domain.c:dev_pm_genpd_suspend
```
**Symbols:**

```
ffffffff817cb1b0-ffffffff817cb293: genpd_switch_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void genpd_switch_state(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81855a50)
Location: drivers/base/power/domain.c:1416
Inline: False
Direct callers:
  - drivers/base/power/domain.c:dev_pm_genpd_resume
  - drivers/base/power/domain.c:dev_pm_genpd_suspend
```
**Symbols:**

```
ffffffff81855a50-ffffffff81855b33: genpd_switch_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void genpd_switch_state(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199bf50)
Location: drivers/base/power/domain.c:1434
Inline: False
Direct callers:
  - drivers/base/power/domain.c:dev_pm_genpd_resume
  - drivers/base/power/domain.c:dev_pm_genpd_suspend
```
**Symbols:**

```
ffffffff8199bf50-ffffffff8199c056: genpd_switch_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void genpd_switch_state(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0e3f0)
Location: drivers/base/power/domain.c:1413
Inline: False
Direct callers:
  - drivers/base/power/domain.c:dev_pm_genpd_resume
  - drivers/base/power/domain.c:dev_pm_genpd_suspend
```
**Symbols:**

```
ffffffff81b0e3f0-ffffffff81b0e4f6: genpd_switch_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void genpd_switch_state(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5c4a0)
Location: drivers/base/power/domain.c:1439
Inline: False
Direct callers:
  - drivers/base/power/domain.c:dev_pm_genpd_resume
  - drivers/base/power/domain.c:dev_pm_genpd_suspend
```
**Symbols:**

```
ffffffff81b5c4a0-ffffffff81b5c5aa: genpd_switch_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void genpd_switch_state(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa3fa0)
Location: drivers/pmdomain/core.c:1446
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:dev_pm_genpd_resume
  - drivers/pmdomain/core.c:dev_pm_genpd_suspend
```
**Symbols:**

```
ffffffff81aa3fa0-ffffffff81aa40aa: genpd_switch_state (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
