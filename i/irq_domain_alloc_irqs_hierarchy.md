# Function: <code>irq_domain_alloc_irqs_hierarchy</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ebc2f)
Location: kernel/irq/irqdomain.c:1368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff810ece90-ffffffff810ecea2: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f419f)
Location: kernel/irq/irqdomain.c:1369
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff810f58d0-ffffffff810f58e8: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fc61e)
Location: kernel/irq/irqdomain.c:1253
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff810fdc80-ffffffff810fdc98: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107dee)
Location: kernel/irq/irqdomain.c:1253
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff81109450-ffffffff81109468: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111131e)
Location: kernel/irq/irqdomain.c:1290
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff81112a50-ffffffff81112a68: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111d57e)
Location: kernel/irq/irqdomain.c:1292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff8111ece0-ffffffff8111ecf8: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112ac8e)
Location: kernel/irq/irqdomain.c:1294
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff8112b000-ffffffff8112b043: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112647e)
Location: kernel/irq/irqdomain.c:1407
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff81126a90-ffffffff81126ad3: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112649e)
Location: kernel/irq/irqdomain.c:1374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff81126ad0-ffffffff81126b13: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146e6e)
Location: kernel/irq/irqdomain.c:1414
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff81147050-ffffffff81147090: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116b23e)
Location: kernel/irq/irqdomain.c:1417
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff8116b480-ffffffff8116b4d3: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119fe5e)
Location: kernel/irq/irqdomain.c:1477
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff811a0280-ffffffff811a02d3: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1d31)
Location: kernel/irq/irqdomain.c:1456
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff811b2140-ffffffff811b2193: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1ae1)
Location: kernel/irq/irqdomain.c:1456
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff811c1ef0-ffffffff811c1f43: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010182870)
Location: kernel/irq/irqdomain.c:1292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffff800010184770-ffff8000101847c4: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d1c7c)
Location: kernel/irq/irqdomain.c:1292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
c03d3854-c03d3878: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe000119e00)
Location: kernel/irq/irqdomain.c:1292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffe00011b6fa-ffffffe00011b73a: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115b5e)
Location: kernel/irq/irqdomain.c:1292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff811172c0-ffffffff811172d8: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8110684e)
Location: kernel/irq/irqdomain.c:1292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff81107fb0-ffffffff81107fc8: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81113a4e)
Location: kernel/irq/irqdomain.c:1292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff811151b0-ffffffff811151c8: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f06e)
Location: kernel/irq/irqdomain.c:1292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff811207e0-ffffffff811207f8: irq_domain_alloc_irqs_hierarchy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
