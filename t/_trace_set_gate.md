# Function: <code>_trace_set_gate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81f59401)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107cacf)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:early_trap_pf_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107cc09)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f40b)
Location: arch/x86/include/asm/desc.h:324
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f744db)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff814c9e1f)
Location: arch/x86/include/asm/desc.h:324
Inline: True
```
**Symbols:**

```
ffffffff8107cacf-ffffffff8107cb3c: _trace_set_gate.isra.5.constprop.21 (STB_LOCAL)
ffffffff8107cc09-ffffffff8107cc76: _trace_set_gate.isra.1.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81f81397)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107e53c)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:early_trap_pf_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107e672)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f55c)
Location: arch/x86/include/asm/desc.h:324
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f9cd13)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8151a9a0)
Location: arch/x86/include/asm/desc.h:324
Inline: True
```
**Symbols:**

```
ffffffff8107e53c-ffffffff8107e5a9: _trace_set_gate.isra.5.constprop.20 (STB_LOCAL)
ffffffff8107e672-ffffffff8107e6df: _trace_set_gate.isra.1.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81fbd397)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff81082bea)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:early_trap_pf_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff81082c85)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051d5c)
Location: arch/x86/include/asm/desc.h:324
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81fd8266)
Location: arch/x86/include/asm/desc.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff81546e72)
Location: arch/x86/include/asm/desc.h:324
Inline: True
```
**Symbols:**

```
ffffffff81082bea-ffffffff81082c57: _trace_set_gate.isra.5.constprop.21 (STB_LOCAL)
ffffffff81082c85-ffffffff81082cf2: _trace_set_gate.isra.1.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8209d38c)
Location: arch/x86/include/asm/desc.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8102d27e)
Location: arch/x86/include/asm/desc.h:431
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:early_trap_pf_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff8103098f)
Location: arch/x86/include/asm/desc.h:431
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105186f)
Location: arch/x86/include/asm/desc.h:431
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff820b90b3)
Location: arch/x86/include/asm/desc.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8155ac53)
Location: arch/x86/include/asm/desc.h:431
Inline: True
```
**Symbols:**

```
ffffffff8102d27e-ffffffff8102d2e4: _trace_set_gate.isra.5.constprop.21 (STB_LOCAL)
ffffffff8103098f-ffffffff810309f5: _trace_set_gate.isra.1.constprop.4 (STB_LOCAL)
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
