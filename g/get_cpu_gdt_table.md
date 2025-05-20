# Function: <code>get_cpu_gdt_table</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff81003f02)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/xen/enlighten.c (ffffffff8101bf26)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp.c (ffffffff8102b793)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040433)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:switch_to_new_gdt
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fb98)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051b96)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064760)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/power/cpu.c (ffffffff816faf3d)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/entry/vdso/vma.c (ffffffff81003e8d)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/xen/enlighten.c (ffffffff8101b351)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp.c (ffffffff8102ab07)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810411e7)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:switch_to_new_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fd12)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051d28)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/paravirt.c (ffffffff810643b0)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/power/cpu.c (ffffffff817603f1)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/entry/vdso/vma.c (ffffffff81003e7d)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/xen/enlighten.c (ffffffff8101bb81)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp.c (ffffffff8102ac97)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040c34)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:switch_to_new_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81052532)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054625)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067880)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/power/cpu.c (ffffffff8178d3f1)
Location: arch/x86/include/asm/desc.h:48
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
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
