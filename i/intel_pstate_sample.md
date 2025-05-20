# Function: <code>intel_pstate_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff816ba911)
Location: drivers/cpufreq/intel_pstate.c:876
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
  - drivers/cpufreq/intel_pstate.c:intel_hwp_timer_func
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c180)
Location: drivers/cpufreq/intel_pstate.c:1172
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8174f54f)
Location: drivers/cpufreq/intel_pstate.c:1632
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8176da0d)
Location: drivers/cpufreq/intel_pstate.c:1572
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_pid
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
In drivers/cpufreq/intel_pstate.c (ffffffff817e2a39)
Location: drivers/cpufreq/intel_pstate.c:1387
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8182bc32)
Location: drivers/cpufreq/intel_pstate.c:1566
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff81857c22)
Location: drivers/cpufreq/intel_pstate.c:1629
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8189b007)
Location: drivers/cpufreq/intel_pstate.c:1658
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818cd1b7)
Location: drivers/cpufreq/intel_pstate.c:1704
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool intel_pstate_sample(struct cpudata *cpu, u64 time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0860)
Location: drivers/cpufreq/intel_pstate.c:1712
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff819a0860-ffffffff819a095a: intel_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool intel_pstate_sample(struct cpudata *cpu, u64 time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a3710)
Location: drivers/cpufreq/intel_pstate.c:1860
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff819a3710-ffffffff819a380a: intel_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool intel_pstate_sample(struct cpudata *cpu, u64 time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81988340)
Location: drivers/cpufreq/intel_pstate.c:1857
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81988340-ffffffff8198844f: intel_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool intel_pstate_sample(struct cpudata *cpu, u64 time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a323d0)
Location: drivers/cpufreq/intel_pstate.c:2015
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81a323d0-ffffffff81a324df: intel_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool intel_pstate_sample(struct cpudata *cpu, u64 time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9e7c0)
Location: drivers/cpufreq/intel_pstate.c:2184
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81b9e7c0-ffffffff81b9e8f4: intel_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool intel_pstate_sample(struct cpudata *cpu, u64 time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3fd50)
Location: drivers/cpufreq/intel_pstate.c:2146
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81d3fd50-ffffffff81d3fe87: intel_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool intel_pstate_sample(struct cpudata *cpu, u64 time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81daa8c0)
Location: drivers/cpufreq/intel_pstate.c:2176
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81daa8c0-ffffffff81daa9f7: intel_pstate_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool intel_pstate_sample(struct cpudata *cpu, u64 time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e62a00)
Location: drivers/cpufreq/intel_pstate.c:2200
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81e62a00-ffffffff81e62b37: intel_pstate_sample (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81870db7)
Location: drivers/cpufreq/intel_pstate.c:1704
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8183bdf7)
Location: drivers/cpufreq/intel_pstate.c:1704
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818c2667)
Location: drivers/cpufreq/intel_pstate.c:1704
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818de977)
Location: drivers/cpufreq/intel_pstate.c:1704
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
