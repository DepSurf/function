# Function: <code>vector_free_reserved_and_managed</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105b943)
Location: arch/x86/kernel/apic/vector.c:455
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8105e8d7)
Location: arch/x86/kernel/apic/vector.c:465
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81064537)
Location: arch/x86/kernel/apic/vector.c:456
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81067c1a)
Location: arch/x86/kernel/apic/vector.c:453
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8106855a)
Location: arch/x86/kernel/apic/vector.c:464
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vector_free_reserved_and_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106ed70)
Location: arch/x86/kernel/apic/vector.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
```
**Symbols:**

```
ffffffff8106ed70-ffffffff8106ee7e: vector_free_reserved_and_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vector_free_reserved_and_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070360)
Location: arch/x86/kernel/apic/vector.c:467
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
```
**Symbols:**

```
ffffffff81070360-ffffffff81070425: vector_free_reserved_and_managed (STB_LOCAL)
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
In arch/x86/kernel/apic/vector.c (ffffffff81071959)
Location: arch/x86/kernel/apic/vector.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8107d769)
Location: arch/x86/kernel/apic/vector.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8108cf8a)
Location: arch/x86/kernel/apic/vector.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810a149a)
Location: arch/x86/kernel/apic/vector.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810a448a)
Location: arch/x86/kernel/apic/vector.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810ab4ba)
Location: arch/x86/kernel/apic/vector.c:478
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff8106804a)
Location: arch/x86/kernel/apic/vector.c:464
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810583ba)
Location: arch/x86/kernel/apic/vector.c:464
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff810684fa)
Location: arch/x86/kernel/apic/vector.c:464
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
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
In arch/x86/kernel/apic/vector.c (ffffffff81069c1a)
Location: arch/x86/kernel/apic/vector.c:464
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
