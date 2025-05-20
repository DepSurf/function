# Function: <code>assign_managed_vector</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105bc60)
Location: arch/x86/kernel/apic/vector.c:309
Inline: True
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff8105bc60-ffffffff8105bd72: assign_managed_vector.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105eb90)
Location: arch/x86/kernel/apic/vector.c:319
Inline: True
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff8105eb90-ffffffff8105ecab: assign_managed_vector.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81064ba0)
Location: arch/x86/kernel/apic/vector.c:311
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81064ba0-ffffffff81064cc1: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810682a0)
Location: arch/x86/kernel/apic/vector.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff810682a0-ffffffff810683ce: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068be0)
Location: arch/x86/kernel/apic/vector.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81068be0-ffffffff81068d0e: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106f380)
Location: arch/x86/kernel/apic/vector.c:309
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
```
**Symbols:**

```
ffffffff8106f380-ffffffff8106f4c0: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810708b0)
Location: arch/x86/kernel/apic/vector.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
```
**Symbols:**

```
ffffffff810708b0-ffffffff810709d6: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810710d0)
Location: arch/x86/kernel/apic/vector.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
```
**Symbols:**

```
ffffffff810710d0-ffffffff810711f6: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107ce60)
Location: arch/x86/kernel/apic/vector.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
```
**Symbols:**

```
ffffffff8107ce60-ffffffff8107cf83: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108c4e0)
Location: arch/x86/kernel/apic/vector.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
```
**Symbols:**

```
ffffffff8108c4e0-ffffffff8108c61e: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0a50)
Location: arch/x86/kernel/apic/vector.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
```
**Symbols:**

```
ffffffff810a0a50-ffffffff810a0b8e: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3a40)
Location: arch/x86/kernel/apic/vector.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
```
**Symbols:**

```
ffffffff810a3a40-ffffffff810a3b7e: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aaa70)
Location: arch/x86/kernel/apic/vector.c:324
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
```
**Symbols:**

```
ffffffff810aaa70-ffffffff810aabae: assign_managed_vector (STB_LOCAL)
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
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810686d0)
Location: arch/x86/kernel/apic/vector.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff810686d0-ffffffff810687fe: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058a40)
Location: arch/x86/kernel/apic/vector.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81058a40-ffffffff81058b6e: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068b80)
Location: arch/x86/kernel/apic/vector.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81068b80-ffffffff81068cae: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int assign_managed_vector(struct irq_data *irqd, const struct cpumask *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106a310)
Location: arch/x86/kernel/apic/vector.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff8106a310-ffffffff8106a457: assign_managed_vector (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
