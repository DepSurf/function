# Function: <code>irq_matrix_alloc_managed</code>

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
int irq_matrix_alloc_managed(struct irq_matrix *m, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff810f95b0)
Location: kernel/irq/matrix.c:244
Inline: False
```
**Symbols:**

```
ffffffff810f95b0-ffffffff810f9686: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81101b00)
Location: kernel/irq/matrix.c:242
Inline: False
```
**Symbols:**

```
ffffffff81101b00-ffffffff81101bd4: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110d420)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff8110d420-ffffffff8110d574: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81116b20)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff81116b20-ffffffff81116c74: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81122ef0)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff81122ef0-ffffffff81123044: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112f530)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff8112f530-ffffffff8112f680: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b460)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff8112b460-ffffffff8112b59d: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b710)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff8112b710-ffffffff8112b866: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff81cade57-ffffffff81cade89: irq_matrix_alloc_managed.cold (STB_LOCAL)
ffffffff8114c1a0-ffffffff8114c352: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff81e5e36d-ffffffff81e5e39d: irq_matrix_alloc_managed.cold (STB_LOCAL)
ffffffff81171b00-ffffffff81171cd7: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff82059c05-ffffffff82059c37: irq_matrix_alloc_managed.cold (STB_LOCAL)
ffffffff811a81a0-ffffffff811a8383: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff820d83e4-ffffffff820d8416: irq_matrix_alloc_managed.cold (STB_LOCAL)
ffffffff811b9e70-ffffffff811ba053: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff821b3665-ffffffff821b3697: irq_matrix_alloc_managed.cold (STB_LOCAL)
ffffffff811c9d30-ffffffff811c9f13: irq_matrix_alloc_managed (STB_GLOBAL)
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
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8111b4d0)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff8111b4d0-ffffffff8111b624: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110c540)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff8110c540-ffffffff8110c694: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811193c0)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff811193c0-ffffffff81119514: irq_matrix_alloc_managed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix *m, const struct cpumask *msk, unsigned int *mapped_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81124ac0)
Location: kernel/irq/matrix.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
**Symbols:**

```
ffffffff81124ac0-ffffffff81124c2d: irq_matrix_alloc_managed (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask *msk</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int *mapped_cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int cpu</code>
</li>
</ul>
</details>
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
