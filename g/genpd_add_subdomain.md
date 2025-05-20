# Function: <code>genpd_add_subdomain</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815df2fb)
Location: drivers/base/power/domain.c:1286
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f403b)
Location: drivers/base/power/domain.c:1369
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165be8b)
Location: drivers/base/power/domain.c:1492
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81697bf6)
Location: drivers/base/power/domain.c:1490
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b68b6)
Location: drivers/base/power/domain.c:1569
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f0701)
Location: drivers/base/power/domain.c:1622
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81714ba1)
Location: drivers/base/power/domain.c:1617
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d1a20)
Location: drivers/base/power/domain.c:1606
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffffffff817d1a20-ffffffff817d1c21: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e6540)
Location: drivers/base/power/domain.c:1766
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffffffff817e6540-ffffffff817e6741: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817ca940)
Location: drivers/base/power/domain.c:1762
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffffffff817ca940-ffffffff817cab41: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81854a10)
Location: drivers/base/power/domain.c:1802
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffffffff81854a10-ffffffff81854c11: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199b110)
Location: drivers/base/power/domain.c:1838
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffffffff8199b110-ffffffff8199b327: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0c2a0)
Location: drivers/base/power/domain.c:1817
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffffffff81b0c2a0-ffffffff81b0c4b7: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5a2e0)
Location: drivers/base/power/domain.c:1843
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffffffff81b5a2e0-ffffffff81b5a4f7: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa1d10)
Location: drivers/pmdomain/core.c:1850
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffffffff81aa1d10-ffffffff81aa1f58: genpd_add_subdomain (STB_LOCAL)
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
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010908558)
Location: drivers/base/power/domain.c:1617
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffff800010908558-ffff80001090873c: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09efe80)
Location: drivers/base/power/domain.c:1617
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
c09efe80-c09f0098: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a9d20)
Location: drivers/base/power/domain.c:1617
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
c0000000009a9d20-c0000000009a9fcc: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int genpd_add_subdomain(struct generic_pm_domain *genpd, struct generic_pm_domain *subdomain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058d6fe)
Location: drivers/base/power/domain.c:1617
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
**Symbols:**

```
ffffffe00058d6fe-ffffffe00058d86c: genpd_add_subdomain (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816daed1)
Location: drivers/base/power/domain.c:1617
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b5551)
Location: drivers/base/power/domain.c:1617
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81708861)
Location: drivers/base/power/domain.c:1617
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817233d1)
Location: drivers/base/power/domain.c:1617
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
