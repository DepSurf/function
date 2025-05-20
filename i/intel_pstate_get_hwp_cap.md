# Function: <code>intel_pstate_get_hwp_cap</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819879f1)
Location: drivers/cpufreq/intel_pstate.c:832
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pstate_get_hwp_cap(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a2ffa0)
Location: drivers/cpufreq/intel_pstate.c:908
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81a2ffa0-ffffffff81a30036: intel_pstate_get_hwp_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pstate_get_hwp_cap(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9bbb0)
Location: drivers/cpufreq/intel_pstate.c:931
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81b9bbb0-ffffffff81b9bc5c: intel_pstate_get_hwp_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pstate_get_hwp_cap(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3d530)
Location: drivers/cpufreq/intel_pstate.c:906
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81d3d530-ffffffff81d3d5dc: intel_pstate_get_hwp_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pstate_get_hwp_cap(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da80d0)
Location: drivers/cpufreq/intel_pstate.c:926
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81da80d0-ffffffff81da817c: intel_pstate_get_hwp_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pstate_get_hwp_cap(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5feb0)
Location: drivers/cpufreq/intel_pstate.c:950
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81e5feb0-ffffffff81e5ff5c: intel_pstate_get_hwp_cap (STB_LOCAL)
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
