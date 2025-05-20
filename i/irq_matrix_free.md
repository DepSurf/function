# Function: <code>irq_matrix_free</code>

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
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff810f9970)
Location: kernel/irq/matrix.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff810f9970-ffffffff810f9a37: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81101ec0)
Location: kernel/irq/matrix.c:366
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff81101ec0-ffffffff81101f87: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110d860)
Location: kernel/irq/matrix.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff8110d860-ffffffff8110d940: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81116f60)
Location: kernel/irq/matrix.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff81116f60-ffffffff81117044: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81123330)
Location: kernel/irq/matrix.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff81123330-ffffffff81123414: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112f980)
Location: kernel/irq/matrix.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff8112f980-ffffffff8112fa63: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b800)
Location: kernel/irq/matrix.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff8112b800-ffffffff8112b8a7: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112bae0)
Location: kernel/irq/matrix.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff8112bae0-ffffffff8112bb8e: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff81caded7-ffffffff81cadf15: irq_matrix_free.cold (STB_LOCAL)
ffffffff8114c610-ffffffff8114c735: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff81e5e3e9-ffffffff81e5e460: irq_matrix_free.cold (STB_LOCAL)
ffffffff811720a0-ffffffff8117221a: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff82059c6b-ffffffff82059ce2: irq_matrix_free.cold (STB_LOCAL)
ffffffff811a87b0-ffffffff811a892a: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff820d844a-ffffffff820d84c3: irq_matrix_free.cold (STB_LOCAL)
ffffffff811ba480-ffffffff811ba601: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff821b36cb-ffffffff821b3744: irq_matrix_free.cold (STB_LOCAL)
ffffffff811ca340-ffffffff811ca4c1: irq_matrix_free (STB_GLOBAL)
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
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8111b910)
Location: kernel/irq/matrix.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff8111b910-ffffffff8111b9f4: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110c980)
Location: kernel/irq/matrix.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff8110c980-ffffffff8110ca64: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81119800)
Location: kernel/irq/matrix.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff81119800-ffffffff811198e4: irq_matrix_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_matrix_free(struct irq_matrix *m, unsigned int cpu, unsigned int bit, bool managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81124f60)
Location: kernel/irq/matrix.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
**Symbols:**

```
ffffffff81124f60-ffffffff8112505a: irq_matrix_free (STB_GLOBAL)
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
