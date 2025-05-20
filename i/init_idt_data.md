# Function: <code>init_idt_data</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81003024)
Location: arch/x86/include/asm/desc.h:386
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff82fbae22)
Location: arch/x86/include/asm/desc.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:set_intr_gate
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
In arch/x86/kernel/head64.c (ffffffff81003024)
Location: arch/x86/include/asm/desc.h:386
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff831c56bc)
Location: arch/x86/include/asm/desc.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:set_intr_gate
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
In arch/x86/kernel/head64.c (ffffffff8100309b)
Location: arch/x86/include/asm/desc.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_setup_idt
```
```
In arch/x86/kernel/idt.c (ffffffff832a6419)
Location: arch/x86/include/asm/desc.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:set_intr_gate
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
In arch/x86/kernel/head64.c (ffffffff81000ad3)
Location: arch/x86/include/asm/desc.h:407
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff834555eb)
Location: arch/x86/include/asm/desc.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:set_intr_gate
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
In arch/x86/kernel/head64.c (ffffffff81000b23)
Location: arch/x86/include/asm/desc.h:407
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff83e7347c)
Location: arch/x86/include/asm/desc.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:set_intr_gate
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
In arch/x86/kernel/head64.c (ffffffff81049ff7)
Location: arch/x86/include/asm/desc.h:407
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff83694f3c)
Location: arch/x86/include/asm/desc.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:set_intr_gate
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
In arch/x86/kernel/head64.c (ffffffff81051257)
Location: arch/x86/include/asm/desc.h:407
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff838c4e2c)
Location: arch/x86/include/asm/desc.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:set_intr_gate
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
