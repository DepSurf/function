# Function: <code>freq_qos_update_request</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106e30)
Location: kernel/power/qos.c:789
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81106e30-ffffffff81106e86: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81111df0)
Location: kernel/power/qos.c:564
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81111df0-ffffffff81111e46: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110eec0)
Location: kernel/power/qos.c:564
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff8110eec0-ffffffff8110ef16: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f960)
Location: kernel/power/qos.c:564
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
```
**Symbols:**

```
ffffffff8110f960-ffffffff8110f9b6: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112f2b0)
Location: kernel/power/qos.c:564
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
```
**Symbols:**

```
ffffffff8112f2b0-ffffffff8112f306: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811508e0)
Location: kernel/power/qos.c:564
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_set_boost
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff811508e0-ffffffff81150954: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117f2c0)
Location: kernel/power/qos.c:564
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_set_boost
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff8117f2c0-ffffffff8117f338: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118ff10)
Location: kernel/power/qos.c:569
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_set_boost
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff8118ff10-ffffffff8118ff89: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119e8d0)
Location: kernel/power/qos.c:574
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_set_boost
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff8119e8d0-ffffffff8119e949: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016dba0)
Location: kernel/power/qos.c:789
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/thermal/cpu_cooling.c:cpufreq_set_cur_state
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
**Symbols:**

```
ffff80001016dba0-ffff80001016dc28: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b8ac8)
Location: kernel/power/qos.c:789
Inline: True
Direct callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_set_cur_state
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
**Symbols:**

```
c03b8ac8-c03b8b60: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c5350)
Location: kernel/power/qos.c:789
Inline: True
Direct callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_set_cur_state
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
```
**Symbols:**

```
c0000000001c5350-c0000000001c53f4: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010d1f6)
Location: kernel/power/qos.c:789
Inline: True
```
**Symbols:**

```
ffffffe00010d1f6-ffffffe00010d260: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81100140)
Location: kernel/power/qos.c:789
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81100140-ffffffff81100196: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f0330)
Location: kernel/power/qos.c:789
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff810f0330-ffffffff810f0386: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fd300)
Location: kernel/power/qos.c:789
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff810fd300-ffffffff810fd356: freq_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_update_request(struct freq_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81108570)
Location: kernel/power/qos.c:789
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:store_scaling_max_freq
  - drivers/cpufreq/cpufreq.c:store_scaling_min_freq
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81108570-ffffffff811085c6: freq_qos_update_request (STB_GLOBAL)
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
