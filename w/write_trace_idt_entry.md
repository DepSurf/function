# Function: <code>write_trace_idt_entry</code>

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
In arch/x86/kernel/head64.c (ffffffff81f593ed)
Location: arch/x86/include/asm/desc.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107cafe)
Location: arch/x86/include/asm/desc.h:319
Inline: True
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107cc38)
Location: arch/x86/include/asm/desc.h:319
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f3f7)
Location: arch/x86/include/asm/desc.h:319
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f744c7)
Location: arch/x86/include/asm/desc.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff814c9e0b)
Location: arch/x86/include/asm/desc.h:319
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
In arch/x86/kernel/head64.c (ffffffff81f81382)
Location: arch/x86/include/asm/desc.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107e56b)
Location: arch/x86/include/asm/desc.h:319
Inline: True
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107e6a1)
Location: arch/x86/include/asm/desc.h:319
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f547)
Location: arch/x86/include/asm/desc.h:319
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f9ccfe)
Location: arch/x86/include/asm/desc.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8151a98b)
Location: arch/x86/include/asm/desc.h:319
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
In arch/x86/kernel/head64.c (ffffffff81fbd382)
Location: arch/x86/include/asm/desc.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff81082bb9)
Location: arch/x86/include/asm/desc.h:319
Inline: True
```
```
In arch/x86/kernel/irqinit.c (ffffffff81082cb4)
Location: arch/x86/include/asm/desc.h:319
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051d47)
Location: arch/x86/include/asm/desc.h:319
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81fd8251)
Location: arch/x86/include/asm/desc.h:319
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff81546e5d)
Location: arch/x86/include/asm/desc.h:319
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
In arch/x86/kernel/head64.c (ffffffff8209d377)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8102d24d)
Location: arch/x86/include/asm/desc.h:426
Inline: True
```
```
In arch/x86/kernel/irqinit.c (ffffffff810309bf)
Location: arch/x86/include/asm/desc.h:426
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105185b)
Location: arch/x86/include/asm/desc.h:426
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff820b909f)
Location: arch/x86/include/asm/desc.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8155ac3f)
Location: arch/x86/include/asm/desc.h:426
Inline: True
```
</details>
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
