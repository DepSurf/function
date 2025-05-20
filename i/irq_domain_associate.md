# Function: <code>irq_domain_associate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e03d0)
Location: kernel/irq/irqdomain.c:339
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_associate_many
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
```
**Symbols:**

```
ffffffff810e03d0-ffffffff810e059a: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e5e10)
Location: kernel/irq/irqdomain.c:335
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff810e5e10-ffffffff810e5fe7: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec800)
Location: kernel/irq/irqdomain.c:358
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff810ec800-ffffffff810ec9d7: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec1c0)
Location: kernel/irq/irqdomain.c:495
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff810ec1c0-ffffffff810ec37d: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4b10)
Location: kernel/irq/irqdomain.c:515
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff810f4b10-ffffffff810f4cba: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:517
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff810fe4aa-ffffffff810fe4c8: irq_domain_associate.cold.25 (STB_LOCAL)
ffffffff810fcf10-ffffffff810fd094: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:517
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff81109c7a-ffffffff81109c98: irq_domain_associate.cold.24 (STB_LOCAL)
ffffffff811087c0-ffffffff81108944: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:531
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff8111330a-ffffffff81113329: irq_domain_associate.cold (STB_LOCAL)
ffffffff81111da0-ffffffff81111f2e: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:533
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff8111f4ea-ffffffff8111f509: irq_domain_associate.cold (STB_LOCAL)
ffffffff8111e020-ffffffff8111e1ae: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:518
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff8112ba3b-ffffffff8112ba59: irq_domain_associate.cold (STB_LOCAL)
ffffffff8112a260-ffffffff8112a405: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:539
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff81be1be1-ffffffff81be1bff: irq_domain_associate.cold (STB_LOCAL)
ffffffff81125d30-ffffffff81125ed5: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:541
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff81bd3c59-ffffffff81bd3c77: irq_domain_associate.cold (STB_LOCAL)
ffffffff81125dc0-ffffffff81125f65: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:562
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff81cadc8a-ffffffff81cadca8: irq_domain_associate.cold (STB_LOCAL)
ffffffff811467d0-ffffffff81146967: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:562
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff81e5e179-ffffffff81e5e197: irq_domain_associate.cold (STB_LOCAL)
ffffffff8116ab30-ffffffff8116acd1: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119fbef)
Location: kernel/irq/irqdomain.c:637
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff8119f920-ffffffff8119f972: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1754)
Location: kernel/irq/irqdomain.c:619
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff811b1480-ffffffff811b14d6: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1504)
Location: kernel/irq/irqdomain.c:619
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff811c1230-ffffffff811c1286: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010183680)
Location: kernel/irq/irqdomain.c:533
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffff800010183680-ffff80001018384c: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d2964)
Location: kernel/irq/irqdomain.c:533
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
c03d2964-c03d2b48: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001ddaf0)
Location: kernel/irq/irqdomain.c:533
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
c0000000001ddaf0-c0000000001dddb8: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a9d6)
Location: kernel/irq/irqdomain.c:533
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffe00011a9d6-ffffffe00011ab36: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:533
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff81117aca-ffffffff81117ae9: irq_domain_associate.cold (STB_LOCAL)
ffffffff81116600-ffffffff8111678e: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:533
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff811087ba-ffffffff811087d9: irq_domain_associate.cold (STB_LOCAL)
ffffffff811072f0-ffffffff8110747e: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:533
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff811159ba-ffffffff811159d9: irq_domain_associate.cold (STB_LOCAL)
ffffffff811144f0-ffffffff8111467e: irq_domain_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int irq_domain_associate(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:533
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff81120fea-ffffffff81121009: irq_domain_associate.cold (STB_LOCAL)
ffffffff8111fb20-ffffffff8111fcae: irq_domain_associate (STB_GLOBAL)
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
