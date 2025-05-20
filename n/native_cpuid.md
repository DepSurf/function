# Function: <code>native_cpuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f60622)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_check_mwait
  - arch/x86/xen/enlighten.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81f6cde9)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81f6ceb1)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e268)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd
```
```
In arch/x86/kernel/smpboot.c (ffffffff810527d2)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064600)
Location: arch/x86/include/asm/processor.h:197
Inline: False
```
**Symbols:**

```
ffffffff81064600-ffffffff8106461e: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f88288)
Location: arch/x86/include/asm/processor.h:195
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_check_mwait
  - arch/x86/xen/enlighten.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104cfe6)
Location: arch/x86/include/asm/processor.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104dba6)
Location: arch/x86/include/asm/processor.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e547)
Location: arch/x86/include/asm/processor.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd
```
```
In arch/x86/kernel/smpboot.c (ffffffff81052922)
Location: arch/x86/include/asm/processor.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064250)
Location: arch/x86/include/asm/processor.h:195
Inline: False
```
**Symbols:**

```
ffffffff81064250-ffffffff8106426e: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81fc3676)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_check_mwait
  - arch/x86/xen/enlighten.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041a2a)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f506)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050321)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810512e3)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
```
```
In arch/x86/kernel/smpboot.c (ffffffff81055232)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067720)
Location: arch/x86/include/asm/processor.h:210
Inline: False
```
**Symbols:**

```
ffffffff81067720-ffffffff8106773e: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff820a5841)
Location: arch/x86/include/asm/processor.h:203
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fb0f)
Location: arch/x86/include/asm/processor.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f456)
Location: arch/x86/include/asm/processor.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fb88)
Location: arch/x86/include/asm/processor.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054b26)
Location: arch/x86/include/asm/processor.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810669e0)
Location: arch/x86/include/asm/processor.h:203
Inline: False
```
**Symbols:**

```
ffffffff810669e0-ffffffff810669fe: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff826abf08)
Location: arch/x86/include/asm/processor.h:207
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81042ddb)
Location: arch/x86/include/asm/processor.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052ea6)
Location: arch/x86/include/asm/processor.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053f62)
Location: arch/x86/include/asm/processor.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/smpboot.c (ffffffff810588f2)
Location: arch/x86/include/asm/processor.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106aba0)
Location: arch/x86/include/asm/processor.h:207
Inline: False
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff81080529)
Location: arch/x86/include/asm/processor.h:207
Inline: True
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_enable
  - arch/x86/mm/mem_encrypt.c:sme_enable
  - arch/x86/mm/mem_encrypt.c:sme_enable
