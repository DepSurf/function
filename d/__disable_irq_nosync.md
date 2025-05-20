# Function: <code>__disable_irq_nosync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dae30)
Location: kernel/irq/manage.c:439
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq_nosync
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:disable_hardirq
```
**Symbols:**

```
ffffffff810dae30-ffffffff810daeb9: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e04c0)
Location: kernel/irq/manage.c:453
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:disable_irq_nosync
```
**Symbols:**

```
ffffffff810e04c0-ffffffff810e0549: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6e10)
Location: kernel/irq/manage.c:453
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:disable_irq_nosync
```
**Symbols:**

```
ffffffff810e6e10-ffffffff810e6e93: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6510)
Location: kernel/irq/manage.c:424
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:disable_irq_nosync
```
**Symbols:**

```
ffffffff810e6510-ffffffff810e6599: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ee7c0)
Location: kernel/irq/manage.c:452
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:disable_irq_nosync
```
**Symbols:**

```
ffffffff810ee7c0-ffffffff810ee849: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f6bb0)
Location: kernel/irq/manage.c:485
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:disable_irq_nosync
```
**Symbols:**

```
ffffffff810f6bb0-ffffffff810f6c3a: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102320)
Location: kernel/irq/manage.c:488
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:disable_irq_nosync
```
**Symbols:**

```
ffffffff81102320-ffffffff811023aa: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110ab00)
Location: kernel/irq/manage.c:517
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff8110ab00-ffffffff8110ab8e: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81116ed0)
Location: kernel/irq/manage.c:510
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff81116ed0-ffffffff81116f5e: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81122d50)
Location: kernel/irq/manage.c:586
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff81122d50-ffffffff81122ddc: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111ebe0)
Location: kernel/irq/manage.c:656
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff8111ebe0-ffffffff8111ec6c: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111ee60)
Location: kernel/irq/manage.c:656
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff8111ee60-ffffffff8111eeec: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8113f120)
Location: kernel/irq/manage.c:680
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff8113f120-ffffffff8113f1ac: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81162a50)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff81162a50-ffffffff81162aed: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811965f0)
Location: kernel/irq/manage.c:687
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff811965f0-ffffffff8119668d: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a7fb0)
Location: kernel/irq/manage.c:690
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff811a7fb0-ffffffff811a804d: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b7b10)
Location: kernel/irq/manage.c:692
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff811b7b10-ffffffff811b7bad: __disable_irq_nosync (STB_LOCAL)
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
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff800010178e50)
Location: kernel/irq/manage.c:510
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffff800010178e50-ffff800010178eec: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ca8ec)
Location: kernel/irq/manage.c:510
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
c03ca8ec-c03ca98c: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d3330)
Location: kernel/irq/manage.c:510
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
c0000000001d3330-c0000000001d33ec: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe00011394e)
Location: kernel/irq/manage.c:510
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffe00011394e-ffffffe0001139ae: __disable_irq_nosync (STB_LOCAL)
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
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f4b0)
Location: kernel/irq/manage.c:510
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff8110f4b0-ffffffff8110f53e: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811001f0)
Location: kernel/irq/manage.c:510
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff811001f0-ffffffff8110027e: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d3a0)
Location: kernel/irq/manage.c:510
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff8110d3a0-ffffffff8110d42e: __disable_irq_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __disable_irq_nosync(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118900)
Location: kernel/irq/manage.c:510
Inline: False
Direct callers:
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:disable_irq
```
**Symbols:**

```
ffffffff81118900-ffffffff8111898e: __disable_irq_nosync (STB_LOCAL)
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
