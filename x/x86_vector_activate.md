# Function: <code>x86_vector_activate</code>

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
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105c1f0)
Location: arch/x86/kernel/apic/vector.c:430
Inline: False
```
**Symbols:**

```
ffffffff8105c1f0-ffffffff8105c474: x86_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f1c0)
Location: arch/x86/kernel/apic/vector.c:440
Inline: False
```
**Symbols:**

```
ffffffff8105f1c0-ffffffff8105f44e: x86_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81064e30)
Location: arch/x86/kernel/apic/vector.c:431
Inline: False
```
**Symbols:**

```
ffffffff81064e30-ffffffff810650c5: x86_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:428
Inline: False
```
**Symbols:**

```
ffffffff81068540-ffffffff810687b5: x86_vector_activate (STB_LOCAL)
ffffffff81068b30-ffffffff81068b66: x86_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:439
Inline: False
```
**Symbols:**

```
ffffffff81068e80-ffffffff81069127: x86_vector_activate (STB_LOCAL)
ffffffff810694a0-ffffffff810694ec: x86_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106f800)
Location: arch/x86/kernel/apic/vector.c:440
Inline: False
```
**Symbols:**

```
ffffffff8106f800-ffffffff8106f976: x86_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070d20)
Location: arch/x86/kernel/apic/vector.c:444
Inline: False
```
**Symbols:**

```
ffffffff81070d20-ffffffff81070e52: x86_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:444
Inline: False
```
**Symbols:**

```
ffffffff810714b0-ffffffff8107163f: x86_vector_activate (STB_LOCAL)
ffffffff81bc9246-ffffffff81bc925c: x86_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:444
Inline: False
```
**Symbols:**

```
ffffffff8107d2a0-ffffffff8107d42f: x86_vector_activate (STB_LOCAL)
ffffffff81c9dd32-ffffffff81c9dd48: x86_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:444
Inline: False
```
**Symbols:**

```
ffffffff8108c970-ffffffff8108cb17: x86_vector_activate (STB_LOCAL)
ffffffff81e4d1bf-ffffffff81e4d1d3: x86_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0f60)
Location: arch/x86/kernel/apic/vector.c:444
Inline: False
```
**Symbols:**

```
ffffffff810a0f60-ffffffff810a111b: x86_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3f50)
Location: arch/x86/kernel/apic/vector.c:444
Inline: False
```
**Symbols:**

```
ffffffff810a3f50-ffffffff810a410b: x86_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aaf80)
Location: arch/x86/kernel/apic/vector.c:455
Inline: False
```
**Symbols:**

```
ffffffff810aaf80-ffffffff810ab13b: x86_vector_activate (STB_LOCAL)
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
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:439
Inline: False
```
**Symbols:**

```
ffffffff81068970-ffffffff81068c17: x86_vector_activate (STB_LOCAL)
ffffffff81068f90-ffffffff81068fdc: x86_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:439
Inline: False
```
**Symbols:**

```
ffffffff81058ce0-ffffffff81058f87: x86_vector_activate (STB_LOCAL)
ffffffff81059300-ffffffff8105934c: x86_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:439
Inline: False
```
**Symbols:**

```
ffffffff81068e20-ffffffff810690c7: x86_vector_activate (STB_LOCAL)
ffffffff81069440-ffffffff8106948c: x86_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int x86_vector_activate(struct irq_domain *dom, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:439
Inline: False
```
**Symbols:**

```
ffffffff8106a510-ffffffff8106a7d5: x86_vector_activate (STB_LOCAL)
ffffffff8106ab3e-ffffffff8106ab8a: x86_vector_activate.cold (STB_LOCAL)
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
