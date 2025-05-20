# Function: <code>native_write_cr4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bac6)
Location: arch/x86/include/asm/special_insns.h:82
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_cr4
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d545)
Location: arch/x86/include/asm/special_insns.h:82
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064560)
Location: arch/x86/include/asm/special_insns.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81064560-ffffffff81064569: native_write_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101aec0)
Location: arch/x86/include/asm/special_insns.h:82
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_cr4
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104dd68)
Location: arch/x86/include/asm/special_insns.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/paravirt.c (ffffffff810645e5)
Location: arch/x86/include/asm/special_insns.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff810641b0-ffffffff810641b9: native_write_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b5f0)
Location: arch/x86/include/asm/special_insns.h:74
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_cr4
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810506eb)
Location: arch/x86/include/asm/special_insns.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067ac5)
Location: arch/x86/include/asm/special_insns.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff810676a0-ffffffff810676a9: native_write_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101e670)
Location: arch/x86/include/asm/special_insns.h:74
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050529)
Location: arch/x86/include/asm/special_insns.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066d58)
Location: arch/x86/include/asm/special_insns.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81066960-ffffffff81066969: native_write_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f390)
Location: arch/x86/include/asm/special_insns.h:75
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106ae98)
Location: arch/x86/include/asm/special_insns.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff8106ab20-ffffffff8106ab29: native_write_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101fe65)
Location: arch/x86/include/asm/special_insns.h:75
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106db4f)
Location: arch/x86/include/asm/special_insns.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff8106d800-ffffffff8106d809: native_write_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f6e5)
Location: arch/x86/include/asm/special_insns.h:75
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073b9f)
Location: arch/x86/include/asm/special_insns.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff810739a0-ffffffff810739a9: native_write_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045870)
Location: arch/x86/kernel/cpu/common.c:391
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81045870-ffffffff810458c4: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045fc0)
Location: arch/x86/kernel/cpu/common.c:391
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81045fc0-ffffffff81046014: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a1c0)
Location: arch/x86/kernel/cpu/common.c:375
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff8104a1c0-ffffffff8104a21b: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049660)
Location: arch/x86/kernel/cpu/common.c:377
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81049660-ffffffff810496bb: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104ade0)
Location: arch/x86/kernel/cpu/common.c:376
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff8104ade0-ffffffff8104ae3b: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:384
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81c9a9dd-ffffffff81c9a9f1: native_write_cr4.cold (STB_LOCAL)
ffffffff81051e70-ffffffff81051edf: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:440
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81e49e64-ffffffff81e49e79: native_write_cr4.cold (STB_LOCAL)
ffffffff8105d750-ffffffff8105d7cd: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff820528c8-ffffffff820528dd: native_write_cr4.cold (STB_LOCAL)
ffffffff8106bc80-ffffffff8106bcfd: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:429
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff820d0d83-ffffffff820d0d98: native_write_cr4.cold (STB_LOCAL)
ffffffff8106d630-ffffffff8106d6ad: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:410
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff821ab8a7-ffffffff821ab8bc: native_write_cr4.cold (STB_LOCAL)
ffffffff81074880-ffffffff810748fd: native_write_cr4 (STB_GLOBAL)
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
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046140)
Location: arch/x86/kernel/cpu/common.c:391
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81046140-ffffffff81046194: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81035400)
Location: arch/x86/kernel/cpu/common.c:391
Inline: False
Direct callers:
  - arch/x86/events/core.c:refresh_pce
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_init
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/mm/init.c:cr4_set_bits
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81035400-ffffffff81035454: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045f80)
Location: arch/x86/kernel/cpu/common.c:391
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81045f80-ffffffff81045fd4: native_write_cr4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void native_write_cr4(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047380)
Location: arch/x86/kernel/cpu/common.c:391
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr4
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
**Symbols:**

```
ffffffff81047380-ffffffff810473d4: native_write_cr4 (STB_GLOBAL)
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
