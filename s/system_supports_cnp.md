# Function: <code>system_supports_cnp</code>

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
In arch/arm64/kernel/cpufeature.c (ffff800010099f40)
Location: arch/arm64/include/asm/cpufeature.h:584
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6a00)
Location: arch/arm64/include/asm/cpufeature.h:584
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
```
```
In arch/arm64/mm/mmu.c (ffff800011438484)
Location: arch/arm64/include/asm/cpufeature.h:584
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:paging_init
```
```
In arch/arm64/mm/context.c (ffff8000100afa78)
Location: arch/arm64/include/asm/cpufeature.h:584
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010dae300)
Location: arch/arm64/include/asm/cpufeature.h:584
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:__activate_vm
```
```
In arch/arm64/kvm/hyp/tlb.c (ffff800010daf000)
Location: arch/arm64/include/asm/cpufeature.h:584
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/tlb.c:__tlb_switch_to_guest
  - arch/arm64/kvm/hyp/tlb.c:__tlb_switch_to_guest_vhe
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
