# Function: <code>irq_init_percpu_irqstack</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81034500)
Location: arch/x86/kernel/irq_64.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81034500-ffffffff810345ff: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81034d90)
Location: arch/x86/kernel/irq_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81034d90-ffffffff81034e8f: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81036c70)
Location: arch/x86/kernel/irq_64.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81036c70-ffffffff81036c9f: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81037e40)
Location: arch/x86/kernel/irq_64.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81037e40-ffffffff81037e6f: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81039900)
Location: arch/x86/kernel/irq_64.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81039900-ffffffff810399ff: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff8103f1e0)
Location: arch/x86/kernel/irq_64.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff8103f1e0-ffffffff8103f358: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81046800)
Location: arch/x86/kernel/irq_64.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81046800-ffffffff810469a4: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81050870)
Location: arch/x86/kernel/irq_64.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81050870-ffffffff81050a14: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff810515a0)
Location: arch/x86/kernel/irq_64.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:native_kick_ap
```
**Symbols:**

```
ffffffff810515a0-ffffffff81051744: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff810587c0)
Location: arch/x86/kernel/irq_64.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:native_kick_ap
```
**Symbols:**

```
ffffffff810587c0-ffffffff81058964: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81034ef0)
Location: arch/x86/kernel/irq_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81034ef0-ffffffff81034fef: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81024830)
Location: arch/x86/kernel/irq_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81024830-ffffffff8102492f: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81034d50)
Location: arch/x86/kernel/irq_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81034d50-ffffffff81034e4f: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_init_percpu_irqstack(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81035c90)
Location: arch/x86/kernel/irq_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/irqinit.c:init_IRQ
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81035c90-ffffffff81035d8f: irq_init_percpu_irqstack (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
