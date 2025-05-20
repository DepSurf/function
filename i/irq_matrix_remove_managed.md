# Function: <code>irq_matrix_remove_managed</code>

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
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff810f9340)
Location: kernel/irq/matrix.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff810f9340-ffffffff810f9468: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81101890)
Location: kernel/irq/matrix.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff81101890-ffffffff811019b8: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110d1b0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff8110d1b0-ffffffff8110d2d2: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811168b0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff811168b0-ffffffff811169d8: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81122c80)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff81122c80-ffffffff81122da8: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112f2d0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:vector_free_reserved_and_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff8112f2d0-ffffffff8112f3ea: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b240)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:vector_free_reserved_and_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff8112b240-ffffffff8112b340: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b4e0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff8112b4e0-ffffffff8112b5ee: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff81cade19-ffffffff81cade3c: irq_matrix_remove_managed.cold (STB_LOCAL)
ffffffff8114bef0-ffffffff8114c027: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff81e5e335-ffffffff81e5e352: irq_matrix_remove_managed.cold (STB_LOCAL)
ffffffff811717e0-ffffffff81171947: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff82059bc8-ffffffff82059be4: irq_matrix_remove_managed.cold (STB_LOCAL)
ffffffff811a7e40-ffffffff811a7fbe: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff820d83a7-ffffffff820d83c3: irq_matrix_remove_managed.cold (STB_LOCAL)
ffffffff811b9b20-ffffffff811b9c87: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff821b3628-ffffffff821b3644: irq_matrix_remove_managed.cold (STB_LOCAL)
ffffffff811c99e0-ffffffff811c9b47: irq_matrix_remove_managed (STB_GLOBAL)
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
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8111b260)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff8111b260-ffffffff8111b388: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110c2d0)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff8110c2d0-ffffffff8110c3f8: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81119150)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff81119150-ffffffff81119278: irq_matrix_remove_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_matrix_remove_managed(struct irq_matrix *m, const struct cpumask *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81124810)
Location: kernel/irq/matrix.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
```
**Symbols:**

```
ffffffff81124810-ffffffff81124951: irq_matrix_remove_managed (STB_GLOBAL)
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
