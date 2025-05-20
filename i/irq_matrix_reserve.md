# Function: <code>irq_matrix_reserve</code>

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
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff810f9760)
Location: kernel/irq/matrix.c:292
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff810f9760-ffffffff810f97e4: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:290
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81101fea-ffffffff81102003: irq_matrix_reserve.cold.5 (STB_LOCAL)
ffffffff81101cb0-ffffffff81101d22: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8110d99a-ffffffff8110d9b3: irq_matrix_reserve.cold.7 (STB_LOCAL)
ffffffff8110d650-ffffffff8110d6c2: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff811170aa-ffffffff811170c1: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff81116d50-ffffffff81116dc3: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8112347a-ffffffff81123491: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff81123120-ffffffff81123193: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8112faca-ffffffff8112fae3: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff8112f750-ffffffff8112f7c2: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81be1cbd-ffffffff81be1cdc: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff8112b620-ffffffff8112b679: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81bd3d77-ffffffff81bd3d93: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff8112b8f0-ffffffff8112b943: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:346
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81cade89-ffffffff81cadea5: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff8114c3e0-ffffffff8114c430: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:346
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81e5e39d-ffffffff81e5e3b9: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff81171de0-ffffffff81171e59: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811a84b0)
Location: kernel/irq/matrix.c:346
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff811a84b0-ffffffff811a8530: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811ba180)
Location: kernel/irq/matrix.c:346
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff811ba180-ffffffff811ba200: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811ca040)
Location: kernel/irq/matrix.c:346
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff811ca040-ffffffff811ca0c0: irq_matrix_reserve (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8111ba5a-ffffffff8111ba71: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff8111b700-ffffffff8111b773: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8110caca-ffffffff8110cae1: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff8110c770-ffffffff8110c7e3: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8111994a-ffffffff81119961: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff811195f0-ffffffff81119663: irq_matrix_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void irq_matrix_reserve(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:345
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff811250ba-ffffffff811250d1: irq_matrix_reserve.cold (STB_LOCAL)
ffffffff81124d10-ffffffff81124d95: irq_matrix_reserve (STB_GLOBAL)
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
