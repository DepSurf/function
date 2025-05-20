# Function: <code>apic_update_vector</code>

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
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105b620)
Location: arch/x86/kernel/apic/vector.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8105b620-ffffffff8105b772: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105e580)
Location: arch/x86/kernel/apic/vector.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8105e580-ffffffff8105e6d0: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81064210)
Location: arch/x86/kernel/apic/vector.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81064210-ffffffff81064360: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810678d0)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff810678d0-ffffffff81067a2f: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068210)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81068210-ffffffff8106836f: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106f200)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8106f200-ffffffff8106f379: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070770)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81070770-ffffffff810708aa: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070f90)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81070f90-ffffffff810710ca: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107cc70)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8107cc70-ffffffff8107ce5b: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108c2c0)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff8108c2c0-ffffffff8108c4d6: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a05d0)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff810a05d0-ffffffff810a07e6: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3550)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff810a3550-ffffffff810a3766: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aa520)
Location: arch/x86/kernel/apic/vector.c:142
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff810aa520-ffffffff810aa736: apic_update_vector (STB_LOCAL)
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
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81067d00)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81067d00-ffffffff81067e5f: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058070)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81058070-ffffffff810581cf: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810681b0)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff810681b0-ffffffff8106830f: apic_update_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void apic_update_vector(struct irq_data *irqd, unsigned int newvec, unsigned int newcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069890)
Location: arch/x86/kernel/apic/vector.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
```
**Symbols:**

```
ffffffff81069890-ffffffff81069a06: apic_update_vector (STB_LOCAL)
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
