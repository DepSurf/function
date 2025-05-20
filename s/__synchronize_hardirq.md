# Function: <code>__synchronize_hardirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810daa90)
Location: kernel/irq/manage.c:41
Inline: False
Direct callers:
  - kernel/irq/manage.c:synchronize_hardirq
  - kernel/irq/manage.c:synchronize_irq
```
**Symbols:**

```
ffffffff810daa90-ffffffff810daae6: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e00a0)
Location: kernel/irq/manage.c:41
Inline: False
Direct callers:
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff810e00a0-ffffffff810e00f6: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e69f0)
Location: kernel/irq/manage.c:41
Inline: False
Direct callers:
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff810e69f0-ffffffff810e6a46: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6040)
Location: kernel/irq/manage.c:43
Inline: False
Direct callers:
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff810e6040-ffffffff810e6096: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ee2c0)
Location: kernel/irq/manage.c:43
Inline: False
Direct callers:
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff810ee2c0-ffffffff810ee316: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f66b0)
Location: kernel/irq/manage.c:43
Inline: False
Direct callers:
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff810f66b0-ffffffff810f6706: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81101e20)
Location: kernel/irq/manage.c:43
Inline: False
Direct callers:
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff81101e20-ffffffff81101e76: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110a630)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff8110a630-ffffffff8110a6ff: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81116a00)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff81116a00-ffffffff81116acf: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811253c0)
Location: kernel/irq/manage.c:45
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:synchronize_irq
```
**Symbols:**

```
ffffffff811253c0-ffffffff8112546d: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121220)
Location: kernel/irq/manage.c:45
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:synchronize_irq
```
**Symbols:**

```
ffffffff81121220-ffffffff811212cd: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121500)
Location: kernel/irq/manage.c:45
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:synchronize_irq
```
**Symbols:**

```
ffffffff81121500-ffffffff811215ad: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:38
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:synchronize_irq
```
**Symbols:**

```
ffffffff81141a80-ffffffff81141b41: __synchronize_hardirq (STB_LOCAL)
ffffffff81cad887-ffffffff81cad89c: __synchronize_hardirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:38
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:synchronize_irq
```
**Symbols:**

```
ffffffff81165550-ffffffff8116561e: __synchronize_hardirq (STB_LOCAL)
ffffffff81e5dd58-ffffffff81e5dd6d: __synchronize_hardirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:38
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:synchronize_irq
```
**Symbols:**

```
ffffffff81199460-ffffffff8119952e: __synchronize_hardirq (STB_LOCAL)
ffffffff820599dc-ffffffff820599f1: __synchronize_hardirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:38
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:synchronize_irq
```
**Symbols:**

```
ffffffff811ab140-ffffffff811ab20e: __synchronize_hardirq (STB_LOCAL)
ffffffff820d80ff-ffffffff820d8114: __synchronize_hardirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:38
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
```
**Symbols:**

```
ffffffff811bad80-ffffffff811bae4e: __synchronize_hardirq (STB_LOCAL)
ffffffff821b3380-ffffffff821b3395: __synchronize_hardirq.cold (STB_LOCAL)
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
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff800010179490)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffff800010179490-ffff8000101795fc: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ca1ac)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
c03ca1ac-c03ca2d8: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d29a0)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
c0000000001d29a0-c0000000001d2ae4: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe0001133dc)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffe0001133dc-ffffffe000113480: __synchronize_hardirq (STB_LOCAL)
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
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110efe0)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff8110efe0-ffffffff8110f0af: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ffd20)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff810ffd20-ffffffff810ffdef: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110ced0)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff8110ced0-ffffffff8110cf9f: __synchronize_hardirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __synchronize_hardirq(struct irq_desc *desc, bool sync_chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118430)
Location: kernel/irq/manage.c:44
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_hardirq
```
**Symbols:**

```
ffffffff81118430-ffffffff811184ff: __synchronize_hardirq (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool sync_chip</code>
</li>
</ul>
</details>
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
