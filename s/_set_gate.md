# Function: <code>_set_gate</code>

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
In arch/x86/kernel/head64.c (ffffffff81f5938d)
Location: arch/x86/include/asm/desc.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107cb3c)
Location: arch/x86/include/asm/desc.h:344
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:early_trap_init
  - arch/x86/kernel/traps.c:early_trap_init
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
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107cc76)
Location: arch/x86/include/asm/desc.h:344
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f39e)
Location: arch/x86/include/asm/desc.h:344
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f74452)
Location: arch/x86/include/asm/desc.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff814c9db2)
Location: arch/x86/include/asm/desc.h:344
Inline: True
```
**Symbols:**

```
ffffffff8107cb3c-ffffffff8107cbd7: _set_gate.isra.6.constprop.22 (STB_LOCAL)
ffffffff8107cc76-ffffffff8107cd07: _set_gate.isra.2.constprop.5 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff81f81330)
Location: arch/x86/include/asm/desc.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8107e5a9)
Location: arch/x86/include/asm/desc.h:344
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
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:early_trap_pf_init
  - arch/x86/kernel/traps.c:early_trap_init
  - arch/x86/kernel/traps.c:early_trap_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff8107e6df)
Location: arch/x86/include/asm/desc.h:344
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f4ec)
Location: arch/x86/include/asm/desc.h:344
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81f9cc8a)
Location: arch/x86/include/asm/desc.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8151a930)
Location: arch/x86/include/asm/desc.h:344
Inline: True
```
**Symbols:**

```
ffffffff8107e5a9-ffffffff8107e644: _set_gate.isra.6.constprop.21 (STB_LOCAL)
ffffffff8107e6df-ffffffff8107e770: _set_gate.isra.2.constprop.5 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff81fbd330)
Location: arch/x86/include/asm/desc.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff81082b4f)
Location: arch/x86/include/asm/desc.h:344
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
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:early_trap_pf_init
  - arch/x86/kernel/traps.c:early_trap_init
  - arch/x86/kernel/traps.c:early_trap_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff81082cf2)
Location: arch/x86/include/asm/desc.h:344
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051cec)
Location: arch/x86/include/asm/desc.h:344
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81fd81dd)
Location: arch/x86/include/asm/desc.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff81546e02)
Location: arch/x86/include/asm/desc.h:344
Inline: True
```
**Symbols:**

```
ffffffff81082b4f-ffffffff81082bea: _set_gate.isra.6.constprop.20 (STB_LOCAL)
ffffffff81082cf2-ffffffff81082d83: _set_gate.isra.2.constprop.5 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff8209d32f)
Location: arch/x86/include/asm/desc.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff8102d1e3)
Location: arch/x86/include/asm/desc.h:451
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
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:early_trap_pf_init
  - arch/x86/kernel/traps.c:early_trap_init
  - arch/x86/kernel/traps.c:early_trap_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff810309f5)
Location: arch/x86/include/asm/desc.h:451
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105180c)
Location: arch/x86/include/asm/desc.h:451
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff820b9031)
Location: arch/x86/include/asm/desc.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
```
In drivers/xen/events/events_base.c (ffffffff8155abf0)
Location: arch/x86/include/asm/desc.h:451
Inline: True
```
**Symbols:**

```
ffffffff8102d1e3-ffffffff8102d27e: _set_gate.isra.6.constprop.20 (STB_LOCAL)
ffffffff810309f5-ffffffff81030a7f: _set_gate.isra.2.constprop.5 (STB_LOCAL)
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
