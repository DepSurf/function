# Function: <code>intel_pstate_update_pstate</code>

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
In drivers/cpufreq/intel_pstate.c (ffffffff8171c263)
Location: drivers/cpufreq/intel_pstate.c:1293
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174ec90)
Location: drivers/cpufreq/intel_pstate.c:1766
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff8174ec90-ffffffff8174eccd: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176b9f0)
Location: drivers/cpufreq/intel_pstate.c:1711
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
```
**Symbols:**

```
ffffffff8176b9f0-ffffffff8176ba20: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e29a0)
Location: drivers/cpufreq/intel_pstate.c:1488
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff817e29a0-ffffffff817e29d6: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182bba0)
Location: drivers/cpufreq/intel_pstate.c:1667
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff8182bba0-ffffffff8182bbd5: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81857b90)
Location: drivers/cpufreq/intel_pstate.c:1730
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81857b90-ffffffff81857bc5: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189af40)
Location: drivers/cpufreq/intel_pstate.c:1754
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff8189af40-ffffffff8189af75: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cd0f0)
Location: drivers/cpufreq/intel_pstate.c:1800
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff818cd0f0-ffffffff818cd125: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0bba)
Location: drivers/cpufreq/intel_pstate.c:1808
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a3282)
Location: drivers/cpufreq/intel_pstate.c:1956
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81987cfd)
Location: drivers/cpufreq/intel_pstate.c:1953
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81a31abb)
Location: drivers/cpufreq/intel_pstate.c:2111
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81b9dd7a)
Location: drivers/cpufreq/intel_pstate.c:2280
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81d3fbd2)
Location: drivers/cpufreq/intel_pstate.c:2242
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81daa742)
Location: drivers/cpufreq/intel_pstate.c:2272
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
In drivers/cpufreq/intel_pstate.c (ffffffff81e62886)
Location: drivers/cpufreq/intel_pstate.c:2296
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
<summary>In <code>aws</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81870cf0)
Location: drivers/cpufreq/intel_pstate.c:1800
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81870cf0-ffffffff81870d25: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8183a640)
Location: drivers/cpufreq/intel_pstate.c:1800
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff8183a640-ffffffff8183a684: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c25a0)
Location: drivers/cpufreq/intel_pstate.c:1800
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff818c25a0-ffffffff818c25d5: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pstate_update_pstate(struct cpudata *cpu, int pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818de8b0)
Location: drivers/cpufreq/intel_pstate.c:1800
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff818de8b0-ffffffff818de8e5: intel_pstate_update_pstate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
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
