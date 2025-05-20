# Function: <code>cpuid_ebx</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff810409ec)
Location: arch/x86/include/asm/processor.h:533
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044bfe)
Location: arch/x86/include/asm/processor.h:533
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810409e7)
Location: arch/x86/include/asm/processor.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/cpu/common.c (ffffffff8104042b)
Location: arch/x86/include/asm/processor.h:586
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81fd103b)
Location: arch/x86/include/asm/processor.h:586
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
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
In arch/x86/xen/enlighten_hvm.c (ffffffff820a3c06)
Location: arch/x86/include/asm/processor.h:597
Inline: True
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff820a7663)
Location: arch/x86/include/asm/processor.h:597
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e3c0)
Location: arch/x86/include/asm/processor.h:597
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820b1b74)
Location: arch/x86/include/asm/processor.h:597
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff826aa305)
Location: arch/x86/include/asm/processor.h:619
Inline: True
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826ade13)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040f42)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043853)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810554e7)
Location: arch/x86/include/asm/processor.h:619
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff815ba7c0)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
**Symbols:**

```
ffffffff810554e7-ffffffff81055538: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff826d3471)
Location: arch/x86/include/asm/processor.h:635
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826d7192)
Location: arch/x86/include/asm/processor.h:635
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810428b2)
Location: arch/x86/include/asm/processor.h:635
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81045b7e)
Location: arch/x86/include/asm/processor.h:635
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105836f)
Location: arch/x86/include/asm/processor.h:635
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff815f2461)
Location: arch/x86/include/asm/processor.h:635
Inline: True
```
**Symbols:**

```
ffffffff8105836f-ffffffff810583c0: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff82889395)
Location: arch/x86/include/asm/processor.h:630
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8288d226)
Location: arch/x86/include/asm/processor.h:630
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043ed4)
Location: arch/x86/include/asm/processor.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810475d8)
Location: arch/x86/include/asm/processor.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810483ab)
Location: arch/x86/include/asm/processor.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105df94)
Location: arch/x86/include/asm/processor.h:630
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff8160d951)
Location: arch/x86/include/asm/processor.h:630
Inline: True
```
**Symbols:**

```
ffffffff8105df94-ffffffff8105dfe5: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a0716)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a46b6)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046444)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a37f)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b145)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061393)
Location: arch/x86/include/asm/processor.h:620
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff816413ad)
Location: arch/x86/include/asm/processor.h:620
Inline: True
```
**Symbols:**

```
ffffffff81061393-ffffffff810613e4: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a3806)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a7746)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046ba4)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ad0f)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bb45)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061c23)
Location: arch/x86/include/asm/processor.h:620
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff81663d6d)
Location: arch/x86/include/asm/processor.h:620
Inline: True
```
**Symbols:**

```
ffffffff81061c23-ffffffff81061c74: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff82cc9ac6)
Location: arch/x86/include/asm/processor.h:654
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82ccdb26)
Location: arch/x86/include/asm/processor.h:654
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a94a)
Location: arch/x86/include/asm/processor.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104fa22)
Location: arch/x86/include/asm/processor.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050413)
Location: arch/x86/include/asm/processor.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105f048)
Location: arch/x86/include/asm/processor.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067bcd)
Location: arch/x86/include/asm/processor.h:654
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff81712f8b)
Location: arch/x86/include/asm/processor.h:654
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
```
**Symbols:**

```
ffffffff81067bcd-ffffffff81067c1c: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff82fb592b)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82fb9956)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81049dfa)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ec82)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f4e3)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d588)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bd6617)
Location: arch/x86/include/asm/processor.h:637
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff8172fd8b)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
```
**Symbols:**

```
ffffffff81bd6617-ffffffff81bd6666: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff831c0136)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff831c4016)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c5023)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b6aa)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81050413)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050fa3)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105deb8)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bc88c9)
Location: arch/x86/include/asm/processor.h:619
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff81713e23)
Location: arch/x86/include/asm/processor.h:619
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
**Symbols:**

```
ffffffff81bc88c9-ffffffff81bc8918: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff832a0904)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff832a4b76)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5d53)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810528cf)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058710)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810593db)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81067658)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c9d0b9)
Location: arch/x86/include/asm/processor.h:631
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff81790853)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
**Symbols:**

```
ffffffff81c9d0b9-ffffffff81c9d108: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8344a916)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8344f8e8)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83453d3a)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454e46)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105e34f)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810650dc)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065acd)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81074372)
Location: arch/x86/include/asm/processor.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81e4c4a0)
Location: arch/x86/include/asm/processor.h:631
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff818c8b0f)
Location: arch/x86/include/asm/processor.h:631
Inline: True
```
**Symbols:**

```
ffffffff81e4c4a0-ffffffff81e4c501: cpuid_ebx (STB_LOCAL)
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
In arch/x86/events/amd/core.c (ffffffff83e65234)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/lbr.c (ffffffff83e65617)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b479)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83e714d2)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e729fe)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106c915)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810743af)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81074dfd)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810845a2)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e85511)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff81a198f2)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
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
In arch/x86/events/amd/core.c (ffffffff836858b4)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/lbr.c (ffffffff83685c97)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368bf19)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83692333)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8369391e)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106e2f1)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107625c)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81076f6d)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086b52)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a8a51)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff81a62972)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
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
In arch/x86/events/amd/core.c (ffffffff838b4a44)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/lbr.c (ffffffff838b4e27)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbad9)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff838c1e43)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff838c3301)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810755ba)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107d340)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e4ed)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108da72)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d9011)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff81ab58d2)
Location: arch/x86/include/asm/cpuid.h:103
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
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
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff82891827)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82895756)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046d24)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ae7f)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bcb5)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810617a3)
Location: arch/x86/include/asm/processor.h:620
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff81629bdd)
Location: arch/x86/include/asm/processor.h:620
Inline: True
```
**Symbols:**

```
ffffffff810617a3-ffffffff810617f4: cpuid_ebx (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff81035daa)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a320)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103ae98)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82899b73)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4806)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8746)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046b64)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104acbf)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104baf5)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061bd3)
Location: arch/x86/include/asm/processor.h:620
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff81657bad)
Location: arch/x86/include/asm/processor.h:620
Inline: True
```
**Symbols:**

```
ffffffff81061bd3-ffffffff81061c24: cpuid_ebx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_ebx(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a47da)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8756)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047f64)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c0cf)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104cf05)
Location: arch/x86/include/asm/processor.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81063183)
Location: arch/x86/include/asm/processor.h:620
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In drivers/xen/grant-table.c (ffffffff816721ad)
Location: arch/x86/include/asm/processor.h:620
Inline: True
```
**Symbols:**

```
ffffffff81063183-ffffffff810631d4: cpuid_ebx (STB_LOCAL)
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
