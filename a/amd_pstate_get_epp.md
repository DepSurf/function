# Function: <code>amd_pstate_get_epp</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s16 amd_pstate_get_epp(struct amd_cpudata *cpudata, u64 cppc_req_cached);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81da12c0)
Location: drivers/cpufreq/amd-pstate.c:125
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81da12c0-ffffffff81da137f: amd_pstate_get_epp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s16 amd_pstate_get_epp(struct amd_cpudata *cpudata, u64 cppc_req_cached);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate.c (ffffffff81e59080)
Location: drivers/cpufreq/amd-pstate.c:125
Inline: False
Direct callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:show_energy_performance_preference
```
**Symbols:**

```
ffffffff81e59080-ffffffff81e5913f: amd_pstate_get_epp (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
