# Function: <code>x86_match_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81041480)
Location: arch/x86/kernel/cpu/match.c:31
Inline: False
Direct callers:
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81041480-ffffffff8104151e: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff810413c0)
Location: arch/x86/kernel/cpu/match.c:31
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff810413c0-ffffffff81041464: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81040e10)
Location: arch/x86/kernel/cpu/match.c:31
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81040e10-ffffffff81040eb4: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8103edb0)
Location: arch/x86/kernel/cpu/match.c:31
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
**Symbols:**

```
ffffffff8103edb0-ffffffff8103ee48: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81041bc0)
Location: arch/x86/kernel/cpu/match.c:32
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
**Symbols:**

```
ffffffff81041bc0-ffffffff81041c5b: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff810435c0)
Location: arch/x86/kernel/cpu/match.c:32
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
**Symbols:**

```
ffffffff810435c0-ffffffff8104365b: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81044c60)
Location: arch/x86/kernel/cpu/match.c:32
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
**Symbols:**

```
ffffffff81044c60-ffffffff81044cfb: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81047290)
Location: arch/x86/kernel/cpu/match.c:32
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81047290-ffffffff81047324: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81047a10)
Location: arch/x86/kernel/cpu/match.c:32
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81047a10-ffffffff81047aa4: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8104b7b0)
Location: arch/x86/kernel/cpu/match.c:37
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff8104b7b0-ffffffff8104b86f: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8104acf0)
Location: arch/x86/kernel/cpu/match.c:37
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff8104acf0-ffffffff8104adaf: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8104c5d0)
Location: arch/x86/kernel/cpu/match.c:37
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff8104c5d0-ffffffff8104c68f: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/match.c (0)
Location: arch/x86/kernel/cpu/match.c:37
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:force_storage_d3
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81c9ab9e-ffffffff81c9abbf: x86_match_cpu.cold (STB_LOCAL)
ffffffff810538a0-ffffffff81053974: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/match.c (0)
Location: arch/x86/kernel/cpu/match.c:37
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:force_storage_d3
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81e4a00e-ffffffff81e4a02f: x86_match_cpu.cold (STB_LOCAL)
ffffffff8105f290-ffffffff8105f391: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/match.c (0)
Location: arch/x86/kernel/cpu/match.c:37
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:force_storage_d3
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff82052936-ffffffff82052957: x86_match_cpu.cold (STB_LOCAL)
ffffffff8106da40-ffffffff8106db2e: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/match.c (0)
Location: arch/x86/kernel/cpu/match.c:37
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_init
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:force_storage_d3
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff820d0df1-ffffffff820d0e0f: x86_match_cpu.cold (STB_LOCAL)
ffffffff8106f350-ffffffff8106f448: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/match.c (0)
Location: arch/x86/kernel/cpu/match.c:37
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_init
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:force_storage_d3
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff821ab914-ffffffff821ab932: x86_match_cpu.cold (STB_LOCAL)
ffffffff81076710-ffffffff81076808: x86_match_cpu (STB_GLOBAL)
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
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81047b80)
Location: arch/x86/kernel/cpu/match.c:32
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81047b80-ffffffff81047c14: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81036e80)
Location: arch/x86/kernel/cpu/match.c:32
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81036e80-ffffffff81036f14: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff810479c0)
Location: arch/x86/kernel/cpu/match.c:32
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff810479c0-ffffffff81047a54: x86_match_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct x86_cpu_id *x86_match_cpu(const struct x86_cpu_id *match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81048dd0)
Location: arch/x86/kernel/cpu/match.c:32
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/cpu/common.c:cpu_matches
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/cpufreq/speedstep-centrino.c:centrino_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/power/cpu.c:pm_check_save_msr
```
**Symbols:**

```
ffffffff81048dd0-ffffffff81048e64: x86_match_cpu (STB_GLOBAL)
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
