# Function: <code>genpd_summary_one</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165b3c3)
Location: drivers/base/power/domain.c:2397
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_summary_show
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
In drivers/base/power/domain.c (ffffffff81697083)
Location: drivers/base/power/domain.c:2581
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_summary_show
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
In drivers/base/power/domain.c (ffffffff816b7a13)
Location: drivers/base/power/domain.c:2695
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
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
In drivers/base/power/domain.c (ffffffff816f1673)
Location: drivers/base/power/domain.c:2768
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
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
In drivers/base/power/domain.c (ffffffff81715dc3)
Location: drivers/base/power/domain.c:2763
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genpd_summary_one(struct seq_file *s, struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d0f90)
Location: drivers/base/power/domain.c:2801
Inline: False
Direct callers:
  - drivers/base/power/domain.c:summary_show
```
**Symbols:**

```
ffffffff817d0f90-ffffffff817d11aa: genpd_summary_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genpd_summary_one(struct seq_file *s, struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e54a0)
Location: drivers/base/power/domain.c:2958
Inline: False
Direct callers:
  - drivers/base/power/domain.c:summary_show
```
**Symbols:**

```
ffffffff817e54a0-ffffffff817e56ba: genpd_summary_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genpd_summary_one(struct seq_file *s, struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817c9b90)
Location: drivers/base/power/domain.c:2964
Inline: False
Direct callers:
  - drivers/base/power/domain.c:summary_show
```
**Symbols:**

```
ffffffff817c9b90-ffffffff817c9e00: genpd_summary_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genpd_summary_one(struct seq_file *s, struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff818540b0)
Location: drivers/base/power/domain.c:3026
Inline: False
Direct callers:
  - drivers/base/power/domain.c:summary_show
```
**Symbols:**

```
ffffffff818540b0-ffffffff81854344: genpd_summary_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genpd_summary_one(struct seq_file *s, struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199a660)
Location: drivers/base/power/domain.c:3091
Inline: False
Direct callers:
  - drivers/base/power/domain.c:summary_show
```
**Symbols:**

```
ffffffff8199a660-ffffffff8199a91f: genpd_summary_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genpd_summary_one(struct seq_file *s, struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0b920)
Location: drivers/base/power/domain.c:3084
Inline: False
Direct callers:
  - drivers/base/power/domain.c:summary_show
```
**Symbols:**

```
ffffffff81b0b920-ffffffff81b0bbdf: genpd_summary_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genpd_summary_one(struct seq_file *s, struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b59960)
Location: drivers/base/power/domain.c:3113
Inline: False
Direct callers:
  - drivers/base/power/domain.c:summary_show
```
**Symbols:**

```
ffffffff81b59960-ffffffff81b59c1f: genpd_summary_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genpd_summary_one(struct seq_file *s, struct generic_pm_domain *genpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa1320)
Location: drivers/pmdomain/core.c:3089
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:summary_show
```
**Symbols:**

```
ffffffff81aa1320-ffffffff81aa15df: genpd_summary_one (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010906f38)
Location: drivers/base/power/domain.c:2763
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f0c54)
Location: drivers/base/power/domain.c:2763
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a6500)
Location: drivers/base/power/domain.c:2763
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058e53c)
Location: drivers/base/power/domain.c:2763
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
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
In drivers/base/power/domain.c (ffffffff816dc0f3)
Location: drivers/base/power/domain.c:2763
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
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
In drivers/base/power/domain.c (ffffffff816b6773)
Location: drivers/base/power/domain.c:2763
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
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
In drivers/base/power/domain.c (ffffffff81709a83)
Location: drivers/base/power/domain.c:2763
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
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
In drivers/base/power/domain.c (ffffffff817245f3)
Location: drivers/base/power/domain.c:2763
Inline: True
Inline callers:
  - drivers/base/power/domain.c:summary_show
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
