# Function: <code>mp_irqdomain_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056ab0)
Location: arch/x86/kernel/apic/io_apic.c:2966
Inline: True
```
**Symbols:**

```
ffffffff81056ab0-ffffffff81056ba9: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056d30)
Location: arch/x86/kernel/apic/io_apic.c:2963
Inline: True
```
**Symbols:**

```
ffffffff81056d30-ffffffff81056e19: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059ae0)
Location: arch/x86/kernel/apic/io_apic.c:2964
Inline: True
```
**Symbols:**

```
ffffffff81059ae0-ffffffff81059bc9: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058d10)
Location: arch/x86/kernel/apic/io_apic.c:2962
Inline: False
```
**Symbols:**

```
ffffffff81058d10-ffffffff81058de6: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105d1f0)
Location: arch/x86/kernel/apic/io_apic.c:2972
Inline: False
```
**Symbols:**

```
ffffffff8105d1f0-ffffffff8105d2c6: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810601b0)
Location: arch/x86/kernel/apic/io_apic.c:2965
Inline: False
```
**Symbols:**

```
ffffffff810601b0-ffffffff81060286: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065f20)
Location: arch/x86/kernel/apic/io_apic.c:2966
Inline: False
```
**Symbols:**

```
ffffffff81065f20-ffffffff81065ff6: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:3029
Inline: False
```
**Symbols:**

```
ffffffff8106b505-ffffffff8106b518: mp_irqdomain_free.cold (STB_LOCAL)
ffffffff810696e0-ffffffff8106979a: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a580)
Location: arch/x86/kernel/apic/io_apic.c:3032
Inline: True
```
**Symbols:**

```
ffffffff8106a580-ffffffff8106a644: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81070cc0)
Location: arch/x86/kernel/apic/io_apic.c:3025
Inline: False
```
**Symbols:**

```
ffffffff81070cc0-ffffffff81070d84: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810720d0)
Location: arch/x86/kernel/apic/io_apic.c:3050
Inline: False
```
**Symbols:**

```
ffffffff810720d0-ffffffff81072194: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072be0)
Location: arch/x86/kernel/apic/io_apic.c:3052
Inline: False
```
**Symbols:**

```
ffffffff81072be0-ffffffff81072ca4: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107eb70)
Location: arch/x86/kernel/apic/io_apic.c:3052
Inline: False
```
**Symbols:**

```
ffffffff8107eb70-ffffffff8107ec34: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108e4c0)
Location: arch/x86/kernel/apic/io_apic.c:3066
Inline: False
```
**Symbols:**

```
ffffffff8108e4c0-ffffffff8108e593: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a2c70)
Location: arch/x86/kernel/apic/io_apic.c:3066
Inline: False
```
**Symbols:**

```
ffffffff810a2c70-ffffffff810a2d43: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5d10)
Location: arch/x86/kernel/apic/io_apic.c:3073
Inline: False
```
**Symbols:**

```
ffffffff810a5d10-ffffffff810a5ddd: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810acd40)
Location: arch/x86/kernel/apic/io_apic.c:3069
Inline: False
```
**Symbols:**

```
ffffffff810acd40-ffffffff810ace0d: mp_irqdomain_free (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a070)
Location: arch/x86/kernel/apic/io_apic.c:3038
Inline: True
```
**Symbols:**

```
ffffffff8106a070-ffffffff8106a134: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a3d0)
Location: arch/x86/kernel/apic/io_apic.c:3032
Inline: True
```
**Symbols:**

```
ffffffff8105a3d0-ffffffff8105a494: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a520)
Location: arch/x86/kernel/apic/io_apic.c:3032
Inline: True
```
**Symbols:**

```
ffffffff8106a520-ffffffff8106a5e4: mp_irqdomain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mp_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bca0)
Location: arch/x86/kernel/apic/io_apic.c:3032
Inline: True
```
**Symbols:**

```
ffffffff8106bca0-ffffffff8106bd64: mp_irqdomain_free (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
