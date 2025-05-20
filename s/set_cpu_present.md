# Function: <code>set_cpu_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_cpu_present(unsigned int cpu, bool present);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081f40)
Location: kernel/cpu.c:790
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
**Symbols:**

```
ffffffff81081f40-ffffffff81081f66: set_cpu_present (STB_GLOBAL)
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
In arch/x86/xen/smp.c (ffffffff81f8ca91)
Location: include/linux/cpumask.h:735
Inline: True
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8104fb26)
Location: include/linux/cpumask.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f97d7a)
Location: include/linux/cpumask.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_init_package_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81054715)
Location: include/linux/cpumask.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff81fa460f)
Location: include/linux/cpumask.h:735
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81514e05)
Location: include/linux/cpumask.h:735
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/smp.c (ffffffff81fc809c)
Location: include/linux/cpumask.h:740
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81052296)
Location: include/linux/cpumask.h:740
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81057413)
Location: include/linux/cpumask.h:740
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__generic_processor_info
```
```
In kernel/cpu.c (ffffffff81fdffbf)
Location: include/linux/cpumask.h:740
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81541297)
Location: include/linux/cpumask.h:740
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/smp_pv.c (ffffffff820a8746)
Location: include/linux/cpumask.h:783
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81051e66)
Location: include/linux/cpumask.h:783
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056b48)
Location: include/linux/cpumask.h:783
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff820c0dc3)
Location: include/linux/cpumask.h:783
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81555126)
Location: include/linux/cpumask.h:783
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/smp_pv.c (ffffffff826aed3d)
Location: include/linux/cpumask.h:787
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81055ad6)
Location: include/linux/cpumask.h:787
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105a8b1)
Location: include/linux/cpumask.h:787
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff826c8fbe)
Location: include/linux/cpumask.h:787
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff815b8c8a)
Location: include/linux/cpumask.h:787
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/smp_pv.c (ffffffff826d7fe5)
Location: include/linux/cpumask.h:789
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81058959)
Location: include/linux/cpumask.h:789
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105d7a6)
Location: include/linux/cpumask.h:789
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff826f316f)
Location: include/linux/cpumask.h:789
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff815f121a)
Location: include/linux/cpumask.h:789
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/smp_pv.c (ffffffff8288e005)
Location: include/linux/cpumask.h:801
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8105e579)
Location: include/linux/cpumask.h:801
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81063436)
Location: include/linux/cpumask.h:801
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828a9f5e)
Location: include/linux/cpumask.h:801
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8160be5a)
Location: include/linux/cpumask.h:801
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/smp_pv.c (ffffffff828a55a1)
Location: include/linux/cpumask.h:800
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81061989)
Location: include/linux/cpumask.h:800
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066acf)
Location: include/linux/cpumask.h:800
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828c2753)
Location: include/linux/cpumask.h:800
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8163fcdb)
Location: include/linux/cpumask.h:800
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/smp_pv.c (ffffffff828a8634)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81062219)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106713f)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828cad4f)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8166229b)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/smp_pv.c (ffffffff82ccdf84)
Location: include/linux/cpumask.h:835
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810681c9)
Location: include/linux/cpumask.h:835
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106dd12)
Location: include/linux/cpumask.h:835
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff82ced16c)
Location: include/linux/cpumask.h:835
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff817116a7)
Location: include/linux/cpumask.h:835
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:enable_hotplug_cpu
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
In arch/x86/xen/smp_pv.c (ffffffff82fb9db4)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81069ec9)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106f4b2)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff82fd97c6)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8172e3d7)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:enable_hotplug_cpu
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
In arch/x86/xen/smp_pv.c (ffffffff831c445a)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8106a999)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106ffe2)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff831e411a)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81712183)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
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
In arch/x86/xen/smp_pv.c (ffffffff832a5080)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81075264)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107ba52)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff832c7cf7)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8178ebf3)
Location: include/linux/cpumask.h:812
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_cpu_present(unsigned int cpu, bool present);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81e46fac)
Location: include/linux/cpumask.h:838
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81083c14)
Location: include/linux/cpumask.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108ac32)
Location: include/linux/cpumask.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff8347ad17)
Location: include/linux/cpumask.h:838
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff818c6c25)
Location: include/linux/cpumask.h:838
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
**Symbols:**

```
ffffffff81e46fac-ffffffff81e46fd7: set_cpu_present (STB_LOCAL)
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
In arch/x86/xen/smp_pv.c (ffffffff83e71905)
Location: include/linux/cpumask.h:947
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810969d4)
Location: include/linux/cpumask.h:947
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109ed48)
Location: include/linux/cpumask.h:947
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff83ea5858)
Location: include/linux/cpumask.h:947
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a175d3)
Location: include/linux/cpumask.h:947
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
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
In arch/x86/xen/smp_pv.c (ffffffff836927ea)
Location: include/linux/cpumask.h:999
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81099af4)
Location: include/linux/cpumask.h:999
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a1cbf)
Location: include/linux/cpumask.h:999
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff836c9f18)
Location: include/linux/cpumask.h:999
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a60663)
Location: include/linux/cpumask.h:999
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
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
In arch/x86/xen/smp_pv.c (ffffffff838c2338)
Location: include/linux/cpumask.h:1019
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810a131f)
Location: include/linux/cpumask.h:1019
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a75f4)
Location: include/linux/cpumask.h:1019
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:cpu_update_apic
```
```
In kernel/cpu.c (ffffffff838fabc8)
Location: include/linux/cpumask.h:1019
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81ab2ea3)
Location: include/linux/cpumask.h:1019
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
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
In arch/arm64/kernel/smp.c (ffff800011435d24)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:smp_prepare_cpus
  - arch/arm64/kernel/smp.c:smp_prepare_cpus
  - arch/arm64/kernel/smp.c:cpu_die_early
```
```
In kernel/cpu.c (ffff800011442280)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffff80001082b60c)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/arm/mach-qcom/platsmp.c (c1518ed8)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/arm/mach-qcom/platsmp.c:qcom_smp_prepare_cpus
```
```
In kernel/cpu.c (c151c274)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/firmware/qcom_scm-32.c (c0c36614)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/setup-common.c (c00000000134a334)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000fa0fc)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In kernel/cpu.c (c000000001365e84)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/riscv/kernel/smpboot.c (ffffffe00000352c)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/riscv/kernel/smpboot.c:smp_prepare_cpus
```
```
In kernel/cpu.c (ffffffe0000047e2)
Location: include/linux/cpumask.h:830
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
In arch/x86/xen/smp_pv.c (ffffffff82896644)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81061d99)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066c2f)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828b3b42)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8162810b)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/kernel/acpi/boot.c (ffffffff81052169)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056fff)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828abcc3)
Location: include/linux/cpumask.h:830
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
In arch/x86/xen/smp_pv.c (ffffffff828a9634)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810621b9)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810670df)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828c6a41)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff816560db)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/smp_pv.c (ffffffff828a9644)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81063779)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810686bf)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In kernel/cpu.c (ffffffff828cbd8c)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In drivers/xen/cpu_hotplug.c (ffffffff816706bb)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
