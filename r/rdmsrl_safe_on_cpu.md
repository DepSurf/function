# Function: <code>rdmsrl_safe_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b750)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
```
**Symbols:**

```
ffffffff8141b750-ffffffff8141b7d0: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81463910)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
```
**Symbols:**

```
ffffffff81463910-ffffffff81463990: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81482bb0)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff81482bb0-ffffffff81482c30: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c3c0)
Location: arch/x86/lib/msr-smp.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff8148c3c0-ffffffff8148c440: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c84b0)
Location: arch/x86/lib/msr-smp.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff814c84b0-ffffffff814c8530: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f9550)
Location: arch/x86/lib/msr-smp.c:226
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff814f9550-ffffffff814f95a8: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150ddf0)
Location: arch/x86/lib/msr-smp.c:226
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff8150ddf0-ffffffff8150de48: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153c460)
Location: arch/x86/lib/msr-smp.c:226
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff8153c460-ffffffff8153c4b8: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155d270)
Location: arch/x86/lib/msr-smp.c:226
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff8155d270-ffffffff8155d2c8: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e6c50)
Location: arch/x86/lib/msr-smp.c:226
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff815e6c50-ffffffff815e6cad: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160bda0)
Location: arch/x86/lib/msr-smp.c:225
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff8160bda0-ffffffff8160bdfd: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815ef080)
Location: arch/x86/lib/msr-smp.c:225
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff815ef080-ffffffff815ef0d7: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165c190)
Location: arch/x86/lib/msr-smp.c:225
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff8165c190-ffffffff8165c1e7: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81775150)
Location: arch/x86/lib/msr-smp.c:225
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc.c:cpc_read_ffh
  - drivers/cpufreq/amd-pstate.c:pstate_init_perf
```
**Symbols:**

```
ffffffff81775150-ffffffff817751c1: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a5cd0)
Location: arch/x86/lib/msr-smp.c:225
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc.c:cpc_read_ffh
  - drivers/cpufreq/amd-pstate.c:pstate_init_perf
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
**Symbols:**

```
ffffffff818a5cd0-ffffffff818a5d41: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818e8af0)
Location: arch/x86/lib/msr-smp.c:225
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc.c:cpc_read_ffh
  - drivers/cpufreq/amd-pstate.c:pstate_init_perf
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
**Symbols:**

```
ffffffff818e8af0-ffffffff818e8b53: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8192ff90)
Location: arch/x86/lib/msr-smp.c:225
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc.c:cpc_read_ffh
  - drivers/cpufreq/amd-pstate.c:pstate_init_perf
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
**Symbols:**

```
ffffffff8192ff90-ffffffff8192fff3: rdmsrl_safe_on_cpu (STB_GLOBAL)
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
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81555860)
Location: arch/x86/lib/msr-smp.c:226
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff81555860-ffffffff815558b8: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81545b30)
Location: arch/x86/lib/msr-smp.c:226
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff81545b30-ffffffff81545b88: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815515a0)
Location: arch/x86/lib/msr-smp.c:226
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff815515a0-ffffffff815515f8: rdmsrl_safe_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdmsrl_safe_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156b400)
Location: arch/x86/lib/msr-smp.c:226
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_write_ffh
  - arch/x86/kernel/acpi/cppc_msr.c:cpc_read_ffh
```
**Symbols:**

```
ffffffff8156b400-ffffffff8156b458: rdmsrl_safe_on_cpu (STB_GLOBAL)
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
