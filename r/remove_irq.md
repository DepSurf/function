# Function: <code>remove_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810db900)
Location: kernel/irq/manage.c:1529
Inline: False
```
**Symbols:**

```
ffffffff810db900-ffffffff810db948: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e1210)
Location: kernel/irq/manage.c:1559
Inline: False
```
**Symbols:**

```
ffffffff810e1210-ffffffff810e1258: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7b80)
Location: kernel/irq/manage.c:1559
Inline: False
```
**Symbols:**

```
ffffffff810e7b80-ffffffff810e7bc5: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7000)
Location: kernel/irq/manage.c:1602
Inline: False
```
**Symbols:**

```
ffffffff810e7000-ffffffff810e7036: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ef2e0)
Location: kernel/irq/manage.c:1655
Inline: False
```
**Symbols:**

```
ffffffff810ef2e0-ffffffff810ef316: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f7480)
Location: kernel/irq/manage.c:1699
Inline: False
```
**Symbols:**

```
ffffffff810f7480-ffffffff810f74b0: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102e40)
Location: kernel/irq/manage.c:1715
Inline: False
```
**Symbols:**

```
ffffffff81102e40-ffffffff81102e70: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1836
Inline: False
```
**Symbols:**

```
ffffffff8110d70a-ffffffff8110d71d: remove_irq.cold (STB_LOCAL)
ffffffff8110bbb0-ffffffff8110bbe0: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81117fb0)
Location: kernel/irq/manage.c:1828
Inline: False
```
**Symbols:**

```
ffffffff81117fb0-ffffffff81117fe0: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017a768)
Location: kernel/irq/manage.c:1828
Inline: False
```
**Symbols:**

```
ffff80001017a768-ffff80001017a7b4: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cba40)
Location: kernel/irq/manage.c:1828
Inline: False
Direct callers:
  - arch/arm/plat-omap/dma.c:omap_system_dma_remove
```
**Symbols:**

```
c03cba40-c03cba98: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d4b70)
Location: kernel/irq/manage.c:1828
Inline: False
```
**Symbols:**

```
c0000000001d4b70-c0000000001d4bf4: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe00011400a)
Location: kernel/irq/manage.c:1828
Inline: False
```
**Symbols:**

```
ffffffe00011400a-ffffffe000114056: remove_irq (STB_GLOBAL)
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
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81110590)
Location: kernel/irq/manage.c:1828
Inline: False
```
**Symbols:**

```
ffffffff81110590-ffffffff811105c0: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811012c0)
Location: kernel/irq/manage.c:1828
Inline: False
```
**Symbols:**

```
ffffffff811012c0-ffffffff811012f0: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110e480)
Location: kernel/irq/manage.c:1828
Inline: False
```
**Symbols:**

```
ffffffff8110e480-ffffffff8110e4b0: remove_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_irq(unsigned int irq, struct irqaction *act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811199b0)
Location: kernel/irq/manage.c:1828
Inline: False
```
**Symbols:**

```
ffffffff811199b0-ffffffff811199e0: remove_irq (STB_GLOBAL)
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
