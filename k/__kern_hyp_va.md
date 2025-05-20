# Function: <code>__kern_hyp_va</code>

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
In virt/kvm/arm/arm.c (ffff8000100c5720)
Location: arch/arm64/include/asm/kvm_mmu.h:95
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
```
```
In virt/kvm/arm/mmu.c (ffff8000100ccd10)
Location: arch/arm64/include/asm/kvm_mmu.h:95
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:create_hyp_mappings
  - virt/kvm/arm/mmu.c:create_hyp_mappings
  - virt/kvm/arm/mmu.c:free_hyp_pgds
```
```
In arch/arm64/kvm/fpsimd.c (ffff8000100dab98)
Location: arch/arm64/include/asm/kvm_mmu.h:95
Inline: True
Inline callers:
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_run_map_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_run_map_fp
```
```
In virt/kvm/arm/hyp/vgic-v3-sr.c (ffff800010daca08)
Location: arch/arm64/include/asm/kvm_mmu.h:95
Inline: True
Inline callers:
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_restore_aprs
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_save_aprs
```
```
In arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c (ffff800010dad048)
Location: arch/arm64/include/asm/kvm_mmu.h:95
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c:__vgic_v2_perform_cpuif_access
```
```
In arch/arm64/kvm/hyp/debug-sr.c (ffff800010dae048)
Location: arch/arm64/include/asm/kvm_mmu.h:95
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_host
  - arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_host
  - arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_guest
  - arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_guest
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010daeba8)
Location: arch/arm64/include/asm/kvm_mmu.h:95
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
```
```
In arch/arm64/kvm/hyp/tlb.c (ffff800010daf198)
Location: arch/arm64/include/asm/kvm_mmu.h:95
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/tlb.c:__kvm_tlb_flush_local_vmid
  - arch/arm64/kvm/hyp/tlb.c:__kvm_tlb_flush_local_vmid
  - arch/arm64/kvm/hyp/tlb.c:__kvm_tlb_flush_vmid
  - arch/arm64/kvm/hyp/tlb.c:__kvm_tlb_flush_vmid_ipa
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
