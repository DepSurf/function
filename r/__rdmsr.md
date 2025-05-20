# Function: <code>__rdmsr</code>

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
In arch/x86/kernel/cpu/intel.c (ffffffff8103fb18)
Location: arch/x86/include/asm/msr.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff820b131e)
Location: arch/x86/include/asm/msr.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fb91)
Location: arch/x86/include/asm/msr.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810511e6)
Location: arch/x86/include/asm/msr.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066f10)
Location: arch/x86/include/asm/msr.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int __rdmsr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81042de4)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826b7bad)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053f6c)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054ec6)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b041)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810804e3)
Location: arch/x86/include/asm/msr.h:91
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_enable
  - arch/x86/mm/mem_encrypt.c:sme_enable
```
**Symbols:**

```
ffffffff810804e3-ffffffff810804f4: __rdmsr (STB_LOCAL)
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
In arch/x86/kernel/cpu/intel.c (ffffffff81044e3a)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826e18b8)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056bb1)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057b84)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106dcd0)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0736)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104684a)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8289787a)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81054241)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81055524)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073d40)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a743e)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/kernel/cpu/intel.c (ffffffff81049108)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828af44e)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057465)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058756)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff810778c0)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bfb2f)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/kernel/cpu/intel.c (ffffffff810499d8)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b2787)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057d35)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059026)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078930)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5fad)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int __rdmsr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e0bf)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe1ca)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82cd777b)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105cf0c)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105e2c6)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fd40)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81095273)
Location: arch/x86/include/asm/msr.h:91
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81095273-ffffffff8109527f: __rdmsr (STB_LOCAL)
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104d5ef)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c36ab6)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82fc352d)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b76c)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c926)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f960)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/kernel/sev-es.c (ffffffff81bd8470)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:sev_es_rd_ghcb_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6c88)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104f07f)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c28f66)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff831cde7c)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c11c)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105d286)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff810809e0)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/kernel/sev.c (ffffffff81bca2ad)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_rd_ghcb_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e16bc)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/kernel/cpu/intel.c (ffffffff8105717b)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d471e6)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff832affff)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810658b6)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81066986)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f930)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/kernel/sev.c (ffffffff81c9f675)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_rd_ghcb_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4faf)
Location: arch/x86/include/asm/msr.h:89
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/hyperv/ivm.c (ffffffff8103f155)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d69d)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063618)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f156f5)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8346107d)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81072336)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8107351c)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a06b0)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/kernel/sev.c (ffffffff810a62d4)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:__sev_cpuid_hv
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477a64)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/xen/pmu.c (ffffffff81034a9f)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103707f)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048275)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106bbd8)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072781)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bcd25)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83e82f72)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81082139)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810837ac)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108d5ce)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8310)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/kernel/sev.c (ffffffff810beab4)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:__sev_cpuid_hv
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea12b9)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/events/amd/brs.c (ffffffff82139c59)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb
  - arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_disable
```
```
In arch/x86/xen/pmu.c (ffffffff81034a1f)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81036fcf)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048625)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d588)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81074366)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213e735)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff836a62d2)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810845d6)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085c5c)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8109047e)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb4a0)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/kernel/sev.c (ffffffff810c2134)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:__sev_cpuid_hv
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c5389)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd4f50)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
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
In arch/x86/events/amd/brs.c (ffffffff8221bbc9)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb
  - arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_disable
```
```
In arch/x86/xen/pmu.c (ffffffff8103ac1f)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d24f)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f3e3)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810747d8)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107b855)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220725)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff838d62dd)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108bd38)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff838d6be1)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8109780e)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c28b0)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/kernel/sev.c (ffffffff810c95b9)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:__sev_cpuid_hv
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5f89)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d0a0)
Location: arch/x86/include/asm/msr.h:80
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs
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
In arch/x86/kernel/cpu/intel.c (ffffffff81049b48)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828a07a6)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810578b5)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058ba6)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077930)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0f45)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/events/core.c (ffffffff81005980)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100775b)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff8288c27f)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/msr.c (ffffffff8100a29a)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_start
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100c27b)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8101063e)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81011159)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81012289)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
```
In arch/x86/events/intel/p4.c (ffffffff81012b6c)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810138f5)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81014de5)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016f22)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810191c0)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019df6)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101bc20)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8101d1e5)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f175)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8101f3f9)
Location: arch/x86/include/asm/msr.h:91
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff8288f927)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8101f440)
Location: arch/x86/include/asm/msr.h:91
Inline: True
```
```
In arch/x86/kernel/tsc.c (ffffffff82893aab)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8102c3ed)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff8102cfe3)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff81032f15)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81035edf)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828957d1)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81037d55)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff82895fcb)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103949b)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81039885)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81039b78)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a172)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103b13b)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8103b610)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b92a)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103e539)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103ff86)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041094)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042899)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff82896d0f)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810454c5)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81045faa)
Location: arch/x86/include/asm/msr.h:91
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8289891a)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047a9b)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048cd8)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8289933f)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104dd2b)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051bb5)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055379)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056235)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c9e3)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cfa0)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d810)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810605c5)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061d0f)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81065f27)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106be6f)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff810742ee)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a90ca)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
```
In kernel/kexec_core.c (ffffffff8114605a)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff81545590)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815b1c24)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/acpi/processor_perflib.c (ffffffff815f2369)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835945)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81837b45)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/msr.h:91
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828f1c81)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical
  - drivers/cpufreq/intel_pstate.c:core_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:airmont_get_scaling
  - drivers/cpufreq/intel_pstate.c:silvermont_get_scaling
  - drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828f656a)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
```
In drivers/hv/vmbus_drv.c (ffffffff828f6e6c)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
```
In drivers/hv/hv.c (ffffffff8184fb55)
Location: arch/x86/include/asm/msr.h:91
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
In arch/x86/pci/amd_bus.c (ffffffff818633f5)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff8186359e)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1d934)
Location: arch/x86/include/asm/msr.h:91
Inline: True
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
In arch/x86/kernel/cpu/intel.c (ffffffff81049988)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3769)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057ce5)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058fd6)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff810778e0)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3e44)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104ad98)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3797)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81059185)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105a476)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079980)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_read_msr
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6fea)
Location: arch/x86/include/asm/msr.h:91
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
