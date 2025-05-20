# Function: <code>irq_domain_free_irqs_hierarchy</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed2d5)
Location: kernel/irq/irqdomain.c:1361
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f5cd1)
Location: kernel/irq/irqdomain.c:1361
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fe082)
Location: kernel/irq/irqdomain.c:1245
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81109852)
Location: kernel/irq/irqdomain.c:1245
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81112e41)
Location: kernel/irq/irqdomain.c:1282
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f0d1)
Location: kernel/irq/irqdomain.c:1284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
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
In kernel/irq/irqdomain.c (ffffffff8112b5b5)
Location: kernel/irq/irqdomain.c:1286
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_free_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126250)
Location: kernel/irq/irqdomain.c:1392
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
**Symbols:**

```
ffffffff81126250-ffffffff811262be: irq_domain_free_irqs_hierarchy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_free_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126270)
Location: kernel/irq/irqdomain.c:1359
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
**Symbols:**

```
ffffffff81126270-ffffffff811262de: irq_domain_free_irqs_hierarchy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_free_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146560)
Location: kernel/irq/irqdomain.c:1399
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
**Symbols:**

```
ffffffff81146560-ffffffff811465ce: irq_domain_free_irqs_hierarchy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_free_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116a850)
Location: kernel/irq/irqdomain.c:1402
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
**Symbols:**

```
ffffffff8116a850-ffffffff8116a8d6: irq_domain_free_irqs_hierarchy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_free_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119f430)
Location: kernel/irq/irqdomain.c:1462
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
**Symbols:**

```
ffffffff8119f430-ffffffff8119f4b6: irq_domain_free_irqs_hierarchy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_free_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1930)
Location: kernel/irq/irqdomain.c:1441
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
**Symbols:**

```
ffffffff811b1930-ffffffff811b19b6: irq_domain_free_irqs_hierarchy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_free_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c16e0)
Location: kernel/irq/irqdomain.c:1441
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
**Symbols:**

```
ffffffff811c16e0-ffffffff811c1766: irq_domain_free_irqs_hierarchy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010184c08)
Location: kernel/irq/irqdomain.c:1284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3cb8)
Location: kernel/irq/irqdomain.c:1284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011baba)
Location: kernel/irq/irqdomain.c:1284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811176b1)
Location: kernel/irq/irqdomain.c:1284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811083a1)
Location: kernel/irq/irqdomain.c:1284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811155a1)
Location: kernel/irq/irqdomain.c:1284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120bd1)
Location: kernel/irq/irqdomain.c:1284
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
