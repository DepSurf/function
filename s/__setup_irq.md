# Function: <code>__setup_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dc660)
Location: kernel/irq/manage.c:1110
Inline: False
Direct callers:
  - kernel/irq/manage.c:setup_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
```
**Symbols:**

```
ffffffff810dc660-ffffffff810dcc76: __setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e1d70)
Location: kernel/irq/manage.c:1124
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810e1d70-ffffffff810e2384: __setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e8680)
Location: kernel/irq/manage.c:1124
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810e8680-ffffffff810e8caf: __setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7ba0)
Location: kernel/irq/manage.c:1111
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810e7ba0-ffffffff810e8242: __setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810eff20)
Location: kernel/irq/manage.c:1139
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810eff20-ffffffff810f0619: __setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1183
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810f8360-ffffffff810f89e0: __setup_irq (STB_LOCAL)
ffffffff810f8efe-ffffffff810f8f94: __setup_irq.cold.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1194
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81103b00-ffffffff81104180: __setup_irq (STB_LOCAL)
ffffffff811046aa-ffffffff81104740: __setup_irq.cold.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1294
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff8110c550-ffffffff8110cc66: __setup_irq (STB_LOCAL)
ffffffff8110d79a-ffffffff8110d882: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1286
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81118930-ffffffff81119046: __setup_irq (STB_LOCAL)
ffffffff81119b1c-ffffffff81119c04: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1369
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81124220-ffffffff81124977: __setup_irq (STB_LOCAL)
ffffffff81125a46-ffffffff81125b32: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1439
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81120080-ffffffff811207d5: __setup_irq (STB_LOCAL)
ffffffff81be177e-ffffffff81be186a: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1439
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81120340-ffffffff81120a8a: __setup_irq (STB_LOCAL)
ffffffff81bd3839-ffffffff81bd3925: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1463
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81140870-ffffffff81141007: __setup_irq (STB_LOCAL)
ffffffff81cad6d7-ffffffff81cad86d: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1505
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81164260-ffffffff811649c7: __setup_irq (STB_LOCAL)
ffffffff81e5dbf5-ffffffff81e5dd3e: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1497
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81198020-ffffffff811987b3: __setup_irq (STB_LOCAL)
ffffffff8205996b-ffffffff820599dc: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1503
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff811a9d00-ffffffff811aa48d: __setup_irq (STB_LOCAL)
ffffffff820d808e-ffffffff820d80ff: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1505
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff811b9860-ffffffff811b9fa3: __setup_irq (STB_LOCAL)
ffffffff821b330f-ffffffff821b3380: __setup_irq.cold (STB_LOCAL)
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
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017b2d0)
Location: kernel/irq/manage.c:1286
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffff80001017b2d0-ffff80001017baf0: __setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cc3f4)
Location: kernel/irq/manage.c:1286
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
c03cc3f4-c03ccbf0: __setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d5970)
Location: kernel/irq/manage.c:1286
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
c0000000001d5970-c0000000001d6434: __setup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000114e6c)
Location: kernel/irq/manage.c:1286
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffe000114e6c-ffffffe000115450: __setup_irq (STB_LOCAL)
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
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1286
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81110f10-ffffffff81111626: __setup_irq (STB_LOCAL)
ffffffff811120fc-ffffffff811121e4: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1286
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81101c40-ffffffff81102356: __setup_irq (STB_LOCAL)
ffffffff81102e2c-ffffffff81102f14: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1286
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff8110ee00-ffffffff8110f516: __setup_irq (STB_LOCAL)
ffffffff8110ffec-ffffffff811100d4: __setup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc *desc, struct irqaction *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1286
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff8111a330-ffffffff8111aa46: __setup_irq (STB_LOCAL)
ffffffff8111b55c-ffffffff8111b644: __setup_irq.cold (STB_LOCAL)
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
