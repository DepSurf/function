# Function: <code>acpi_processor_unregister_performance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff814aeb58)
Location: drivers/acpi/processor_perflib.c:783
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff814aeb58-ffffffff814aebb7: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff814fe521)
Location: drivers/acpi/processor_perflib.c:783
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
```
**Symbols:**

```
ffffffff814fe521-ffffffff814fe580: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81521215)
Location: drivers/acpi/processor_perflib.c:792
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
```
**Symbols:**

```
ffffffff81521215-ffffffff81521274: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81532ab0)
Location: drivers/acpi/processor_perflib.c:790
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
```
**Symbols:**

```
ffffffff81532ab0-ffffffff81532b0f: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81594060)
Location: drivers/acpi/processor_perflib.c:790
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
```
**Symbols:**

```
ffffffff81594060-ffffffff815940bf: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff815cb4e0)
Location: drivers/acpi/processor_perflib.c:790
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
```
**Symbols:**

```
ffffffff815cb4e0-ffffffff815cb53f: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff815e4ac0)
Location: drivers/acpi/processor_perflib.c:790
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
```
**Symbols:**

```
ffffffff815e4ac0-ffffffff815e4b1f: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff816166a0)
Location: drivers/acpi/processor_perflib.c:777
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
```
**Symbols:**

```
ffffffff816166a0-ffffffff816166ff: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81637dd0)
Location: drivers/acpi/processor_perflib.c:763
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81637dd0-ffffffff81637e2f: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff816e4cc0)
Location: drivers/acpi/processor_perflib.c:763
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_acpi_perf_limits
```
**Symbols:**

```
ffffffff816e4cc0-ffffffff816e4d22: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81702730)
Location: drivers/acpi/processor_perflib.c:761
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
```
**Symbols:**

```
ffffffff81702730-ffffffff81702792: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff816e4010)
Location: drivers/acpi/processor_perflib.c:759
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
```
**Symbols:**

```
ffffffff816e4010-ffffffff816e4072: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff8175cc90)
Location: drivers/acpi/processor_perflib.c:757
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
```
**Symbols:**

```
ffffffff8175cc90-ffffffff8175cd12: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81890840)
Location: drivers/acpi/processor_perflib.c:757
Inline: True
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
```
**Symbols:**

```
ffffffff81890840-ffffffff818908cc: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff819d7710)
Location: drivers/acpi/processor_perflib.c:750
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
```
**Symbols:**

```
ffffffff819d7710-ffffffff819d779c: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a1f110)
Location: drivers/acpi/processor_perflib.c:772
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
```
**Symbols:**

```
ffffffff81a1f110-ffffffff81a1f19c: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a6a430)
Location: drivers/acpi/processor_perflib.c:772
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
```
**Symbols:**

```
ffffffff81a6a430-ffffffff81a6a4bc: acpi_processor_unregister_performance (STB_GLOBAL)
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
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffff8000107a33f0)
Location: drivers/acpi/processor_perflib.c:763
Inline: False
```
**Symbols:**

```
ffff8000107a33f0-ffff8000107a345c: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
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
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81607000)
Location: drivers/acpi/processor_perflib.c:763
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81607000-ffffffff8160705f: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff815f20d0)
Location: drivers/acpi/processor_perflib.c:763
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff815f20d0-ffffffff815f212f: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff8162c0b0)
Location: drivers/acpi/processor_perflib.c:763
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8162c0b0-ffffffff8162c10f: acpi_processor_unregister_performance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_processor_unregister_performance(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81645f50)
Location: drivers/acpi/processor_perflib.c:763
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81645f50-ffffffff81645faf: acpi_processor_unregister_performance (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
