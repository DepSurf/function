# Function: <code>freq_qos_remove_request</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106e90)
Location: kernel/power/qos.c:815
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81106e90-ffffffff81106ef5: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811119d0)
Location: kernel/power/qos.c:590
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff811119d0-ffffffff81111a6d: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110eab0)
Location: kernel/power/qos.c:590
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8110eab0-ffffffff8110eb4d: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f550)
Location: kernel/power/qos.c:590
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/powercap/dtpm_cpu.c:pd_release
```
**Symbols:**

```
ffffffff8110f550-ffffffff8110f5ed: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112eea0)
Location: kernel/power/qos.c:590
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/powercap/dtpm_cpu.c:pd_release
```
**Symbols:**

```
ffffffff8112eea0-ffffffff8112ef3d: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81150400)
Location: kernel/power/qos.c:590
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81150400-ffffffff811504c5: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117ed60)
Location: kernel/power/qos.c:590
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8117ed60-ffffffff8117ee25: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118f9b0)
Location: kernel/power/qos.c:595
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8118f9b0-ffffffff8118fa75: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119e370)
Location: kernel/power/qos.c:600
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8119e370-ffffffff8119e435: freq_qos_remove_request (STB_GLOBAL)
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
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016dc28)
Location: kernel/power/qos.c:815
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffff80001016dc28-ffff80001016dca4: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b8b60)
Location: kernel/power/qos.c:815
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
c03b8b60-c03b8bec: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c5400)
Location: kernel/power/qos.c:815
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
c0000000001c5400-c0000000001c54a4: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010d260)
Location: kernel/power/qos.c:815
Inline: False
```
**Symbols:**

```
ffffffe00010d260-ffffffe00010d2c4: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811001a0)
Location: kernel/power/qos.c:815
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff811001a0-ffffffff81100205: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f0390)
Location: kernel/power/qos.c:815
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff810f0390-ffffffff810f03f5: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fd360)
Location: kernel/power/qos.c:815
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff810fd360-ffffffff810fd3c5: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811085d0)
Location: kernel/power/qos.c:815
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff811085d0-ffffffff81108635: freq_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
