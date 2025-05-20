# Function: <code>irq_matrix_alloc</code>

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
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff810f9850)
Location: kernel/irq/matrix.c:324
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff810f9850-ffffffff810f996b: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81101d90)
Location: kernel/irq/matrix.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81101d90-ffffffff81101eb1: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110d730)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8110d730-ffffffff8110d855: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81116e30)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81116e30-ffffffff81116f56: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81123200)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81123200-ffffffff81123326: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112f830)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8112f830-ffffffff8112f97c: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b6d0)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8112b6d0-ffffffff8112b7fe: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b9a0)
Location: kernel/irq/matrix.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8112b9a0-ffffffff8112bae0: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81cadea5-ffffffff81caded7: irq_matrix_alloc.cold (STB_LOCAL)
ffffffff8114c470-ffffffff8114c60c: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81e5e3b9-ffffffff81e5e3e9: irq_matrix_alloc.cold (STB_LOCAL)
ffffffff81171ee0-ffffffff8117209d: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff82059c37-ffffffff82059c6b: irq_matrix_alloc.cold (STB_LOCAL)
ffffffff811a85d0-ffffffff811a8795: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff820d8416-ffffffff820d844a: irq_matrix_alloc.cold (STB_LOCAL)
ffffffff811ba2a0-ffffffff811ba465: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff821b3697-ffffffff821b36cb: irq_matrix_alloc.cold (STB_LOCAL)
ffffffff811ca160-ffffffff811ca325: irq_matrix_alloc (STB_GLOBAL)
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
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8111b7e0)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8111b7e0-ffffffff8111b906: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110c850)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8110c850-ffffffff8110c976: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811196d0)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff811196d0-ffffffff811197f6: irq_matrix_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_matrix_alloc(struct irq_matrix *m, const struct cpumask *msk, bool reserved, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81124e20)
Location: kernel/irq/matrix.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81124e20-ffffffff81124f5b: irq_matrix_alloc (STB_GLOBAL)
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
