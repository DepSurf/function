# Function: <code>intel_pstate_get_epp</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174de90)
Location: drivers/cpufreq/intel_pstate.c:658
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff8174de90-ffffffff8174df1f: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c7b0)
Location: drivers/cpufreq/intel_pstate.c:598
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff8176c7b0-ffffffff8176c83f: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e24a0)
Location: drivers/cpufreq/intel_pstate.c:489
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff817e24a0-ffffffff817e252f: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b2d0)
Location: drivers/cpufreq/intel_pstate.c:513
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff8182b2d0-ffffffff8182b35f: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81857260)
Location: drivers/cpufreq/intel_pstate.c:536
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81857260-ffffffff818572ef: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189ab60)
Location: drivers/cpufreq/intel_pstate.c:536
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff8189ab60-ffffffff8189abfe: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818ccd10)
Location: drivers/cpufreq/intel_pstate.c:537
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff818ccd10-ffffffff818ccdae: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199e030)
Location: drivers/cpufreq/intel_pstate.c:537
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff8199e030-ffffffff8199e0cc: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0a00)
Location: drivers/cpufreq/intel_pstate.c:528
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff819a0a00-ffffffff819a0a9c: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81985670)
Location: drivers/cpufreq/intel_pstate.c:528
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81985670-ffffffff8198570c: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a2f2a0)
Location: drivers/cpufreq/intel_pstate.c:601
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81a2f2a0-ffffffff81a2f33c: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9ad70)
Location: drivers/cpufreq/intel_pstate.c:614
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81b9ad70-ffffffff81b9ae1e: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3c0b0)
Location: drivers/cpufreq/intel_pstate.c:589
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81d3c0b0-ffffffff81d3c15e: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da6c10)
Location: drivers/cpufreq/intel_pstate.c:607
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81da6c10-ffffffff81da6cbe: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5ed10)
Location: drivers/cpufreq/intel_pstate.c:631
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81e5ed10-ffffffff81e5edbe: intel_pstate_get_epp (STB_LOCAL)
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
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81870910)
Location: drivers/cpufreq/intel_pstate.c:537
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81870910-ffffffff818709ae: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81839e90)
Location: drivers/cpufreq/intel_pstate.c:537
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81839e90-ffffffff81839f2e: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c21c0)
Location: drivers/cpufreq/intel_pstate.c:537
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff818c21c0-ffffffff818c225e: intel_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s16 intel_pstate_get_epp(struct cpudata *cpu_data, u64 hwp_req_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818de4d0)
Location: drivers/cpufreq/intel_pstate.c:537
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_save_state
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff818de4d0-ffffffff818de56e: intel_pstate_get_epp (STB_LOCAL)
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
