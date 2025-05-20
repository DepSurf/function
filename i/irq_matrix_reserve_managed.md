# Function: <code>irq_matrix_reserve_managed</code>

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
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff810f9470)
Location: kernel/irq/matrix.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff810f9470-ffffffff810f95a8: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811019c0)
Location: kernel/irq/matrix.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff811019c0-ffffffff81101af5: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110d2e0)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff8110d2e0-ffffffff8110d415: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811169e0)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff811169e0-ffffffff81116b19: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81122db0)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff81122db0-ffffffff81122ee9: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112f3f0)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_managed_vector
```
**Symbols:**

```
ffffffff8112f3f0-ffffffff8112f52d: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b340)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_managed_vector
```
**Symbols:**

```
ffffffff8112b340-ffffffff8112b454: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b5f0)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff8112b5f0-ffffffff8112b704: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff81cade3c-ffffffff81cade57: irq_matrix_reserve_managed.cold (STB_LOCAL)
ffffffff8114c030-ffffffff8114c1a0: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff81e5e352-ffffffff81e5e36d: irq_matrix_reserve_managed.cold (STB_LOCAL)
ffffffff81171950-ffffffff81171af6: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:210
Inline: False
```
**Symbols:**

```
ffffffff82059be4-ffffffff82059c05: irq_matrix_reserve_managed.cold (STB_LOCAL)
ffffffff811a7fd0-ffffffff811a8186: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:210
Inline: False
```
**Symbols:**

```
ffffffff820d83c3-ffffffff820d83e4: irq_matrix_reserve_managed.cold (STB_LOCAL)
ffffffff811b9ca0-ffffffff811b9e56: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff821b3644-ffffffff821b3665: irq_matrix_reserve_managed.cold (STB_LOCAL)
ffffffff811c9b60-ffffffff811c9d16: irq_matrix_reserve_managed (STB_GLOBAL)
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
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8111b390)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff8111b390-ffffffff8111b4c9: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110c400)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff8110c400-ffffffff8110c539: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81119280)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff81119280-ffffffff811193b9: irq_matrix_reserve_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_matrix_reserve_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81124960)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
**Symbols:**

```
ffffffff81124960-ffffffff81124ab6: irq_matrix_reserve_managed (STB_GLOBAL)
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
