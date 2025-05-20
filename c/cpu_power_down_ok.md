# Function: <code>cpu_power_down_ok</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff816f3960)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
ffffffff816f3960-ffffffff816f3a63: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff81717d60)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
ffffffff81717d60-ffffffff81717e63: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff817d3940)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
ffffffff817d3940-ffffffff817d3a03: cpu_power_down_ok.part.0 (STB_LOCAL)
ffffffff817d3a10-ffffffff817d3a40: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff817e83a0)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
ffffffff817e83a0-ffffffff817e845f: cpu_power_down_ok.part.0 (STB_LOCAL)
ffffffff817e8460-ffffffff817e8490: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff817cc900)
Location: drivers/base/power/domain_governor.c:335
Inline: False
```
**Symbols:**

```
ffffffff817cc900-ffffffff817cc9f2: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff81856ee0)
Location: drivers/base/power/domain_governor.c:336
Inline: False
```
**Symbols:**

```
ffffffff81856ee0-ffffffff81857003: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff8199d310)
Location: drivers/base/power/domain_governor.c:342
Inline: False
```
**Symbols:**

```
ffffffff8199d310-ffffffff8199d443: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff81b0eb50)
Location: drivers/base/power/domain_governor.c:342
Inline: False
```
**Symbols:**

```
ffffffff81b0eb50-ffffffff81b0ec91: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff81b5cc00)
Location: drivers/base/power/domain_governor.c:342
Inline: False
```
**Symbols:**

```
ffffffff81b5cc00-ffffffff81b5cd41: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/governor.c (ffffffff81aa4700)
Location: drivers/pmdomain/governor.c:346
Inline: False
```
**Symbols:**

```
ffffffff81aa4700-ffffffff81aa4841: cpu_power_down_ok (STB_LOCAL)
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
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffff80001090ab98)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
ffff80001090ab98-ffff80001090ace8: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (c09f43ec)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
c09f43ec-c09f455c: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (c0000000009ab230)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
c0000000009ab230-c0000000009ab410: cpu_power_down_ok (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff816de090)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
ffffffff816de090-ffffffff816de193: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff816b86f0)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
ffffffff816b86f0-ffffffff816b87f3: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff8170ba20)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
ffffffff8170ba20-ffffffff8170bb23: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff81726410)
Location: drivers/base/power/domain_governor.c:252
Inline: True
```
**Symbols:**

```
ffffffff81726410-ffffffff81726513: cpu_power_down_ok (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
