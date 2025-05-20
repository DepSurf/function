# Function: <code>irq_domain_alloc_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e08f0)
Location: kernel/irq/irqdomain.c:838
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810e08f0-ffffffff810e0984: irq_domain_alloc_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6790)
Location: kernel/irq/irqdomain.c:881
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff810e6790-ffffffff810e6838: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed180)
Location: kernel/irq/irqdomain.c:907
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff810ed180-ffffffff810ed228: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecbf0)
Location: kernel/irq/irqdomain.c:1074
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff810ecbf0-ffffffff810ecc98: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f5640)
Location: kernel/irq/irqdomain.c:1087
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff810f5640-ffffffff810f56e8: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fd9f0)
Location: kernel/irq/irqdomain.c:971
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff810fd9f0-ffffffff810fda98: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811091c0)
Location: kernel/irq/irqdomain.c:971
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff811091c0-ffffffff81109268: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811127d0)
Location: kernel/irq/irqdomain.c:1008
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff811127d0-ffffffff81112865: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111ea60)
Location: kernel/irq/irqdomain.c:1010
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff8111ea60-ffffffff8111eaf5: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112b43d)
Location: kernel/irq/irqdomain.c:1012
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff81129c20-ffffffff81129ca1: irq_domain_alloc_descs.part.0 (STB_LOCAL)
ffffffff8112af60-ffffffff8112af94: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126ef2)
Location: kernel/irq/irqdomain.c:1036
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
**Symbols:**

```
ffffffff811255e0-ffffffff81125661: irq_domain_alloc_descs.part.0 (STB_LOCAL)
ffffffff811269a0-ffffffff811269d4: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126f7c)
Location: kernel/irq/irqdomain.c:1003
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
**Symbols:**

```
ffffffff811258b0-ffffffff81125931: irq_domain_alloc_descs.part.0 (STB_LOCAL)
ffffffff811269e0-ffffffff81126a14: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811474d8)
Location: kernel/irq/irqdomain.c:1042
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
**Symbols:**

```
ffffffff81146040-ffffffff811460c1: irq_domain_alloc_descs.part.0 (STB_LOCAL)
ffffffff81146fb0-ffffffff81146fe4: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116b68c)
Location: kernel/irq/irqdomain.c:1044
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
**Symbols:**

```
ffffffff8116a2d0-ffffffff8116a373: irq_domain_alloc_descs.part.0 (STB_LOCAL)
ffffffff8116b3b0-ffffffff8116b405: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a05cd)
Location: kernel/irq/irqdomain.c:1101
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
```
**Symbols:**

```
ffffffff8119ee30-ffffffff8119eed3: irq_domain_alloc_descs.part.0 (STB_LOCAL)
ffffffff811a0190-ffffffff811a01e5: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b2446)
Location: kernel/irq/irqdomain.c:1082
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
```
**Symbols:**

```
ffffffff811b0d10-ffffffff811b0db3: irq_domain_alloc_descs.part.0 (STB_LOCAL)
ffffffff811b2050-ffffffff811b20a5: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c2230)
Location: kernel/irq/irqdomain.c:1082
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
```
**Symbols:**

```
ffffffff811c0a90-ffffffff811c0b33: irq_domain_alloc_descs.part.0 (STB_LOCAL)
ffffffff811c1e00-ffffffff811c1e55: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101843f0)
Location: kernel/irq/irqdomain.c:1010
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffff8000101843f0-ffff8000101844c4: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3520)
Location: kernel/irq/irqdomain.c:1010
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
c03d3520-c03d35ec: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001ded30)
Location: kernel/irq/irqdomain.c:1010
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
c0000000001ded30-c0000000001dee44: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b43c)
Location: kernel/irq/irqdomain.c:1010
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffe00011b43c-ffffffe00011b4d4: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81117040)
Location: kernel/irq/irqdomain.c:1010
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff81117040-ffffffff811170d5: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107d30)
Location: kernel/irq/irqdomain.c:1010
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff81107d30-ffffffff81107dc5: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114f30)
Location: kernel/irq/irqdomain.c:1010
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff81114f30-ffffffff81114fc5: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120560)
Location: kernel/irq/irqdomain.c:1010
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff81120560-ffffffff811205f5: irq_domain_alloc_descs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask *affinity</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct cpumask *affinity</code> ➡️ <code>const struct irq_affinity_desc *affinity</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
