# Function: <code>wrmsr</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f218)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8101fc22)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103693d)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8103837b)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103ac6a)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8103b707)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b9f3)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d348)
Location: arch/x86/include/asm/msr.h:273
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104179e)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042b0b)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81049018)
Location: arch/x86/include/asm/msr.h:273
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104afca)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104dd24)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810504ed)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810565f7)
Location: arch/x86/include/asm/msr.h:273
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105ce93)
Location: arch/x86/include/asm/msr.h:273
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d693)
Location: arch/x86/include/asm/msr.h:273
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066bf5)
Location: arch/x86/include/asm/msr.h:273
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff815458be)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818358d5)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81837bd4)
Location: arch/x86/include/asm/msr.h:273
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/msr.h:273
Inline: True
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
