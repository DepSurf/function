# Function: <code>freq_qos_add_request</code>

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
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106db0)
Location: kernel/power/qos.c:753
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81106db0-ffffffff81106e2e: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81111d60)
Location: kernel/power/qos.c:528
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81111d60-ffffffff81111de4: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110ee30)
Location: kernel/power/qos.c:528
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8110ee30-ffffffff8110eeb4: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f8d0)
Location: kernel/power/qos.c:528
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
```
**Symbols:**

```
ffffffff8110f8d0-ffffffff8110f954: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112f220)
Location: kernel/power/qos.c:528
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
```
**Symbols:**

```
ffffffff8112f220-ffffffff8112f2a4: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81150830)
Location: kernel/power/qos.c:528
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81150830-ffffffff811508dd: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117f1f0)
Location: kernel/power/qos.c:528
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8117f1f0-ffffffff8117f2a4: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118fe40)
Location: kernel/power/qos.c:533
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8118fe40-ffffffff8118fef9: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119e800)
Location: kernel/power/qos.c:538
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff8119e800-ffffffff8119e8b9: freq_qos_add_request (STB_GLOBAL)
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
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016daf0)
Location: kernel/power/qos.c:753
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffff80001016daf0-ffff80001016dba0: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b8a08)
Location: kernel/power/qos.c:753
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c03b8a08-c03b8ac8: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c5260)
Location: kernel/power/qos.c:753
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c0000000001c5260-c0000000001c5350: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010d162)
Location: kernel/power/qos.c:753
Inline: False
```
**Symbols:**

```
ffffffe00010d162-ffffffe00010d1f6: freq_qos_add_request (STB_GLOBAL)
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
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811000c0)
Location: kernel/power/qos.c:753
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff811000c0-ffffffff8110013e: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f02b0)
Location: kernel/power/qos.c:753
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff810f02b0-ffffffff810f032e: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fd280)
Location: kernel/power/qos.c:753
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff810fd280-ffffffff810fd2fe: freq_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints *qos, struct freq_qos_request *req, enum freq_qos_req_type type, s32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811084f0)
Location: kernel/power/qos.c:753
Inline: False
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff811084f0-ffffffff8110856e: freq_qos_add_request (STB_GLOBAL)
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
