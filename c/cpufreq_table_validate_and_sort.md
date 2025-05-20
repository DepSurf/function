# Function: <code>cpufreq_table_validate_and_sort</code>

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
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:355
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81823ae3-ffffffff81823af9: cpufreq_table_validate_and_sort.cold.3 (STB_LOCAL)
ffffffff818239a0-ffffffff81823ae3: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:355
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8184f9a3-ffffffff8184f9b9: cpufreq_table_validate_and_sort.cold.3 (STB_LOCAL)
ffffffff8184f860-ffffffff8184f9a3: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81892e99-ffffffff81892eb2: cpufreq_table_validate_and_sort.cold (STB_LOCAL)
ffffffff81892d50-ffffffff81892e99: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818c4eb9-ffffffff818c4ed2: cpufreq_table_validate_and_sort.cold (STB_LOCAL)
ffffffff818c4d70-ffffffff818c4eb9: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81997050)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81997050-ffffffff8199708a: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff8199a160)
Location: drivers/cpufreq/freq_table.c:354
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8199a160-ffffffff8199a19a: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:354
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81c1bd28-ffffffff81c1bd3e: cpufreq_table_validate_and_sort.cold (STB_LOCAL)
ffffffff8197ed30-ffffffff8197ee75: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:354
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81d2c1a3-ffffffff81d2c1b9: cpufreq_table_validate_and_sort.cold (STB_LOCAL)
ffffffff81a27e90-ffffffff81a27fcc: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:354
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81ef8445-ffffffff81ef845b: cpufreq_table_validate_and_sort.cold (STB_LOCAL)
ffffffff81b91d40-ffffffff81b91e86: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81d32140)
Location: drivers/cpufreq/freq_table.c:354
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81d32140-ffffffff81d322a6: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81d9b520)
Location: drivers/cpufreq/freq_table.c:354
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81d9b520-ffffffff81d9b680: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81e53230)
Location: drivers/cpufreq/freq_table.c:354
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81e53230-ffffffff81e53390: cpufreq_table_validate_and_sort (STB_GLOBAL)
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
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffff800010b229a0)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffff800010b229a0-ffff800010b22b28: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (c0bfcd84)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c0bfcd84-c0bfcf1c: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (c000000000c16bb0)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c000000000c16bb0-c000000000c16dcc: cpufreq_table_validate_and_sort (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818695d9-ffffffff818695f2: cpufreq_table_validate_and_sort.cold (STB_LOCAL)
ffffffff81869490-ffffffff818695d9: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81832289-ffffffff818322a2: cpufreq_table_validate_and_sort.cold (STB_LOCAL)
ffffffff81832140-ffffffff81832289: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818ba369-ffffffff818ba382: cpufreq_table_validate_and_sort.cold (STB_LOCAL)
ffffffff818ba220-ffffffff818ba369: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cpufreq_table_validate_and_sort(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:348
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818d6649-ffffffff818d6662: cpufreq_table_validate_and_sort.cold (STB_LOCAL)
ffffffff818d6500-ffffffff818d6649: cpufreq_table_validate_and_sort (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
