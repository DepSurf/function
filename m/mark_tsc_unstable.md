# Function: <code>mark_tsc_unstable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037850)
Location: arch/x86/kernel/tsc.c:1041
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/process.c:amd_e400_idle
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
**Symbols:**

```
ffffffff81037850-ffffffff810378af: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036a60)
Location: arch/x86/kernel/tsc.c:1095
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/process.c:amd_e400_idle
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff81036a60-ffffffff81036abf: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036790)
Location: arch/x86/kernel/tsc.c:1124
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff81036790-ffffffff810367ef: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81034840)
Location: arch/x86/kernel/tsc.c:1055
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff81034840-ffffffff810348ad: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036ba0)
Location: arch/x86/kernel/tsc.c:1056
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff81036ba0-ffffffff81036c0d: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:1093
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8103899e-ffffffff810389c8: mark_tsc_unstable.cold.9 (STB_LOCAL)
ffffffff81037c60-ffffffff81037c98: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81039c04)
Location: arch/x86/kernel/tsc.c:1128
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff81039c04-ffffffff81039c2e: mark_tsc_unstable.cold.10 (STB_LOCAL)
ffffffff81038f80-ffffffff81038fb8: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c1c4)
Location: arch/x86/kernel/tsc.c:1148
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8103c1c4-ffffffff8103c1ed: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff8103b510-ffffffff8103b54d: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c984)
Location: arch/x86/kernel/tsc.c:1148
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8103c984-ffffffff8103c9ad: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff8103bcc0-ffffffff8103bcfd: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f328)
Location: arch/x86/kernel/tsc.c:1163
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff8103f77a-ffffffff8103f7a7: mark_tsc_unstable.part.0 (STB_LOCAL)
ffffffff8103f7a7-ffffffff8103f7ae: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff8103eaa0-ffffffff8103eadd: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f3e8)
Location: arch/x86/kernel/tsc.c:1163
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff81bd4205-ffffffff81bd4232: mark_tsc_unstable.part.0 (STB_LOCAL)
ffffffff81bd4232-ffffffff81bd4239: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff8103eb50-ffffffff8103eb8d: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81040a07)
Location: arch/x86/kernel/tsc.c:1165
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff81bc6724-ffffffff81bc6751: mark_tsc_unstable.part.0 (STB_LOCAL)
ffffffff81bc6751-ffffffff81bc6758: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff81040410-ffffffff8104044f: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81046af7)
Location: arch/x86/kernel/tsc.c:1166
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff81c99962-ffffffff81c9998f: mark_tsc_unstable.part.0 (STB_LOCAL)
ffffffff81c9998f-ffffffff81c99996: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff81046280-ffffffff810462bf: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8104fbe2)
Location: arch/x86/kernel/tsc.c:1166
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff81e4940f-ffffffff81e49446: mark_tsc_unstable.part.0 (STB_LOCAL)
ffffffff81e49446-ffffffff81e49457: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff8104eed0-ffffffff8104ef19: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff83e79528)
Location: arch/x86/kernel/tsc.c:1166
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
Direct callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff8105cd70-ffffffff8105cde8: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8369bc8f)
Location: arch/x86/kernel/tsc.c:1201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
Direct callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff8105e270-ffffffff8105e2e8: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff838cb9af)
Location: arch/x86/kernel/tsc.c:1201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
Direct callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:tsc_sync_mark_tsc_unstable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff810651a0-ffffffff81065218: mark_tsc_unstable (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103cafc)
Location: arch/x86/kernel/tsc.c:1150
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8103cafc-ffffffff8103cb25: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff8103be20-ffffffff8103be5d: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8102c306)
Location: arch/x86/kernel/tsc.c:1148
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8102c306-ffffffff8102c32f: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff8102bc60-ffffffff8102bc9d: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c944)
Location: arch/x86/kernel/tsc.c:1148
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8103c944-ffffffff8103c96d: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff8103bc80-ffffffff8103bcbd: mark_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_tsc_unstable(char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103d9d4)
Location: arch/x86/kernel/tsc.c:1148
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_setup
  - arch/x86/kernel/tsc.c:notsc_setup
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
**Symbols:**

```
ffffffff8103d9d4-ffffffff8103d9fd: mark_tsc_unstable.cold (STB_LOCAL)
ffffffff8103ccd0-ffffffff8103cd0d: mark_tsc_unstable (STB_GLOBAL)
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
