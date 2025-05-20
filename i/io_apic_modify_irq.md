# Function: <code>io_apic_modify_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81055ec0)
Location: arch/x86/kernel/apic/io_apic.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
```
**Symbols:**

```
ffffffff81055ec0-ffffffff81055f3e: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056110)
Location: arch/x86/kernel/apic/io_apic.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81056110-ffffffff81056196: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058ec0)
Location: arch/x86/kernel/apic/io_apic.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81058ec0-ffffffff81058f46: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058510)
Location: arch/x86/kernel/apic/io_apic.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81058510-ffffffff81058598: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ca20)
Location: arch/x86/kernel/apic/io_apic.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff8105ca20-ffffffff8105caaa: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105fa90)
Location: arch/x86/kernel/apic/io_apic.c:437
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff8105fa90-ffffffff8105fb1a: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065700)
Location: arch/x86/kernel/apic/io_apic.c:437
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81065700-ffffffff8106578a: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81068e20)
Location: arch/x86/kernel/apic/io_apic.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81068e20-ffffffff81068ea0: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810697a0)
Location: arch/x86/kernel/apic/io_apic.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff810697a0-ffffffff81069820: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071323)
Location: arch/x86/kernel/apic/io_apic.c:425
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
```
**Symbols:**

```
ffffffff810707c0-ffffffff81070840: io_apic_modify_irq (STB_LOCAL)
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81071de1)
Location: arch/x86/kernel/apic/io_apic.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810728f1)
Location: arch/x86/kernel/apic/io_apic.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107e897)
Location: arch/x86/kernel/apic/io_apic.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108e1bf)
Location: arch/x86/kernel/apic/io_apic.c:418
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a294f)
Location: arch/x86/kernel/apic/io_apic.c:418
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a59ef)
Location: arch/x86/kernel/apic/io_apic.c:419
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810ac96f)
Location: arch/x86/kernel/apic/io_apic.c:419
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
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
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069290)
Location: arch/x86/kernel/apic/io_apic.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81069290-ffffffff81069310: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810595f0)
Location: arch/x86/kernel/apic/io_apic.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff810595f0-ffffffff81059670: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069740)
Location: arch/x86/kernel/apic/io_apic.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff81069740-ffffffff810697c0: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data *data, int mask_and, int mask_or, void (*final)(struct irq_pin_list *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ae40)
Location: arch/x86/kernel/apic/io_apic.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq
  - arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq
```
**Symbols:**

```
ffffffff8106ae40-ffffffff8106aec0: io_apic_modify_irq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
