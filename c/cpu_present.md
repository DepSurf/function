# Function: <code>cpu_present</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff810244e5)
Location: include/linux/cpumask.h:903
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (ffffffff810702c1)
Location: include/linux/cpumask.h:903
Inline: True
```
```
In kernel/cpu.c (ffffffff810a7329)
Location: include/linux/cpumask.h:903
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/cpudeadline.c (ffffffff81100f7a)
Location: include/linux/cpumask.h:903
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In drivers/acpi/acpi_processor.c (ffffffff8168e610)
Location: include/linux/cpumask.h:903
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81712179)
Location: include/linux/cpumask.h:903
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
In arch/x86/xen/apic.c (ffffffff810288c5)
Location: include/linux/cpumask.h:903
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (ffffffff8107be1d)
Location: include/linux/cpumask.h:903
Inline: True
```
```
In kernel/cpu.c (ffffffff810b8d29)
Location: include/linux/cpumask.h:903
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/cpudeadline.c (ffffffff8111d11a)
Location: include/linux/cpumask.h:903
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In drivers/acpi/acpi_processor.c (ffffffff81703ea3)
Location: include/linux/cpumask.h:903
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8178ebe9)
Location: include/linux/cpumask.h:903
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
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
In arch/x86/xen/apic.c (ffffffff8102cee5)
Location: include/linux/cpumask.h:929
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (ffffffff8108b06d)
Location: include/linux/cpumask.h:929
Inline: True
```
```
In kernel/cpu.c (ffffffff810cf669)
Location: include/linux/cpumask.h:929
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/build_policy.c (ffffffff81134f6e)
Location: include/linux/cpumask.h:929
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_clear
  - kernel/sched/build_policy.c:cpudl_find
```
```
In drivers/acpi/acpi_processor.c (ffffffff81831e76)
Location: include/linux/cpumask.h:929
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/xen/cpu_hotplug.c (ffffffff818c6c09)
Location: include/linux/cpumask.h:929
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
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
In arch/x86/xen/apic.c (ffffffff810341f5)
Location: include/linux/cpumask.h:1038
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (ffffffff8109f26d)
Location: include/linux/cpumask.h:1038
Inline: True
```
```
In kernel/cpu.c (ffffffff810eda5a)
Location: include/linux/cpumask.h:1038
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/build_policy.c (ffffffff8115f4ae)
Location: include/linux/cpumask.h:1038
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_clear
  - kernel/sched/build_policy.c:cpudl_find
```
```
In drivers/acpi/acpi_processor.c (ffffffff8196562b)
Location: include/linux/cpumask.h:1038
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a175c9)
Location: include/linux/cpumask.h:1038
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/apic.c (ffffffff81034185)
Location: include/linux/cpumask.h:1090
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a21fd)
Location: include/linux/cpumask.h:1090
Inline: True
```
```
In kernel/cpu.c (ffffffff810f9b4a)
Location: include/linux/cpumask.h:1090
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/build_policy.c (ffffffff8116fb9e)
Location: include/linux/cpumask.h:1090
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_clear
  - kernel/sched/build_policy.c:cpudl_find
```
```
In drivers/acpi/acpi_processor.c (ffffffff819abb92)
Location: include/linux/cpumask.h:1090
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a60659)
Location: include/linux/cpumask.h:1090
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
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
In arch/x86/xen/apic.c (ffffffff8103a3e5)
Location: include/linux/cpumask.h:1112
Inline: True
```
```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a8f6d)
Location: include/linux/cpumask.h:1112
Inline: True
```
```
In kernel/cpu.c (ffffffff81102f5a)
Location: include/linux/cpumask.h:1112
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/build_policy.c (ffffffff8117d0ee)
Location: include/linux/cpumask.h:1112
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_clear
  - kernel/sched/build_policy.c:cpudl_find
```
```
In drivers/acpi/acpi_processor.c (ffffffff819f5f32)
Location: include/linux/cpumask.h:1112
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81ab2e99)
Location: include/linux/cpumask.h:1112
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
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
