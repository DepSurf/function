# Function: <code>reserve_managed_vector</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff8105c08a)
Location: arch/x86/kernel/apic/vector.c:184
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
In arch/x86/kernel/apic/vector.c (ffffffff8105f0a8)
Location: arch/x86/kernel/apic/vector.c:185
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
In arch/x86/kernel/apic/vector.c (ffffffff81064a88)
Location: arch/x86/kernel/apic/vector.c:186
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
In arch/x86/kernel/apic/vector.c (ffffffff81068172)
Location: arch/x86/kernel/apic/vector.c:183
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
In arch/x86/kernel/apic/vector.c (ffffffff81068ab2)
Location: arch/x86/kernel/apic/vector.c:183
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int reserve_managed_vector(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106ec90)
Location: arch/x86/kernel/apic/vector.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff8106ec90-ffffffff8106ed63: reserve_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reserve_managed_vector(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810702a0)
Location: arch/x86/kernel/apic/vector.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff810702a0-ffffffff81070360: reserve_managed_vector (STB_LOCAL)
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
In arch/x86/kernel/apic/vector.c (ffffffff81071d4b)
Location: arch/x86/kernel/apic/vector.c:184
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
In arch/x86/kernel/apic/vector.c (ffffffff8107db48)
Location: arch/x86/kernel/apic/vector.c:184
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
In arch/x86/kernel/apic/vector.c (ffffffff8108d395)
Location: arch/x86/kernel/apic/vector.c:184
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
In arch/x86/kernel/apic/vector.c (ffffffff810a19a7)
Location: arch/x86/kernel/apic/vector.c:184
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
In arch/x86/kernel/apic/vector.c (ffffffff810a4995)
Location: arch/x86/kernel/apic/vector.c:184
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
In arch/x86/kernel/apic/vector.c (ffffffff810aba1a)
Location: arch/x86/kernel/apic/vector.c:195
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
In arch/x86/kernel/apic/vector.c (ffffffff810685a2)
Location: arch/x86/kernel/apic/vector.c:183
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
In arch/x86/kernel/apic/vector.c (ffffffff81058912)
Location: arch/x86/kernel/apic/vector.c:183
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
In arch/x86/kernel/apic/vector.c (ffffffff81068a52)
Location: arch/x86/kernel/apic/vector.c:183
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a1bb)
Location: arch/x86/kernel/apic/vector.c:183
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
