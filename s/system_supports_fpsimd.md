# Function: <code>system_supports_fpsimd</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/fpsimd.c (ffff8000100887d8)
Location: arch/arm64/include/asm/cpufeature.h:567
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:kernel_neon_end
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_cpu_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_update_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_state_to_cpu
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_task_to_cpu
  - arch/arm64/kernel/fpsimd.c:fpsimd_signal_preserve_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_thread
  - arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch
  - arch/arm64/kernel/fpsimd.c:fpsimd_save
  - arch/arm64/kernel/fpsimd.c:task_fpsimd_load
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008d038)
Location: arch/arm64/include/asm/cpufeature.h:567
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:fpr_get
  - arch/arm64/kernel/ptrace.c:fpr_active
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010dae78c)
Location: arch/arm64/include/asm/cpufeature.h:567
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:__activate_traps
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
  - arch/arm64/kvm/hyp/switch.c:__activate_traps_fpsimd32
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
