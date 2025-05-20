# Function: <code>irq_domain_push_irq</code>

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
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f52e0)
Location: kernel/irq/irqdomain.c:1479
Inline: False
```
**Symbols:**

```
ffffffff810f52e0-ffffffff810f54c5: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fd6b0)
Location: kernel/irq/irqdomain.c:1363
Inline: False
```
**Symbols:**

```
ffffffff810fd6b0-ffffffff810fd895: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108b00)
Location: kernel/irq/irqdomain.c:1363
Inline: False
```
**Symbols:**

```
ffffffff81108b00-ffffffff81108ce5: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:1400
Inline: False
```
**Symbols:**

```
ffffffff8111334a-ffffffff8111337c: irq_domain_push_irq.cold (STB_LOCAL)
ffffffff811120f0-ffffffff811122cf: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111e370)
Location: kernel/irq/irqdomain.c:1402
Inline: False
```
**Symbols:**

```
ffffffff8111e370-ffffffff8111e556: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112b050)
Location: kernel/irq/irqdomain.c:1404
Inline: False
```
**Symbols:**

```
ffffffff8112b050-ffffffff8112b253: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126ae0)
Location: kernel/irq/irqdomain.c:1526
Inline: False
```
**Symbols:**

```
ffffffff81126ae0-ffffffff81126ce3: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126b20)
Location: kernel/irq/irqdomain.c:1493
Inline: False
```
**Symbols:**

```
ffffffff81126b20-ffffffff81126d23: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81147090)
Location: kernel/irq/irqdomain.c:1538
Inline: False
```
**Symbols:**

```
ffffffff81147090-ffffffff81147285: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116b900)
Location: kernel/irq/irqdomain.c:1542
Inline: False
```
**Symbols:**

```
ffffffff8116b900-ffffffff8116bafe: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a0ad0)
Location: kernel/irq/irqdomain.c:1610
Inline: False
```
**Symbols:**

```
ffffffff811a0ad0-ffffffff811a0cd1: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b2980)
Location: kernel/irq/irqdomain.c:1589
Inline: False
```
**Symbols:**

```
ffffffff811b2980-ffffffff811b2b6f: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c2770)
Location: kernel/irq/irqdomain.c:1589
Inline: False
```
**Symbols:**

```
ffffffff811c2770-ffffffff811c2990: irq_domain_push_irq (STB_GLOBAL)
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
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010183b40)
Location: kernel/irq/irqdomain.c:1402
Inline: False
```
**Symbols:**

```
ffff800010183b40-ffff800010183cd8: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d2da8)
Location: kernel/irq/irqdomain.c:1402
Inline: False
```
**Symbols:**

```
c03d2da8-c03d2f50: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011ad56)
Location: kernel/irq/irqdomain.c:1402
Inline: False
```
**Symbols:**

```
ffffffe00011ad56-ffffffe00011aede: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81116950)
Location: kernel/irq/irqdomain.c:1402
Inline: False
```
**Symbols:**

```
ffffffff81116950-ffffffff81116b36: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107640)
Location: kernel/irq/irqdomain.c:1402
Inline: False
```
**Symbols:**

```
ffffffff81107640-ffffffff81107826: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114840)
Location: kernel/irq/irqdomain.c:1402
Inline: False
```
**Symbols:**

```
ffffffff81114840-ffffffff81114a26: irq_domain_push_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_domain_push_irq(struct irq_domain *domain, int virq, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111fe70)
Location: kernel/irq/irqdomain.c:1402
Inline: False
```
**Symbols:**

```
ffffffff8111fe70-ffffffff81120056: irq_domain_push_irq (STB_GLOBAL)
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
