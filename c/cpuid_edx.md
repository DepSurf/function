# Function: <code>cpuid_edx</code>

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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f713)
Location: arch/x86/include/asm/processor.h:551
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104096a)
Location: arch/x86/include/asm/processor.h:551
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104276c)
Location: arch/x86/include/asm/processor.h:551
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810433e8)
Location: arch/x86/include/asm/processor.h:551
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f6d802)
Location: arch/x86/include/asm/processor.h:551
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810632da)
Location: arch/x86/include/asm/processor.h:551
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f4f3)
Location: arch/x86/include/asm/processor.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104088b)
Location: arch/x86/include/asm/processor.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042fdd)
Location: arch/x86/include/asm/processor.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81043388)
Location: arch/x86/include/asm/processor.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f95bc1)
Location: arch/x86/include/asm/processor.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81062f4d)
Location: arch/x86/include/asm/processor.h:562
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ef43)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810402d5)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810429c9)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81042e78)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81fd0f7d)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106643b)
Location: arch/x86/include/asm/processor.h:604
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103cf03)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e210)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81040ab8)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81040f53)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820b1ab6)
Location: arch/x86/include/asm/processor.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106574c)
Location: arch/x86/include/asm/processor.h:615
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103fa94)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040dae)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043d3c)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810443de)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81055538)
Location: arch/x86/include/asm/processor.h:637
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106991c)
Location: arch/x86/include/asm/processor.h:637
Inline: True
```
**Symbols:**

```
ffffffff81055538-ffffffff81055589: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041204)
Location: arch/x86/include/asm/processor.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042625)
Location: arch/x86/include/asm/processor.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810459b9)
Location: arch/x86/include/asm/processor.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81046695)
Location: arch/x86/include/asm/processor.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810583c0)
Location: arch/x86/include/asm/processor.h:653
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106c52f)
Location: arch/x86/include/asm/processor.h:653
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106d417)
Location: arch/x86/include/asm/processor.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff810583c0-ffffffff81058411: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810428a4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043c45)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047409)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81048915)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105dfe5)
Location: arch/x86/include/asm/processor.h:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81072378)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810735e7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff8105dfe5-ffffffff8105e036: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044d14)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810460f0)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a06b)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104b6d5)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104b9de)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810613e4)
Location: arch/x86/include/asm/processor.h:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075e89)
Location: arch/x86/include/asm/processor.h:638
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81077157)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff810613e4-ffffffff81061435: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045464)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046850)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a9fb)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c095)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c39e)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061c74)
Location: arch/x86/include/asm/processor.h:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81076e59)
Location: arch/x86/include/asm/processor.h:638
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81077757)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff81061c74-ffffffff81061cc5: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049282)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a864)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f7ad)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810508bf)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81050bee)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067b2f)
Location: arch/x86/include/asm/processor.h:672
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107e180)
Location: arch/x86/include/asm/processor.h:672
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107eab5)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff81067b2f-ffffffff81067b7e: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048732)
Location: arch/x86/include/asm/processor.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81049d14)
Location: arch/x86/include/asm/processor.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ea2a)
Location: arch/x86/include/asm/processor.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104fa23)
Location: arch/x86/include/asm/processor.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104fd4e)
Location: arch/x86/include/asm/processor.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bd6579)
Location: arch/x86/include/asm/processor.h:655
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107de40)
Location: arch/x86/include/asm/processor.h:655
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e6e5)
Location: arch/x86/include/asm/processor.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff81bd6579-ffffffff81bd65c8: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104a002)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b58a)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810501cd)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810515d3)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8105197a)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bc882b)
Location: arch/x86/include/asm/processor.h:637
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107ef60)
Location: arch/x86/include/asm/processor.h:637
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f755)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff81bc882b-ffffffff81bc887a: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81050ae2)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810526d5)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810584bd)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81059b63)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81059f0a)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c9d01b)
Location: arch/x86/include/asm/processor.h:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8108dbf0)
Location: arch/x86/include/asm/processor.h:649
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e515)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff81c9d01b-ffffffff81c9d06a: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105bfcc)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105e095)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81064c6b)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810662a8)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81066701)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81e4c3de)
Location: arch/x86/include/asm/processor.h:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81e4e6ad)
Location: arch/x86/include/asm/processor.h:649
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f395)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52a35)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
**Symbols:**

```
ffffffff81e4c3de-ffffffff81e4c43f: cpuid_edx (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81069fac)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106c627)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81073efb)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810755b8)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff810759e1)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e85548)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b5a56)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b69f5)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83efebcc)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106b8cc)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106dfb8)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81075dab)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81077728)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81077b4f)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a8a88)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b8b4c)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9b35)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83724a3c)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81072ce7)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81075238)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107d66d)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8107eca8)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8107f02f)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d9048)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810bff8c)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810c11d5)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff839588ac)
Location: arch/x86/include/asm/cpuid.h:121
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
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
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810455e4)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810469d0)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ab6b)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c205)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c50e)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810617f4)
Location: arch/x86/include/asm/processor.h:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075e59)
Location: arch/x86/include/asm/processor.h:638
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076757)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff810617f4-ffffffff81061845: cpuid_edx (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034a5e)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81035af0)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81039f2a)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8103b5c0)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b8dc)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82899b30)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81065e3a)
Location: arch/x86/include/asm/processor.h:638
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff828a1dfe)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045424)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046810)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a9ab)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c045)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c34e)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061c24)
Location: arch/x86/include/asm/processor.h:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075e09)
Location: arch/x86/include/asm/processor.h:638
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076707)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff81061c24-ffffffff81061c75: cpuid_edx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_edx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046824)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047c10)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104bdbb)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104d455)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104d75e)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810631d4)
Location: arch/x86/include/asm/processor.h:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81077e69)
Location: arch/x86/include/asm/processor.h:638
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810788d7)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
```
**Symbols:**

```
ffffffff810631d4-ffffffff81063225: cpuid_edx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
