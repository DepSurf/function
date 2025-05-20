# Function: <code>irq_matrix_online</code>

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
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff810f9150)
Location: kernel/irq/matrix.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff810f9150-ffffffff810f91e5: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811016a0)
Location: kernel/irq/matrix.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff811016a0-ffffffff81101735: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110cfc0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8110cfc0-ffffffff8110d055: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811166c0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff811166c0-ffffffff81116755: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81122a90)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff81122a90-ffffffff81122b25: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112f0e0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8112f0e0-ffffffff8112f175: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b0c0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8112b0c0-ffffffff8112b138: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8112b360)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8112b360-ffffffff8112b3d8: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff81caddef-ffffffff81cade19: irq_matrix_online.cold (STB_LOCAL)
ffffffff8114bd40-ffffffff8114bdec: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff81e5e30b-ffffffff81e5e335: irq_matrix_online.cold (STB_LOCAL)
ffffffff81171560-ffffffff8117162a: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff82059b9e-ffffffff82059bc8: irq_matrix_online.cold (STB_LOCAL)
ffffffff811a7b90-ffffffff811a7c5a: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff820d837d-ffffffff820d83a7: irq_matrix_online.cold (STB_LOCAL)
ffffffff811b9870-ffffffff811b993a: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/matrix.c (0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff821b35fe-ffffffff821b3628: irq_matrix_online.cold (STB_LOCAL)
ffffffff811c9730-ffffffff811c97fa: irq_matrix_online (STB_GLOBAL)
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
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8111b070)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8111b070-ffffffff8111b105: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff8110c0e0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff8110c0e0-ffffffff8110c175: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff81118f60)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff81118f60-ffffffff81118ff5: irq_matrix_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_matrix_online(struct irq_matrix *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/matrix.c (ffffffff811245f0)
Location: kernel/irq/matrix.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_online
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
```
**Symbols:**

```
ffffffff811245f0-ffffffff8112469b: irq_matrix_online (STB_GLOBAL)
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
