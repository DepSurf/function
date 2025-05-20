# Function: <code>set_intr_gate</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102e000)
Location: arch/x86/kernel/idt.c:231
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:update_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff8102e000-ffffffff8102e06d: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102f080)
Location: arch/x86/kernel/idt.c:232
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:update_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff8102f080-ffffffff8102f0ed: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81030310)
Location: arch/x86/kernel/idt.c:232
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:update_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff81030310-ffffffff8103037d: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810320f0)
Location: arch/x86/kernel/idt.c:230
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:update_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff810320f0-ffffffff8103215d: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810329b0)
Location: arch/x86/kernel/idt.c:230
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:update_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff810329b0-ffffffff81032a1d: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff82ccef40)
Location: arch/x86/kernel/idt.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff82ccef40-ffffffff82ccefa6: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff82fbae06)
Location: arch/x86/kernel/idt.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff82fbae06-ffffffff82fbae6c: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff831c56a0)
Location: arch/x86/kernel/idt.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff831c56a0-ffffffff831c5706: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff832a63fd)
Location: arch/x86/kernel/idt.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff832a63fd-ffffffff832a6463: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff834555cf)
Location: arch/x86/kernel/idt.c:200
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff834555cf-ffffffff8345563f: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83e73460)
Location: arch/x86/kernel/idt.c:200
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff83e73460-ffffffff83e734d2: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83694f20)
Location: arch/x86/kernel/idt.c:200
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff83694f20-ffffffff83694f92: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff838c4e10)
Location: arch/x86/kernel/idt.c:203
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff838c4e10-ffffffff838c4e82: set_intr_gate (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032b10)
Location: arch/x86/kernel/idt.c:230
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:update_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff81032b10-ffffffff81032b7d: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81022460)
Location: arch/x86/kernel/idt.c:230
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:update_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff81022460-ffffffff810224cd: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032970)
Location: arch/x86/kernel/idt.c:230
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:update_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff81032970-ffffffff810329dd: set_intr_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810338d0)
Location: arch/x86/kernel/idt.c:230
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
  - arch/x86/kernel/idt.c:update_intr_gate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
```
**Symbols:**

```
ffffffff810338d0-ffffffff8103393d: set_intr_gate (STB_LOCAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
