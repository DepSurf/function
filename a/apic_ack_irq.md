# Function: <code>apic_ack_irq</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f630)
Location: arch/x86/kernel/apic/vector.c:814
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff8105f630-ffffffff8105f663: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810652a0)
Location: arch/x86/kernel/apic/vector.c:805
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff810652a0-ffffffff810652d3: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068980)
Location: arch/x86/kernel/apic/vector.c:802
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff81068980-ffffffff810689b3: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810692f0)
Location: arch/x86/kernel/apic/vector.c:813
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff810692f0-ffffffff81069323: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106ec3c)
Location: arch/x86/kernel/apic/vector.c:811
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff810702f0-ffffffff81070323: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107024c)
Location: arch/x86/kernel/apic/vector.c:856
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff81071850-ffffffff81071883: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81071f2c)
Location: arch/x86/kernel/apic/vector.c:889
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff81072350-ffffffff81072383: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107dd4c)
Location: arch/x86/kernel/apic/vector.c:889
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff8107e230-ffffffff8107e263: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108be3b)
Location: arch/x86/kernel/apic/vector.c:889
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff8108d8b0-ffffffff8108d8ed: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a033b)
Location: arch/x86/kernel/apic/vector.c:885
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff810a1fc0-ffffffff810a1ffd: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a32bb)
Location: arch/x86/kernel/apic/vector.c:885
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff810a4fa0-ffffffff810a4fdd: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aa1fb)
Location: arch/x86/kernel/apic/vector.c:907
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff810ac030-ffffffff810ac067: apic_ack_irq (STB_GLOBAL)
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
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068de0)
Location: arch/x86/kernel/apic/vector.c:813
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff81068de0-ffffffff81068e13: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81059150)
Location: arch/x86/kernel/apic/vector.c:813
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff81059150-ffffffff81059183: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069290)
Location: arch/x86/kernel/apic/vector.c:813
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff81069290-ffffffff810692c3: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void apic_ack_irq(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106a990)
Location: arch/x86/kernel/apic/vector.c:813
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
```
**Symbols:**

```
ffffffff8106a990-ffffffff8106a9c3: apic_ack_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
