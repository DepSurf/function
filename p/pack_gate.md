# Function: <code>pack_gate</code>

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
In arch/x86/kernel/head64.c (ffffffff81f593a9)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107ca79)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:set_nmi_gate
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107cc20)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f3a9)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f7446c)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff814c9dbd)
Location: arch/x86/include/asm/desc.h:55
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
In arch/x86/kernel/head64.c (ffffffff81f81330)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107e4e6)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:set_nmi_gate
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107e689)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f4f3)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f9cca4)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8151a937)
Location: arch/x86/include/asm/desc.h:55
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
In arch/x86/kernel/head64.c (ffffffff81fbd330)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff81082af9)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:set_nmi_gate
```
```
In arch/x86/kernel/irqinit.c (ffffffff81082c9c)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051cf3)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81fd81f7)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff81546e09)
Location: arch/x86/include/asm/desc.h:55
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
In arch/x86/kernel/head64.c (ffffffff8209d32f)
Location: arch/x86/include/asm/desc.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8102d194)
Location: arch/x86/include/asm/desc.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:set_nmi_gate
```
```
In arch/x86/kernel/irqinit.c (ffffffff810309a6)
Location: arch/x86/include/asm/desc.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105181d)
Location: arch/x86/include/asm/desc.h:88
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff820b904b)
Location: arch/x86/include/asm/desc.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8155ac01)
Location: arch/x86/include/asm/desc.h:88
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
