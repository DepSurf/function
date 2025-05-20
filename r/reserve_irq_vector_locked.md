# Function: <code>reserve_irq_vector_locked</code>

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
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105bac0)
Location: arch/x86/kernel/apic/vector.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff8105bac0-ffffffff8105bb5f: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105e9d0)
Location: arch/x86/kernel/apic/vector.c:200
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff8105e9d0-ffffffff8105ea78: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81064630)
Location: arch/x86/kernel/apic/vector.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff81064630-ffffffff810646d8: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81067d00)
Location: arch/x86/kernel/apic/vector.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff81067d00-ffffffff81067da8: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068640)
Location: arch/x86/kernel/apic/vector.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff81068640-ffffffff810686e8: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106f140)
Location: arch/x86/kernel/apic/vector.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff8106f140-ffffffff8106f200: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810706c0)
Location: arch/x86/kernel/apic/vector.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff810706c0-ffffffff81070767: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070ef0)
Location: arch/x86/kernel/apic/vector.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff81070ef0-ffffffff81070f84: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107cbd0)
Location: arch/x86/kernel/apic/vector.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff8107cbd0-ffffffff8107cc61: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108c210)
Location: arch/x86/kernel/apic/vector.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff8108c210-ffffffff8108c2bb: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0990)
Location: arch/x86/kernel/apic/vector.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff810a0990-ffffffff810a0a3b: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3980)
Location: arch/x86/kernel/apic/vector.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff810a3980-ffffffff810a3a2b: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aa9b0)
Location: arch/x86/kernel/apic/vector.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff810aa9b0-ffffffff810aaa5b: reserve_irq_vector_locked (STB_LOCAL)
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
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068130)
Location: arch/x86/kernel/apic/vector.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff81068130-ffffffff810681d8: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810584a0)
Location: arch/x86/kernel/apic/vector.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff810584a0-ffffffff81058548: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810685e0)
Location: arch/x86/kernel/apic/vector.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff810685e0-ffffffff81068688: reserve_irq_vector_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reserve_irq_vector_locked(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069d20)
Location: arch/x86/kernel/apic/vector.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
```
**Symbols:**

```
ffffffff81069d20-ffffffff81069dd0: reserve_irq_vector_locked (STB_LOCAL)
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
