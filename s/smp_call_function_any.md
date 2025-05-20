# Function: <code>smp_call_function_any</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103ad0)
Location: kernel/smp.c:361
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff81103ad0-ffffffff81103ba0: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110af00)
Location: kernel/smp.c:345
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff8110af00-ffffffff8110afbf: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81112720)
Location: kernel/smp.c:349
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff81112720-ffffffff811127dc: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81113c10)
Location: kernel/smp.c:358
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff81113c10-ffffffff81113ccc: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111f1c0)
Location: kernel/smp.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff8111f1c0-ffffffff8111f27c: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112c4f0)
Location: kernel/smp.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff8112c4f0-ffffffff8112c5aa: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81137dc0)
Location: kernel/smp.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff81137dc0-ffffffff81137e7a: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81142f40)
Location: kernel/smp.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff81142f40-ffffffff81143003: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114ea80)
Location: kernel/smp.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff8114ea80-ffffffff8114eb43: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115f560)
Location: kernel/smp.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff8115f560-ffffffff8115f623: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115b500)
Location: kernel/smp.c:582
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff8115b500-ffffffff8115b5c3: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115cbe0)
Location: kernel/smp.c:824
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff8115cbe0-ffffffff8115cca2: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81181dc0)
Location: kernel/smp.c:826
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff81181dc0-ffffffff81181ed3: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b8500)
Location: kernel/smp.c:845
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff811b8500-ffffffff811b8654: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f9860)
Location: kernel/smp.c:844
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff811f9860-ffffffff811f99be: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120ef00)
Location: kernel/smp.c:698
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff8120ef00-ffffffff8120f05c: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff812266a0)
Location: kernel/smp.c:718
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff812266a0-ffffffff812267fc: smp_call_function_any (STB_GLOBAL)
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
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bd0c0)
Location: kernel/smp.c:369
Inline: False
```
**Symbols:**

```
ffff8000101bd0c0-ffff8000101bd21c: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c040509c)
Location: kernel/smp.c:369
Inline: False
Direct callers:
  - arch/arm/kernel/perf_event_v7.c:scorpion_mp_pmu_init
  - arch/arm/kernel/perf_event_v7.c:scorpion_pmu_init
  - arch/arm/kernel/perf_event_v7.c:krait_pmu_init
  - arch/arm/kernel/perf_event_v7.c:armv7_a12_pmu_init
  - arch/arm/kernel/perf_event_v7.c:armv7_a7_pmu_init
  - arch/arm/kernel/perf_event_v7.c:armv7_a15_pmu_init
  - arch/arm/kernel/perf_event_v7.c:armv7_a5_pmu_init
  - arch/arm/kernel/perf_event_v7.c:armv7_a9_pmu_init
  - arch/arm/kernel/perf_event_v7.c:armv7_a8_pmu_init
```
**Symbols:**

```
c040509c-c04051b4: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000223080)
Location: kernel/smp.c:369
Inline: False
Direct callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_get
```
**Symbols:**

```
c000000000223080-c000000000223274: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe000140742)
Location: kernel/smp.c:369
Inline: False
```
**Symbols:**

```
ffffffe000140742-ffffffe000140848: smp_call_function_any (STB_GLOBAL)
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
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811470a0)
Location: kernel/smp.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff811470a0-ffffffff81147163: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a380)
Location: kernel/smp.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff8113a380-ffffffff8113a443: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81144f50)
Location: kernel/smp.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff81144f50-ffffffff81145013: smp_call_function_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smp_call_function_any(const struct cpumask *mask, smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81151b00)
Location: kernel/smp.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
**Symbols:**

```
ffffffff81151b00-ffffffff81151be7: smp_call_function_any (STB_GLOBAL)
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
