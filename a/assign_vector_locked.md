# Function: <code>assign_vector_locked</code>

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
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105b780)
Location: arch/x86/kernel/apic/vector.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff8105b780-ffffffff8105b8da: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105e6d0)
Location: arch/x86/kernel/apic/vector.c:255
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff8105e6d0-ffffffff8105e83f: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81064360)
Location: arch/x86/kernel/apic/vector.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81064360-ffffffff8106449d: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81067a30)
Location: arch/x86/kernel/apic/vector.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81067a30-ffffffff81067b79: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068370)
Location: arch/x86/kernel/apic/vector.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81068370-ffffffff810684b9: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106f540)
Location: arch/x86/kernel/apic/vector.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
**Symbols:**

```
ffffffff8106f540-ffffffff8106f6a6: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070a60)
Location: arch/x86/kernel/apic/vector.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
**Symbols:**

```
ffffffff81070a60-ffffffff81070ba4: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81071280)
Location: arch/x86/kernel/apic/vector.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
**Symbols:**

```
ffffffff81071280-ffffffff810713c4: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107d010)
Location: arch/x86/kernel/apic/vector.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
**Symbols:**

```
ffffffff8107d010-ffffffff8107d151: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108c6a0)
Location: arch/x86/kernel/apic/vector.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
**Symbols:**

```
ffffffff8108c6a0-ffffffff8108c803: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0c70)
Location: arch/x86/kernel/apic/vector.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
**Symbols:**

```
ffffffff810a0c70-ffffffff810a0dd9: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3c60)
Location: arch/x86/kernel/apic/vector.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
**Symbols:**

```
ffffffff810a3c60-ffffffff810a3dcc: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aac90)
Location: arch/x86/kernel/apic/vector.c:233
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
**Symbols:**

```
ffffffff810aac90-ffffffff810aadfc: assign_vector_locked (STB_LOCAL)
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
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81067e60)
Location: arch/x86/kernel/apic/vector.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81067e60-ffffffff81067fa9: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810581d0)
Location: arch/x86/kernel/apic/vector.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff810581d0-ffffffff81058319: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068310)
Location: arch/x86/kernel/apic/vector.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81068310-ffffffff81068459: assign_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069a10)
Location: arch/x86/kernel/apic/vector.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81069a10-ffffffff81069b79: assign_vector_locked (STB_LOCAL)
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
