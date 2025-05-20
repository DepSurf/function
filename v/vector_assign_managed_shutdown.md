# Function: <code>vector_assign_managed_shutdown</code>

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
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105b460)
Location: arch/x86/kernel/apic/vector.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8105b460-ffffffff8105b491: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105e3b0)
Location: arch/x86/kernel/apic/vector.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8105e3b0-ffffffff8105e3e1: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81064040)
Location: arch/x86/kernel/apic/vector.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81064040-ffffffff81064071: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81067700)
Location: arch/x86/kernel/apic/vector.c:176
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81067700-ffffffff81067734: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068040)
Location: arch/x86/kernel/apic/vector.c:176
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81068040-ffffffff81068074: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106f891)
Location: arch/x86/kernel/apic/vector.c:177
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070da1)
Location: arch/x86/kernel/apic/vector.c:177
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070eb0)
Location: arch/x86/kernel/apic/vector.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81070eb0-ffffffff81070ee5: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107cb90)
Location: arch/x86/kernel/apic/vector.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8107cb90-ffffffff8107cbc5: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108c1d0)
Location: arch/x86/kernel/apic/vector.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff8108c1d0-ffffffff8108c210: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0940)
Location: arch/x86/kernel/apic/vector.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff810a0940-ffffffff810a0980: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3930)
Location: arch/x86/kernel/apic/vector.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff810a3930-ffffffff810a3970: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aa960)
Location: arch/x86/kernel/apic/vector.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff810aa960-ffffffff810aa9a0: vector_assign_managed_shutdown (STB_LOCAL)
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
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81067b30)
Location: arch/x86/kernel/apic/vector.c:176
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81067b30-ffffffff81067b64: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81057ea0)
Location: arch/x86/kernel/apic/vector.c:176
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81057ea0-ffffffff81057ed4: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81067fe0)
Location: arch/x86/kernel/apic/vector.c:176
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff81067fe0-ffffffff81068014: vector_assign_managed_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vector_assign_managed_shutdown(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810696b0)
Location: arch/x86/kernel/apic/vector.c:176
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
**Symbols:**

```
ffffffff810696b0-ffffffff810696e4: vector_assign_managed_shutdown (STB_LOCAL)
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
