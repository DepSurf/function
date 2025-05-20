# Function: <code>set_cpu_possible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081f10)
Location: kernel/cpu.c:782
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/xen/smp.c:xen_smp_init
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
**Symbols:**

```
ffffffff81081f10-ffffffff81081f36: set_cpu_possible (STB_GLOBAL)
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
In arch/x86/xen/smp.c (ffffffff81f8cd5b)
Location: include/linux/cpumask.h:726
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f982b3)
Location: include/linux/cpumask.h:726
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:smp_init_package_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81054709)
Location: include/linux/cpumask.h:726
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff81fa461d)
Location: include/linux/cpumask.h:726
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp.c (ffffffff81fc8164)
Location: include/linux/cpumask.h:731
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_init
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff81fd37bc)
Location: include/linux/cpumask.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810573f1)
Location: include/linux/cpumask.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__generic_processor_info
```
```
In kernel/cpu.c (ffffffff81fdffcd)
Location: include/linux/cpumask.h:731
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff820a8812)
Location: include/linux/cpumask.h:774
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff820b4445)
Location: include/linux/cpumask.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056b36)
Location: include/linux/cpumask.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff820c0dd1)
Location: include/linux/cpumask.h:774
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff826aee09)
Location: include/linux/cpumask.h:778
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff826bab78)
Location: include/linux/cpumask.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105a89f)
Location: include/linux/cpumask.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff826c8fcc)
Location: include/linux/cpumask.h:778
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff826d80d1)
Location: include/linux/cpumask.h:780
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff826e496c)
Location: include/linux/cpumask.h:780
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105d794)
Location: include/linux/cpumask.h:780
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff826f317d)
Location: include/linux/cpumask.h:780
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff8288e0f1)
Location: include/linux/cpumask.h:792
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289b441)
Location: include/linux/cpumask.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81063424)
Location: include/linux/cpumask.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828a9f6c)
Location: include/linux/cpumask.h:792
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff828a5689)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b321c)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066abd)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828c2762)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff828a871c)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b6673)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106712d)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828cad5e)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102f573)
Location: include/linux/cpumask.h:826
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
```
```
In arch/x86/kernel/smpboot.c (ffffffff82cdb75b)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106dd00)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff82ced17b)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff8102f573-ffffffff8102f593: set_cpu_possible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81bd2d23)
Location: include/linux/cpumask.h:832
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
```
```
In arch/x86/kernel/smpboot.c (ffffffff82fc7bb1)
Location: include/linux/cpumask.h:832
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106f4a0)
Location: include/linux/cpumask.h:832
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff82fd97d5)
Location: include/linux/cpumask.h:832
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff81bd2d23-ffffffff81bd2d43: set_cpu_possible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81bc5072)
Location: include/linux/cpumask.h:803
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff831d2511)
Location: include/linux/cpumask.h:803
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106ffd0)
Location: include/linux/cpumask.h:803
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff831e4129)
Location: include/linux/cpumask.h:803
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff81bc5072-ffffffff81bc5092: set_cpu_possible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81c97bc1)
Location: include/linux/cpumask.h:803
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/smpboot.c (ffffffff832b4d4d)
Location: include/linux/cpumask.h:803
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107ba40)
Location: include/linux/cpumask.h:803
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff832c7d06)
Location: include/linux/cpumask.h:803
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff81c97bc1-ffffffff81c97be1: set_cpu_possible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81e46f81)
Location: include/linux/cpumask.h:829
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/smpboot.c (ffffffff8346661c)
Location: include/linux/cpumask.h:829
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108ac20)
Location: include/linux/cpumask.h:829
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff8347ad20)
Location: include/linux/cpumask.h:829
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff81e46f81-ffffffff81e46fac: set_cpu_possible (STB_LOCAL)
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
In arch/x86/xen/smp_pv.c (ffffffff83e718ee)
Location: include/linux/cpumask.h:938
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e8a007)
Location: include/linux/cpumask.h:938
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109ed36)
Location: include/linux/cpumask.h:938
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff83ea5861)
Location: include/linux/cpumask.h:938
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff836927d3)
Location: include/linux/cpumask.h:990
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/smpboot.c (ffffffff836ad6ad)
Location: include/linux/cpumask.h:990
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a1cad)
Location: include/linux/cpumask.h:990
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff836c9f21)
Location: include/linux/cpumask.h:990
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff838c2321)
Location: include/linux/cpumask.h:1010
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/smpboot.c (ffffffff838ddcfa)
Location: include/linux/cpumask.h:1010
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a75dd)
Location: include/linux/cpumask.h:1010
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:cpu_update_apic
```
```
In kernel/cpu.c (ffffffff838fabd1)
Location: include/linux/cpumask.h:1010
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
</details>
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
In arch/arm64/kernel/smp.c (ffff800011435b88)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:smp_init_cpus
```
```
In kernel/cpu.c (ffff800011442290)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/devtree.c (c15063a8)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps
```
```
In arch/arm/mach-imx/platsmp.c (c150f434)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/arm/mach-imx/platsmp.c:imx_smp_init_cpus
```
```
In arch/arm/mach-omap2/omap-smp.c (c15152d0)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_init_cpus
```
```
In kernel/cpu.c (c151c280)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/kernel/setup-common.c (c00000000134a34c)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
Direct callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In kernel/cpu.c (c000000001365e9c)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
c000000000030388-c0000000000303d0: set_cpu_possible.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/smpboot.c (ffffffe0000034a2)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/riscv/kernel/smpboot.c:setup_smp
```
```
In kernel/cpu.c (ffffffe0000047f0)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
</details>
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
In arch/x86/xen/smp_pv.c (ffffffff8289672c)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff828a467a)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066c1d)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828b3b51)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/kernel/smpboot.c (ffffffff8289c7bc)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056fed)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828abcd2)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff828a971c)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b758a)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810670cd)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828c6a50)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff828a972c)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b768b)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810686ad)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828cbd9b)
Location: include/linux/cpumask.h:821
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
</details>
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
</ul>
