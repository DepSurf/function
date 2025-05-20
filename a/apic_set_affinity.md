# Function: <code>apic_set_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irq_data, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055470)
Location: arch/x86/kernel/apic/vector.c:518
Inline: False
```
**Symbols:**

```
ffffffff81055470-ffffffff810554bd: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irq_data, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810556e0)
Location: arch/x86/kernel/apic/vector.c:520
Inline: False
```
**Symbols:**

```
ffffffff810556e0-ffffffff8105572d: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irq_data, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058430)
Location: arch/x86/kernel/apic/vector.c:520
Inline: False
```
**Symbols:**

```
ffffffff81058430-ffffffff8105847e: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irq_data, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81057b10)
Location: arch/x86/kernel/apic/vector.c:540
Inline: False
```
**Symbols:**

```
ffffffff81057b10-ffffffff81057b68: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105bd80)
Location: arch/x86/kernel/apic/vector.c:759
Inline: True
```
**Symbols:**

```
ffffffff8105bd80-ffffffff8105be18: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105ed70)
Location: arch/x86/kernel/apic/vector.c:770
Inline: False
```
**Symbols:**

```
ffffffff8105ed70-ffffffff8105ee0a: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81064cd0)
Location: arch/x86/kernel/apic/vector.c:761
Inline: False
```
**Symbols:**

```
ffffffff81064cd0-ffffffff81064d67: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810683d0)
Location: arch/x86/kernel/apic/vector.c:758
Inline: False
```
**Symbols:**

```
ffffffff810683d0-ffffffff81068476: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068d10)
Location: arch/x86/kernel/apic/vector.c:769
Inline: False
```
**Symbols:**

```
ffffffff81068d10-ffffffff81068db6: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106f980)
Location: arch/x86/kernel/apic/vector.c:777
Inline: False
```
**Symbols:**

```
ffffffff8106f980-ffffffff8106fa13: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070e60)
Location: arch/x86/kernel/apic/vector.c:822
Inline: False
```
**Symbols:**

```
ffffffff81070e60-ffffffff81070ef3: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81071640)
Location: arch/x86/kernel/apic/vector.c:855
Inline: False
```
**Symbols:**

```
ffffffff81071640-ffffffff810716cf: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107de60)
Location: arch/x86/kernel/apic/vector.c:855
Inline: False
```
**Symbols:**

```
ffffffff8107de60-ffffffff8107deef: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108cb20)
Location: arch/x86/kernel/apic/vector.c:855
Inline: False
```
**Symbols:**

```
ffffffff8108cb20-ffffffff8108cbc5: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a1130)
Location: arch/x86/kernel/apic/vector.c:851
Inline: False
```
**Symbols:**

```
ffffffff810a1130-ffffffff810a11d5: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a4120)
Location: arch/x86/kernel/apic/vector.c:851
Inline: False
```
**Symbols:**

```
ffffffff810a4120-ffffffff810a41c5: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810ab150)
Location: arch/x86/kernel/apic/vector.c:873
Inline: False
```
**Symbols:**

```
ffffffff810ab150-ffffffff810ab1f5: apic_set_affinity (STB_LOCAL)
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
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068800)
Location: arch/x86/kernel/apic/vector.c:769
Inline: False
```
**Symbols:**

```
ffffffff81068800-ffffffff810688a6: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058b70)
Location: arch/x86/kernel/apic/vector.c:769
Inline: False
```
**Symbols:**

```
ffffffff81058b70-ffffffff81058c16: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068cb0)
Location: arch/x86/kernel/apic/vector.c:769
Inline: False
```
**Symbols:**

```
ffffffff81068cb0-ffffffff81068d56: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int apic_set_affinity(struct irq_data *irqd, const struct cpumask *dest, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106a460)
Location: arch/x86/kernel/apic/vector.c:769
Inline: False
```
**Symbols:**

```
ffffffff8106a460-ffffffff8106a508: apic_set_affinity (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_data *irqd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct irq_data *irq_data</code>
</li>
</ul>
</details>
</li>
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
