# Function: <code>genpd_remove</code>

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
In drivers/base/power/domain.c (ffffffff815de7cc)
Location: drivers/base/power/domain.c:1492
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
In drivers/base/power/domain.c (ffffffff815f334c)
Location: drivers/base/power/domain.c:1578
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
In drivers/base/power/domain.c (ffffffff8165ab2c)
Location: drivers/base/power/domain.c:1702
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
In drivers/base/power/domain.c (ffffffff81696777)
Location: drivers/base/power/domain.c:1703
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
In drivers/base/power/domain.c (ffffffff816b7107)
Location: drivers/base/power/domain.c:1784
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
In drivers/base/power/domain.c (ffffffff816f0fd1)
Location: drivers/base/power/domain.c:1851
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
In drivers/base/power/domain.c (ffffffff81715471)
Location: drivers/base/power/domain.c:1846
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d0670)
Location: drivers/base/power/domain.c:1836
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
ffffffff817d0670-ffffffff817d0897: genpd_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e5aa0)
Location: drivers/base/power/domain.c:1998
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
ffffffff817e5aa0-ffffffff817e5cf9: genpd_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817c9eb0)
Location: drivers/base/power/domain.c:1994
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
ffffffff817c9eb0-ffffffff817ca109: genpd_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:2034
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
ffffffff81854400-ffffffff81854667: genpd_remove (STB_LOCAL)
ffffffff81d03f80-ffffffff81d03f94: genpd_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:2111
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
ffffffff8199a050-ffffffff8199a2b2: genpd_remove (STB_LOCAL)
ffffffff81ecc86f-ffffffff81ecc884: genpd_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:2093
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
ffffffff81b0b2e0-ffffffff81b0b53a: genpd_remove (STB_LOCAL)
ffffffff820989ed-ffffffff82098a02: genpd_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (0)
Location: drivers/base/power/domain.c:2119
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
ffffffff81b59320-ffffffff81b5957a: genpd_remove (STB_LOCAL)
ffffffff821199a4-ffffffff821199b9: genpd_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pmdomain/core.c (0)
Location: drivers/pmdomain/core.c:2127
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:pm_genpd_remove
```
**Symbols:**

```
ffffffff81aa0ce0-ffffffff81aa0f3a: genpd_remove (STB_LOCAL)
ffffffff821f20b5-ffffffff821f20ca: genpd_remove.cold (STB_LOCAL)
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
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010906340)
Location: drivers/base/power/domain.c:1846
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
ffff800010906340-ffff800010906530: genpd_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f0474)
Location: drivers/base/power/domain.c:1846
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
c09f0474-c09f0618: genpd_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a5450)
Location: drivers/base/power/domain.c:1846
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
c0000000009a5450-c0000000009a56f4: genpd_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int genpd_remove(struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058db3a)
Location: drivers/base/power/domain.c:1846
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove
```
**Symbols:**

```
ffffffe00058db3a-ffffffe00058dcb2: genpd_remove (STB_LOCAL)
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
In drivers/base/power/domain.c (ffffffff816db7a1)
Location: drivers/base/power/domain.c:1846
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
In drivers/base/power/domain.c (ffffffff816b5e21)
Location: drivers/base/power/domain.c:1846
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
In drivers/base/power/domain.c (ffffffff81709131)
Location: drivers/base/power/domain.c:1846
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
In drivers/base/power/domain.c (ffffffff81723ca1)
Location: drivers/base/power/domain.c:1846
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
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
