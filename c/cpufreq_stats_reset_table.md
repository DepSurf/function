# Function: <code>cpufreq_stats_reset_table</code>

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
void cpufreq_stats_reset_table(struct cpufreq_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_stats.c (ffffffff8199a530)
Location: drivers/cpufreq/cpufreq_stats.c:39
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
```
**Symbols:**

```
ffffffff8199a530-ffffffff8199a5bb: cpufreq_stats_reset_table (STB_LOCAL)
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
In drivers/cpufreq/cpufreq_stats.c (ffffffff8197f502)
Location: drivers/cpufreq/cpufreq_stats.c:39
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
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
In drivers/cpufreq/cpufreq_stats.c (ffffffff81a28652)
Location: drivers/cpufreq/cpufreq_stats.c:39
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
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
In drivers/cpufreq/cpufreq_stats.c (ffffffff81b92570)
Location: drivers/cpufreq/cpufreq_stats.c:39
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpufreq_stats_reset_table(struct cpufreq_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81d32410)
Location: drivers/cpufreq/cpufreq_stats.c:39
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
```
**Symbols:**

```
ffffffff81d32410-ffffffff81d324a6: cpufreq_stats_reset_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpufreq_stats_reset_table(struct cpufreq_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81d9b7d0)
Location: drivers/cpufreq/cpufreq_stats.c:39
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
```
**Symbols:**

```
ffffffff81d9b7d0-ffffffff81d9b858: cpufreq_stats_reset_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpufreq_stats_reset_table(struct cpufreq_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81e534e0)
Location: drivers/cpufreq/cpufreq_stats.c:39
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
```
**Symbols:**

```
ffffffff81e534e0-ffffffff81e53568: cpufreq_stats_reset_table (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
