# Function: <code>assign_irq_vector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int assign_irq_vector(int irq, struct apic_chip_data *data, const struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055040)
Location: arch/x86/kernel/apic/vector.c:229
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff81055040-ffffffff81055462: assign_irq_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int assign_irq_vector(int irq, struct apic_chip_data *data, const struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810552a0)
Location: arch/x86/kernel/apic/vector.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff810552a0-ffffffff810556d2: assign_irq_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int assign_irq_vector(int irq, struct apic_chip_data *data, const struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058040)
Location: arch/x86/kernel/apic/vector.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff81058040-ffffffff81058425: assign_irq_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int assign_irq_vector(int irq, struct apic_chip_data *data, const struct cpumask *mask, struct irq_data *irqdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81057700)
Location: arch/x86/kernel/apic/vector.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff81057700-ffffffff81057b02: assign_irq_vector (STB_LOCAL)
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
In arch/x86/kernel/apic/vector.c (ffffffff8105bf2f)
Location: arch/x86/kernel/apic/vector.c:258
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8105ef7a)
Location: arch/x86/kernel/apic/vector.c:268
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8106495a)
Location: arch/x86/kernel/apic/vector.c:260
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81068045)
Location: arch/x86/kernel/apic/vector.c:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81068985)
Location: arch/x86/kernel/apic/vector.c:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8106ff35)
Location: arch/x86/kernel/apic/vector.c:258
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8107138b)
Location: arch/x86/kernel/apic/vector.c:258
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81071c16)
Location: arch/x86/kernel/apic/vector.c:258
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8107da16)
Location: arch/x86/kernel/apic/vector.c:258
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8108d248)
Location: arch/x86/kernel/apic/vector.c:258
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810a186b)
Location: arch/x86/kernel/apic/vector.c:258
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
In arch/x86/kernel/apic/vector.c (ffffffff810a4859)
Location: arch/x86/kernel/apic/vector.c:258
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
In arch/x86/kernel/apic/vector.c (ffffffff810ab8e7)
Location: arch/x86/kernel/apic/vector.c:269
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81068475)
Location: arch/x86/kernel/apic/vector.c:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810587e5)
Location: arch/x86/kernel/apic/vector.c:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068925)
Location: arch/x86/kernel/apic/vector.c:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a075)
Location: arch/x86/kernel/apic/vector.c:257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_data *irqdata</code>
</li>
</ul>
</details>
</li>
</ul>
