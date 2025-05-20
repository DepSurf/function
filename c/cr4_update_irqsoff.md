# Function: <code>cr4_update_irqsoff</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049e00)
Location: arch/x86/kernel/cpu/common.c:397
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/smp.c:__sysvec_reboot
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
  - arch/x86/mm/tlb.c:cr4_update_pce
```
**Symbols:**

```
ffffffff81049e00-ffffffff81049e32: cr4_update_irqsoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810492a0)
Location: arch/x86/kernel/cpu/common.c:399
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/reboot.c:machine_real_restart
  - arch/x86/kernel/smp.c:__sysvec_reboot
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
  - arch/x86/mm/tlb.c:cr4_update_pce
```
**Symbols:**

```
ffffffff810492a0-ffffffff810492d2: cr4_update_irqsoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104ab70)
Location: arch/x86/kernel/cpu/common.c:398
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
  - arch/x86/kernel/reboot.c:cr4_clear_bits
  - arch/x86/kernel/smp.c:__sysvec_reboot
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
  - arch/x86/mm/tlb.c:cr4_update_pce
```
**Symbols:**

```
ffffffff8104ab70-ffffffff8104aba2: cr4_update_irqsoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81051ad0)
Location: arch/x86/kernel/cpu/common.c:406
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
  - arch/x86/kernel/smp.c:__sysvec_reboot
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
  - arch/x86/mm/tlb.c:cr4_update_pce
```
**Symbols:**

```
ffffffff81051ad0-ffffffff81051b02: cr4_update_irqsoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105d110)
Location: arch/x86/kernel/cpu/common.c:462
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
  - arch/x86/mm/tlb.c:cr4_update_pce
```
**Symbols:**

```
ffffffff8105d110-ffffffff8105d175: cr4_update_irqsoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106b510)
Location: arch/x86/kernel/cpu/common.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
  - arch/x86/mm/tlb.c:cr4_update_pce
```
**Symbols:**

```
ffffffff8106b510-ffffffff8106b575: cr4_update_irqsoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106cec0)
Location: arch/x86/kernel/cpu/common.c:451
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
  - arch/x86/mm/tlb.c:cr4_update_pce
```
**Symbols:**

```
ffffffff8106cec0-ffffffff8106cf25: cr4_update_irqsoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81074627)
Location: arch/x86/kernel/cpu/common.c:432
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
Direct callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
  - arch/x86/mm/tlb.c:cr4_update_pce
```
**Symbols:**

```
ffffffff81074690-ffffffff810746f5: cr4_update_irqsoff (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
