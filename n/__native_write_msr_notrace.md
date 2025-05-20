# Function: <code>__native_write_msr_notrace</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041a1a)
Location: arch/x86/include/asm/msr.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050311)
Location: arch/x86/include/asm/msr.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81051039)
Location: arch/x86/include/asm/msr.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c581)
Location: arch/x86/include/asm/msr.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105ca31)
Location: arch/x86/include/asm/msr.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81067441)
Location: arch/x86/include/asm/msr.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067d00)
Location: arch/x86/include/asm/msr.h:119
Inline: True
```
</details>
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
