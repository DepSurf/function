# Function: <code>native_write_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d4f7)
Location: arch/x86/include/asm/msr.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e38d)
Location: arch/x86/include/asm/msr.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810642a1)
Location: arch/x86/include/asm/msr.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104dd0b)
Location: arch/x86/include/asm/msr.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e469)
Location: arch/x86/include/asm/msr.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81063f41)
Location: arch/x86/include/asm/msr.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064820)
Location: arch/x86/include/asm/msr.h:118
Inline: True
```
**Symbols:**

```
ffffffff81064820-ffffffff81064847: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041a1a)
Location: arch/x86/include/asm/msr.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050311)
Location: arch/x86/include/asm/msr.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81051039)
Location: arch/x86/include/asm/msr.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81067441)
Location: arch/x86/include/asm/msr.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067d00)
Location: arch/x86/include/asm/msr.h:129
Inline: True
```
**Symbols:**

```
ffffffff81067d00-ffffffff81067d27: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81066731)
Location: arch/x86/include/asm/msr.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067050)
Location: arch/x86/include/asm/msr.h:145
Inline: True
```
**Symbols:**

```
ffffffff81067050-ffffffff81067075: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8106a901)
Location: arch/x86/include/asm/msr.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b1a0)
Location: arch/x86/include/asm/msr.h:146
Inline: True
```
**Symbols:**

```
ffffffff8106b1a0-ffffffff8106b1c6: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8106d5d9)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106de20)
Location: arch/x86/include/asm/msr.h:160
Inline: True
```
**Symbols:**

```
ffffffff8106de20-ffffffff8106de43: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810738b9)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073f30)
Location: arch/x86/include/asm/msr.h:160
Inline: True
```
**Symbols:**

```
ffffffff81073f30-ffffffff81073f53: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81077429)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077ab0)
Location: arch/x86/include/asm/msr.h:160
Inline: True
```
**Symbols:**

```
ffffffff81077ab0-ffffffff81077ad2: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810784b9)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078b20)
Location: arch/x86/include/asm/msr.h:160
Inline: True
```
**Symbols:**

```
ffffffff81078b20-ffffffff81078b42: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8107f7e9)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fe20)
Location: arch/x86/include/asm/msr.h:160
Inline: True
```
**Symbols:**

```
ffffffff8107fe20-ffffffff8107fe42: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8107f449)
Location: arch/x86/include/asm/msr.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fa40)
Location: arch/x86/include/asm/msr.h:158
Inline: True
```
**Symbols:**

```
ffffffff8107fa40-ffffffff8107fa62: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81080668)
Location: arch/x86/include/asm/msr.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080b60)
Location: arch/x86/include/asm/msr.h:158
Inline: True
```
**Symbols:**

```
ffffffff81080b60-ffffffff81080b83: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8108f598)
Location: arch/x86/include/asm/msr.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fab0)
Location: arch/x86/include/asm/msr.h:158
Inline: True
```
**Symbols:**

```
ffffffff8108fab0-ffffffff8108fad0: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810a0328)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a07c0)
Location: arch/x86/include/asm/msr.h:143
Inline: True
```
**Symbols:**

```
ffffffff810a07c0-ffffffff810a07fc: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034baa)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103866c)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810b7e18)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b84f0)
Location: arch/x86/include/asm/msr.h:143
Inline: True
```
**Symbols:**

```
ffffffff810b84f0-ffffffff810b852c: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034b2a)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81038479)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810bafa8)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb690)
Location: arch/x86/include/asm/msr.h:143
Inline: True
```
**Symbols:**

```
ffffffff810bb690-ffffffff810bb6cc: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8103ad2a)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103e7e9)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810c23f9)
Location: arch/x86/include/asm/msr.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2aa0)
Location: arch/x86/include/asm/msr.h:143
Inline: True
```
**Symbols:**

```
ffffffff810c2aa0-ffffffff810c2adc: native_write_msr (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810774b9)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077b20)
Location: arch/x86/include/asm/msr.h:160
Inline: True
```
**Symbols:**

```
ffffffff81077b20-ffffffff81077b42: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff810064e5)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81007cfd)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff810086ef)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff810093f1)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100c2a0)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81010e87)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81011188)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810121ec)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
```
```
In arch/x86/events/intel/p4.c (ffffffff81012ce4)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81013922)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81013ba0)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810194ed)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019b55)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c7f4)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8101d295)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f218)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8102001f)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8102d991)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:enable_cpuid
```
```
In arch/x86/kernel/step.c (ffffffff81032f72)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103693d)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037af0)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8103837b)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81039242)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff810398b0)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81039a5e)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103ac6a)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8103b510)
Location: arch/x86/include/asm/msr.h:160
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b820)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103e261)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103ffac)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810410d0)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042b0b)
Location: arch/x86/include/asm/msr.h:160
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047b01)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810493e3)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b788)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e4bd)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810504ed)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055417)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105627a)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105d10a)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d7e1)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810605b5)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061d35)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff81066c25)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810674f9)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106bf26)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8107430d)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff815458be)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815b1cb0)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818358d5)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81837bd4)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/msr.h:160
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183a65d)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828f65ad)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184ec1e)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - drivers/hv/vmbus_drv.c:vmbus_on_msg_dpc
```
```
In drivers/hv/hv.c (ffffffff8184fb82)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
```
```
In drivers/hv/channel_mgmt.c (ffffffff81853477)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
```
```
In arch/x86/pci/amd_bus.c (ffffffff8186343f)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81863779)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8100a7e0-ffffffff8100a802: native_write_msr (STB_LOCAL)
ffffffff8101d070-ffffffff8101d092: native_write_msr (STB_LOCAL)
ffffffff81036f20-ffffffff81036f42: native_write_msr (STB_LOCAL)
ffffffff8103b510-ffffffff8103b532: native_write_msr (STB_LOCAL)
ffffffff8103b820-ffffffff8103b84c: native_write_msr.constprop.0 (STB_LOCAL)
ffffffff81055200-ffffffff8105522c: native_write_msr.constprop.0 (STB_LOCAL)
ffffffff810664d0-ffffffff810664f2: native_write_msr (STB_LOCAL)
ffffffff81067420-ffffffff81067442: native_write_msr (STB_LOCAL)
ffffffff815b1ad0-ffffffff815b1af2: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81077469)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077ad0)
Location: arch/x86/include/asm/msr.h:160
Inline: True
```
**Symbols:**

```
ffffffff81077ad0-ffffffff81077af2: native_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810794a9)
Location: arch/x86/include/asm/msr.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079b70)
Location: arch/x86/include/asm/msr.h:160
Inline: True
```
**Symbols:**

```
ffffffff81079b70-ffffffff81079b92: native_write_msr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int low</code> ➡️ <code>u32 low</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int high</code> ➡️ <code>u32 high</code>
</li>
</ul>
</details>
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
