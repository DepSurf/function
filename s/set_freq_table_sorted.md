# Function: <code>set_freq_table_sorted</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff817149c0)
Location: drivers/cpufreq/freq_table.c:300
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81746750)
Location: drivers/cpufreq/freq_table.c:300
Inline: True
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
In drivers/cpufreq/freq_table.c (ffffffff81764d60)
Location: drivers/cpufreq/freq_table.c:300
Inline: True
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
In drivers/cpufreq/freq_table.c (ffffffff817dad40)
Location: drivers/cpufreq/freq_table.c:300
Inline: True
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
In drivers/cpufreq/freq_table.c (ffffffff818239da)
Location: drivers/cpufreq/freq_table.c:300
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff8184f89a)
Location: drivers/cpufreq/freq_table.c:300
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff81892d8a)
Location: drivers/cpufreq/freq_table.c:293
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff818c4daa)
Location: drivers/cpufreq/freq_table.c:293
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int set_freq_table_sorted(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:293
Inline: False
Direct callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
```
**Symbols:**

```
ffffffff81996b70-ffffffff81996c70: set_freq_table_sorted (STB_LOCAL)
ffffffff8199708a-ffffffff819970a0: set_freq_table_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int set_freq_table_sorted(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/freq_table.c (0)
Location: drivers/cpufreq/freq_table.c:299
Inline: False
Direct callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
```
**Symbols:**

```
ffffffff81999cb0-ffffffff81999db0: set_freq_table_sorted (STB_LOCAL)
ffffffff81c29955-ffffffff81c2996b: set_freq_table_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff8197ed62)
Location: drivers/cpufreq/freq_table.c:299
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff81a27ec2)
Location: drivers/cpufreq/freq_table.c:299
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff81b91d78)
Location: drivers/cpufreq/freq_table.c:299
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff81d32178)
Location: drivers/cpufreq/freq_table.c:299
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff81d9b558)
Location: drivers/cpufreq/freq_table.c:299
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff81e53268)
Location: drivers/cpufreq/freq_table.c:299
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffff800010b229e8)
Location: drivers/cpufreq/freq_table.c:293
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (c0bfcdf0)
Location: drivers/cpufreq/freq_table.c:293
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (c000000000c16c10)
Location: drivers/cpufreq/freq_table.c:293
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff818694ca)
Location: drivers/cpufreq/freq_table.c:293
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff8183217a)
Location: drivers/cpufreq/freq_table.c:293
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff818ba25a)
Location: drivers/cpufreq/freq_table.c:293
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
In drivers/cpufreq/freq_table.c (ffffffff818d653a)
Location: drivers/cpufreq/freq_table.c:293
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_table_validate_and_sort
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
</ul>
