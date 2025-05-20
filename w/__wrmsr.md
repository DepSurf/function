# Function: <code>__wrmsr</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fb00)
Location: arch/x86/include/asm/msr.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fb79)
Location: arch/x86/include/asm/msr.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050749)
Location: arch/x86/include/asm/msr.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bc81)
Location: arch/x86/include/asm/msr.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c141)
Location: arch/x86/include/asm/msr.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81066731)
Location: arch/x86/include/asm/msr.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067050)
Location: arch/x86/include/asm/msr.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81042dcc)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053f4e)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054359)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fd21)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810601c1)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8106a901)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b1a1)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81044e22)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056b99)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057125)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062e30)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810632a0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8106d5d9)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106de20)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81046832)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81054229)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810546d5)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c93f)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068b30)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81068fa0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810738b9)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073f30)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810490f0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105744d)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057925)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fcaf)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c350)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c7d0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81077429)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077ab0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810499c0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057d1d)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810581f5)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106055f)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106cf00)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106da50)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106df20)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810784b9)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078b20)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e0a9)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe1e8)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105cef2)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105dd85)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106626f)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074280)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81074f30)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810753f0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107f7e9)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fe20)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d5d9)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c36ad8)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b752)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105ba55)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106451f)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074e30)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075540)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075a30)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107f449)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fa40)
Location: arch/x86/include/asm/msr.h:101
Inline: True
```
```
In arch/x86/kernel/sev-es.c (ffffffff82fd151f)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev-es.c:sev_es_ap_hlt_loop
  - arch/x86/kernel/sev-es.c:get_jump_table_addr
  - arch/x86/kernel/sev-es.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev-es.c:do_vc_no_ghcb
  - arch/x86/kernel/sev-es.c:do_vc_no_ghcb
  - arch/x86/kernel/sev-es.c:do_vc_no_ghcb
  - arch/x86/kernel/sev-es.c:do_vc_no_ghcb
  - arch/x86/kernel/sev-es.c:do_vc_no_ghcb
  - arch/x86/kernel/sev-es.c:sev_es_ghcb_hv_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f069)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c28f88)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c102)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c415)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064abf)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810758e0)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075fe0)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810764d0)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81080668)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080b62)
Location: arch/x86/include/asm/msr.h:101
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff831dc1c7)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81057165)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47208)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8106589c)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81065ad5)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106eb6f)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81082db0)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810835e0)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083b20)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8108f598)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fab2)
Location: arch/x86/include/asm/msr.h:101
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff832bf27d)
Location: arch/x86/include/asm/msr.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8103f166)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063602)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f1571d)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8107231c)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810725a5)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107c30e)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092ae0)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810934a0)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093b50)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810a0328)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a07c2)
Location: arch/x86/include/asm/msr.h:92
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff810a3b3e)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:sev_es_terminate
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034baa)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103866c)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048286)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107276b)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bcd4d)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108211f)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082575)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108d5e6)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a7c70)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8a00)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9260)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810b7e18)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b84f2)
Location: arch/x86/include/asm/msr.h:92
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff810bbf9e)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:sev_es_terminate
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/brs.c (ffffffff82139c78)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb
  - arch/x86/events/amd/brs.c:amd_brs_disable
  - arch/x86/events/amd/brs.c:amd_brs_enable_all
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/xen/pmu.c (ffffffff81034b2a)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81038479)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048636)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81074350)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213e75d)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810845bc)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810849e5)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81090496)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810aaee0)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abc30)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac480)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810bafa8)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb692)
Location: arch/x86/include/asm/msr.h:92
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff810bf2ae)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:sev_es_terminate
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In drivers/idle/intel_idle.c (ffffffff821437f5)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/brs.c (ffffffff8221bbe8)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb
  - arch/x86/events/amd/brs.c:amd_brs_disable
  - arch/x86/events/amd/brs.c:amd_brs_enable_all
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/xen/pmu.c (ffffffff8103ad2a)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103e7e9)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f016)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107b83f)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8222074d)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108bd15)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108bdd5)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097826)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a6311)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b1ec0)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2aa0)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b31a0)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810c23f9)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2aa2)
Location: arch/x86/include/asm/msr.h:92
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff810c65fe)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_cpuid_hv
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:sev_es_terminate
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In drivers/idle/intel_idle.c (ffffffff82225f13)
Location: arch/x86/include/asm/msr.h:92
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81049b30)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105789d)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057d75)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810600df)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c9f0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cec0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810774b9)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077b20)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810064e5)
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff810086ef)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff810093f1)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100c2a0)
Location: arch/x86/include/asm/msr.h:103
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
```
```
In arch/x86/events/intel/ds.c (ffffffff81010e87)
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810121ec)
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81013922)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81013ba0)
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
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
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f218)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8102001f)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8102d991)
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103693d)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037af0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8103837b)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81039242)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff810398b0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81039a5e)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103ac6a)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8103b510)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:native_write_msr
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b820)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103e261)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103ffac)
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042b0b)
Location: arch/x86/include/asm/msr.h:103
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047a83)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81047f65)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810493e3)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b788)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e4bd)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810504ed)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055417)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105627a)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105d10a)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d7e1)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/crash.c (ffffffff810605b5)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061d35)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff81066c25)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810674f9)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106bf26)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8107430d)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff815458be)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815b1cb0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818358d5)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81837bd4)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183a65d)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828f65ad)
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - drivers/hv/vmbus_drv.c:vmbus_on_msg_dpc
```
```
In drivers/hv/hv.c (ffffffff8184fb82)
Location: arch/x86/include/asm/msr.h:103
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
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
```
```
In arch/x86/pci/amd_bus.c (ffffffff8186343f)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81863779)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81049970)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057ccd)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810581a5)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106050f)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cea0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d370)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81077469)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077ad0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ad80)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105916d)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059645)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061a6f)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e5c0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f120)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f5f0)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810794a9)
Location: arch/x86/include/asm/msr.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079b70)
Location: arch/x86/include/asm/msr.h:103
Inline: True
```
</details>
</li>
</ul>

## Differences
