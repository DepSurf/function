# Function: <code>irq_matrix_assign_system</code>

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
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff810f9270)
Location: kernel/irq/matrix.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff810f9270-ffffffff810f933a: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811017c0)
Location: kernel/irq/matrix.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff811017c0-ffffffff8110188a: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110d0e0)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8110d0e0-ffffffff8110d1a7: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811167e0)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff811167e0-ffffffff811168a9: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81122bb0)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff81122bb0-ffffffff81122c79: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112f200)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8112f200-ffffffff8112f2cc: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b1a0)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8112b1a0-ffffffff8112b234: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b440)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
```
**Symbols:**

```
ffffffff8112b440-ffffffff8112b4d5: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8114be50)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
```
**Symbols:**

```
ffffffff8114be50-ffffffff8114bee2: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811716d0)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
```
**Symbols:**

```
ffffffff811716d0-ffffffff811717de: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811a7d20)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
```
**Symbols:**

```
ffffffff811a7d20-ffffffff811a7e2e: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811b9a00)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
```
**Symbols:**

```
ffffffff811b9a00-ffffffff811b9b0e: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811c98c0)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
```
**Symbols:**

```
ffffffff811c98c0-ffffffff811c99ce: irq_matrix_assign_system (STB_GLOBAL)
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
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8111b190)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8111b190-ffffffff8111b259: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110c200)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8110c200-ffffffff8110c2c9: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81119080)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff81119080-ffffffff81119149: irq_matrix_assign_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_matrix_assign_system(struct irq_matrix *m, unsigned int bit, bool replace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81124730)
Location: kernel/irq/matrix.c:181
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff81124730-ffffffff81124809: irq_matrix_assign_system (STB_GLOBAL)
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
