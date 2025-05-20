# Function: <code>__free_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irqaction *__free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810db680)
Location: kernel/irq/manage.c:1432
Inline: False
Direct callers:
  - kernel/irq/manage.c:remove_irq
  - kernel/irq/manage.c:free_irq
```
**Symbols:**

```
ffffffff810db680-ffffffff810db8f8: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irqaction *__free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e0f80)
Location: kernel/irq/manage.c:1461
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff810e0f80-ffffffff810e1205: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irqaction *__free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7900)
Location: kernel/irq/manage.c:1461
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff810e7900-ffffffff810e7b76: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irqaction *__free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6d70)
Location: kernel/irq/manage.c:1475
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff810e6d70-ffffffff810e6ff1: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irqaction *__free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ef040)
Location: kernel/irq/manage.c:1528
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff810ef040-ffffffff810ef2dd: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f71d0)
Location: kernel/irq/manage.c:1572
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff810f71d0-ffffffff810f7477: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102ba0)
Location: kernel/irq/manage.c:1585
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff81102ba0-ffffffff81102e37: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110b8e0)
Location: kernel/irq/manage.c:1693
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff8110b8e0-ffffffff8110bbab: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81117ce0)
Location: kernel/irq/manage.c:1685
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff81117ce0-ffffffff81117fab: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81125590)
Location: kernel/irq/manage.c:1740
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
```
**Symbols:**

```
ffffffff81125590-ffffffff8112589d: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811213f0)
Location: kernel/irq/manage.c:1810
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
```
**Symbols:**

```
ffffffff811213f0-ffffffff811216fd: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811216d0)
Location: kernel/irq/manage.c:1811
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
```
**Symbols:**

```
ffffffff811216d0-ffffffff811219da: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81141c70)
Location: kernel/irq/manage.c:1840
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
```
**Symbols:**

```
ffffffff81141c70-ffffffff81141f7a: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81165790)
Location: kernel/irq/manage.c:1874
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
```
**Symbols:**

```
ffffffff81165790-ffffffff81165a87: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811996e0)
Location: kernel/irq/manage.c:1866
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
```
**Symbols:**

```
ffffffff811996e0-ffffffff811999d7: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ab3c0)
Location: kernel/irq/manage.c:1872
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
```
**Symbols:**

```
ffffffff811ab3c0-ffffffff811ab6bb: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811bafe0)
Location: kernel/irq/manage.c:1872
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
```
**Symbols:**

```
ffffffff811bafe0-ffffffff811bb254: __free_irq (STB_LOCAL)
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
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017a3f8)
Location: kernel/irq/manage.c:1685
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffff80001017a3f8-ffff80001017a764: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cb72c)
Location: kernel/irq/manage.c:1685
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
c03cb72c-c03cba40: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d4760)
Location: kernel/irq/manage.c:1685
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
c0000000001d4760-c0000000001d4b64: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000113dbe)
Location: kernel/irq/manage.c:1685
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffe000113dbe-ffffffe00011400a: __free_irq (STB_LOCAL)
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
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811102c0)
Location: kernel/irq/manage.c:1685
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff811102c0-ffffffff8111058b: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81100ff0)
Location: kernel/irq/manage.c:1685
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff81100ff0-ffffffff811012bb: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110e1b0)
Location: kernel/irq/manage.c:1685
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff8110e1b0-ffffffff8110e47b: __free_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irqaction *__free_irq(struct irq_desc *desc, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811196e0)
Location: kernel/irq/manage.c:1685
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_irq
  - kernel/irq/manage.c:remove_irq
```
**Symbols:**

```
ffffffff811196e0-ffffffff811199ab: __free_irq (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_desc *desc</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int irq</code>
</li>
</ul>
</details>
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