```
**Symbols:**

```
ffffffff8106aba0-ffffffff8106abbe: native_cpuid (STB_LOCAL)
ffffffff81080529-ffffffff81080547: native_cpuid.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff826d503b)
Location: arch/x86/include/asm/processor.h:205
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81044e31)
Location: arch/x86/include/asm/processor.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055b75)
Location: arch/x86/include/asm/processor.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056ba8)
Location: arch/x86/include/asm/processor.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b579)
Location: arch/x86/include/asm/processor.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106d860)
Location: arch/x86/include/asm/processor.h:205
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f06d9)
Location: arch/x86/include/asm/processor.h:205
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff8106d860-ffffffff8106d87e: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b05c)
Location: arch/x86/include/asm/processor.h:194
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81046841)
Location: arch/x86/include/asm/processor.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81053215)
Location: arch/x86/include/asm/processor.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81054238)
Location: arch/x86/include/asm/processor.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/smpboot.c (ffffffff81061203)
Location: arch/x86/include/asm/processor.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073a00)
Location: arch/x86/include/asm/processor.h:194
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a73e1)
Location: arch/x86/include/asm/processor.h:194
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81073a00-ffffffff81073a1e: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a24a8)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810490ff)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810563d5)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105745c)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/smpboot.c (ffffffff810648c3)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077560)
Location: arch/x86/include/asm/processor.h:197
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bfad1)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81077560-ffffffff8107757e: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a555c)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810499cf)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056c85)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057d2c)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064f43)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810785d0)
Location: arch/x86/include/asm/processor.h:197
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5f4f)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff810785d0-ffffffff810785ee: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccb904)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e0b6)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105be35)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105cf02)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b671)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f9d0)
Location: arch/x86/include/asm/processor.h:211
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce91a8)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff8107f9d0-ffffffff8107f9f4: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7772)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d5e6)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a885)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b762)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d311)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f600)
Location: arch/x86/include/asm/processor.h:211
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6c2e)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff8107f600-ffffffff8107f624: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff831c22a2)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f076)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b225)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c112)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dd81)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080710)
Location: arch/x86/include/asm/processor.h:211
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e167b)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81080710-ffffffff81080735: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff832a2d07)
Location: arch/x86/include/asm/processor.h:213
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81057172)
Location: arch/x86/include/asm/processor.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810647c5)
Location: arch/x86/include/asm/processor.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810658ac)
Location: arch/x86/include/asm/processor.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
```
In arch/x86/kernel/smpboot.c (ffffffff81079591)
Location: arch/x86/include/asm/processor.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f630)
Location: arch/x86/include/asm/processor.h:213
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4f6e)
Location: arch/x86/include/asm/processor.h:213
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff8108f630-ffffffff8108f655: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff83451a05)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8106360f)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810710b5)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8107232c)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088415)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a03a0)
Location: arch/x86/include/asm/processor.h:216
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477a3d)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff810a03a0-ffffffff810a03d9: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6e702)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072778)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81081185)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108212f)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bed5)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b7e60)
Location: arch/x86/include/asm/cpuid.h:30
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea1299)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff810b7e60-ffffffff810b7e99: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f1e2)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107435d)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81083605)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810845cc)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bda0)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb010)
Location: arch/x86/include/asm/cpuid.h:30
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c5369)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff810bb010-ffffffff810bb049: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff838bed32)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107b84c)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8108addc)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume
  - arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108bd2b)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a33a0)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2460)
Location: arch/x86/include/asm/cpuid.h:30
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5f69)
Location: arch/x86/include/asm/cpuid.h:30
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff810c2460-ffffffff810c2499: native_cpuid (STB_LOCAL)
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
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff82893565)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049b3f)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056805)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810578ac)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064a33)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810775d0)
Location: arch/x86/include/asm/processor.h:197
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0ee7)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff810775d0-ffffffff810775ee: native_cpuid (STB_LOCAL)
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
In arch/x86/events/amd/uncore.c (ffffffff81007e5e)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8288c249)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff8288c9d9)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8288e9a6)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff8288f149)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff82893a92)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289443e)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034d46)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_hygon_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810350d1)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103522c)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036b51)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103884f)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff8289609e)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a5da)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103afbb)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8103b56e)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b882)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103cf21)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff82896c57)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046a15)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047a92)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048419)
Location: arch/x86/include/asm/processor.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82898e7f)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82899928)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82899b1a)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82899e30)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81052915)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f64)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81053297)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054d0d)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/crash.c (ffffffff81060523)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81065e3a)
Location: arch/x86/include/asm/processor.h:197
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff828a1dd2)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81067cea)
Location: arch/x86/include/asm/processor.h:197
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a906c)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
```
In drivers/idle/intel_idle.c (ffffffff828d9456)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8183716d)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a655c)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104997f)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056c35)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057cdc)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064ee3)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077580)
Location: arch/x86/include/asm/processor.h:197
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3de6)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81077580-ffffffff8107759e: native_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6530)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ad8f)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810580d5)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105917c)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/smpboot.c (ffffffff810664c3)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079620)
Location: arch/x86/include/asm/processor.h:197
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6f8c)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81079620-ffffffff8107963e: native_cpuid (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
