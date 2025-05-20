# Function: <code>kstat_irqs_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810da4b0)
Location: kernel/irq/irqdesc.c:601
Inline: False
Direct callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810da4b0-ffffffff810da4ec: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810dfa60)
Location: kernel/irq/irqdesc.c:686
Inline: False
Direct callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810dfa60-ffffffff810dfa9c: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e6340)
Location: kernel/irq/irqdesc.c:874
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810e6340-ffffffff810e637c: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5990)
Location: kernel/irq/irqdesc.c:891
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810e5990-ffffffff810e59cf: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810edbf0)
Location: kernel/irq/irqdesc.c:881
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810edbf0-ffffffff810edc2f: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f6030)
Location: kernel/irq/irqdesc.c:898
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
```
**Symbols:**

```
ffffffff810f6030-ffffffff810f606f: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811017c0)
Location: kernel/irq/irqdesc.c:903
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffffffff811017c0-ffffffff811017ff: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81109fc0)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffffffff81109fc0-ffffffff81109ffe: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81116390)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffffffff81116390-ffffffff811163ce: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8112191d)
Location: kernel/irq/irqdesc.c:965
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffffffff81122040-ffffffff81122081: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111e0c0)
Location: kernel/irq/irqdesc.c:916
Inline: False
```
**Symbols:**

```
ffffffff8111e0c0-ffffffff8111e101: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111e360)
Location: kernel/irq/irqdesc.c:916
Inline: False
```
**Symbols:**

```
ffffffff8111e360-ffffffff8111e3a1: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113e7e0)
Location: kernel/irq/irqdesc.c:928
Inline: False
```
**Symbols:**

```
ffffffff8113e7e0-ffffffff8113e83c: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161da0)
Location: kernel/irq/irqdesc.c:905
Inline: False
```
**Symbols:**

```
ffffffff81161da0-ffffffff81161e04: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811955c0)
Location: kernel/irq/irqdesc.c:932
Inline: False
```
**Symbols:**

```
ffffffff811955c0-ffffffff81195624: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6f90)
Location: kernel/irq/irqdesc.c:951
Inline: False
```
**Symbols:**

```
ffffffff811a6f90-ffffffff811a6ff4: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b6af0)
Location: kernel/irq/irqdesc.c:951
Inline: False
```
**Symbols:**

```
ffffffff811b6af0-ffffffff811b6b54: kstat_irqs_cpu (STB_GLOBAL)
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
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010178028)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffff800010178028-ffff800010178094: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c9944)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
c03c9944-c03c9998: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d1ae0)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
c0000000001d1ae0-c0000000001d1b78: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe000112bee)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffffffe000112bee-ffffffe000112c54: kstat_irqs_cpu (STB_GLOBAL)
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
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110e970)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffffffff8110e970-ffffffff8110e9ae: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ff6c0)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffffffff810ff6c0-ffffffff810ff6fe: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110c860)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffffffff8110c860-ffffffff8110c89e: kstat_irqs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int kstat_irqs_cpu(unsigned int irq, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81117d70)
Location: kernel/irq/irqdesc.c:958
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:per_cpu_count_show
```
**Symbols:**

```
ffffffff81117d70-ffffffff81117dae: kstat_irqs_cpu (STB_GLOBAL)
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
