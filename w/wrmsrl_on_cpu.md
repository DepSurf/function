# Function: <code>wrmsrl_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b570)
Location: arch/x86/lib/msr-smp.c:81
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:core_set_pstate
  - drivers/cpufreq/intel_pstate.c:atom_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
```
**Symbols:**

```
ffffffff8141b570-ffffffff8141b5d6: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81463730)
Location: arch/x86/lib/msr-smp.c:81
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_min_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
```
**Symbols:**

```
ffffffff81463730-ffffffff81463796: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814829d0)
Location: arch/x86/lib/msr-smp.c:81
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff814829d0-ffffffff81482a36: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c1c0)
Location: arch/x86/lib/msr-smp.c:81
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8148c1c0-ffffffff8148c22d: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c82b0)
Location: arch/x86/lib/msr-smp.c:82
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff814c82b0-ffffffff814c831d: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f91c0)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff814f91c0-ffffffff814f922d: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150da60)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8150da60-ffffffff8150dacd: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153c110)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff8153c110-ffffffff8153c176: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155cf20)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff8155cf20-ffffffff8155cf86: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e6940)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff815e6940-ffffffff815e69a6: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160ba90)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff8160ba90-ffffffff8160baf6: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815eed70)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff815eed70-ffffffff815eedd6: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165be80)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff8165be80-ffffffff8165bee6: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81774cc0)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff81774cc0-ffffffff81774d39: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a57c0)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff818a57c0-ffffffff818a5839: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818e85e0)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_offline
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_reenable
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_set_epp
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff818e85e0-ffffffff818e8659: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8192fa80)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_offline
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_reenable
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_set_epp
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_resume
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff8192fa80-ffffffff8192faf9: wrmsrl_on_cpu (STB_GLOBAL)
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
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81555510)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff81555510-ffffffff81555576: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81545740)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff81545740-ffffffff815457a6: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81551250)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff81551250-ffffffff815512b6: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wrmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156b090)
Location: arch/x86/lib/msr-smp.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
```
**Symbols:**

```
ffffffff8156b090-ffffffff8156b0f6: wrmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
