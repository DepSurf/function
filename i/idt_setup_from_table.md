# Function: <code>idt_setup_from_table</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc *idt, const struct idt_data *t, int size, bool sys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102df40)
Location: arch/x86/kernel/idt.c:219
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_debugidt_traps
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
**Symbols:**

```
ffffffff8102df40-ffffffff8102dffa: idt_setup_from_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc *idt, const struct idt_data *t, int size, bool sys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102efc0)
Location: arch/x86/kernel/idt.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_debugidt_traps
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
**Symbols:**

```
ffffffff8102efc0-ffffffff8102f07a: idt_setup_from_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc *idt, const struct idt_data *t, int size, bool sys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81030250)
Location: arch/x86/kernel/idt.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_debugidt_traps
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
**Symbols:**

```
ffffffff81030250-ffffffff8103030a: idt_setup_from_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc *idt, const struct idt_data *t, int size, bool sys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032020)
Location: arch/x86/kernel/idt.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_debugidt_traps
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
**Symbols:**

```
ffffffff81032020-ffffffff810320e9: idt_setup_from_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc *idt, const struct idt_data *t, int size, bool sys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810328e0)
Location: arch/x86/kernel/idt.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_debugidt_traps
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
**Symbols:**

```
ffffffff810328e0-ffffffff810329a9: idt_setup_from_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff82ccee8c)
Location: arch/x86/kernel/idt.c:196
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:set_intr_gate
```
**Symbols:**

```
ffffffff82ccee8c-ffffffff82ccef40: idt_setup_from_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff82fbad52)
Location: arch/x86/kernel/idt.c:172
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:set_intr_gate
```
**Symbols:**

```
ffffffff82fbad52-ffffffff82fbae06: idt_setup_from_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff831c55ec)
Location: arch/x86/kernel/idt.c:172
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:set_intr_gate
```
**Symbols:**

```
ffffffff831c55ec-ffffffff831c56a0: idt_setup_from_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff832a6349)
Location: arch/x86/kernel/idt.c:180
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:set_intr_gate
```
**Symbols:**

```
ffffffff832a6349-ffffffff832a63fd: idt_setup_from_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83455504)
Location: arch/x86/kernel/idt.c:188
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:set_intr_gate
```
**Symbols:**

```
ffffffff83455504-ffffffff834555cf: idt_setup_from_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83e73370)
Location: arch/x86/kernel/idt.c:188
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:set_intr_gate
```
**Symbols:**

```
ffffffff83e73370-ffffffff83e73445: idt_setup_from_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83694e30)
Location: arch/x86/kernel/idt.c:188
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:set_intr_gate
```
**Symbols:**

```
ffffffff83694e30-ffffffff83694f05: idt_setup_from_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff838c4d20)
Location: arch/x86/kernel/idt.c:191
Inline: True
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:set_intr_gate
```
**Symbols:**

```
ffffffff838c4d20-ffffffff838c4df5: idt_setup_from_table.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc *idt, const struct idt_data *t, int size, bool sys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032a40)
Location: arch/x86/kernel/idt.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_debugidt_traps
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
**Symbols:**

```
ffffffff81032a40-ffffffff81032b09: idt_setup_from_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc *idt, const struct idt_data *t, int size, bool sys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810223a0)
Location: arch/x86/kernel/idt.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_debugidt_traps
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
**Symbols:**

```
ffffffff810223a0-ffffffff81022456: idt_setup_from_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc *idt, const struct idt_data *t, int size, bool sys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810328a0)
Location: arch/x86/kernel/idt.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_debugidt_traps
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
**Symbols:**

```
ffffffff810328a0-ffffffff81032969: idt_setup_from_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc *idt, const struct idt_data *t, int size, bool sys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81033800)
Location: arch/x86/kernel/idt.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_debugidt_traps
  - arch/x86/kernel/idt.c:idt_setup_ist_traps
  - arch/x86/kernel/idt.c:idt_setup_early_pf
  - arch/x86/kernel/idt.c:idt_setup_traps
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
**Symbols:**

```
ffffffff81033800-ffffffff810338c9: idt_setup_from_table (STB_LOCAL)
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
