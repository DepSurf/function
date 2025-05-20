# Function: <code>write_idt_entry</code>

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
In arch/x86/kernel/head64.c (ffffffff81f5938d)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107ca91)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:set_nmi_gate
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107cc38)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f3a5)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f74452)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff814c9db9)
Location: arch/x86/include/asm/paravirt.h:274
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
In arch/x86/kernel/head64.c (ffffffff81f81357)
Location: arch/x86/include/asm/paravirt.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107e4fe)
Location: arch/x86/include/asm/paravirt.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:set_nmi_gate
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107e6a1)
Location: arch/x86/include/asm/paravirt.h:273
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f504)
Location: arch/x86/include/asm/paravirt.h:273
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f9cc8a)
Location: arch/x86/include/asm/paravirt.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8151a948)
Location: arch/x86/include/asm/paravirt.h:273
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
In arch/x86/kernel/head64.c (ffffffff81fbd357)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff81082b11)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:set_nmi_gate
```
```
In arch/x86/kernel/irqinit.c (ffffffff81082cb4)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051d04)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81fd81dd)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff81546e1a)
Location: arch/x86/include/asm/paravirt.h:264
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
In arch/x86/kernel/head64.c (ffffffff8209d356)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8102d1ad)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:set_nmi_gate
```
```
In arch/x86/kernel/irqinit.c (ffffffff810309bf)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051813)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff820b9031)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8155abf7)
Location: arch/x86/include/asm/paravirt.h:264
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102df85)
Location: arch/x86/include/asm/paravirt.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102f034)
Location: arch/x86/include/asm/paravirt.h:256
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810302c4)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810320a3)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032963)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff82cceefa)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff82fbadc0)
Location: arch/x86/include/asm/paravirt.h:295
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff831c565a)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff832a63b7)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83455570)
Location: arch/x86/include/asm/paravirt.h:318
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83e733e3)
Location: arch/x86/include/asm/paravirt.h:318
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83694ea3)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff838c4d93)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032ac3)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032923)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81033883)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
</ul>

## Differences
