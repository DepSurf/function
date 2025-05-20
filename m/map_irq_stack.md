# Function: <code>map_irq_stack</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81034568)
Location: arch/x86/kernel/irq_64.c:42
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81034df8)
Location: arch/x86/kernel/irq_64.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int map_irq_stack(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81036b90)
Location: arch/x86/kernel/irq_64.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
**Symbols:**

```
ffffffff81036b90-ffffffff81036c6b: map_irq_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int map_irq_stack(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81037d60)
Location: arch/x86/kernel/irq_64.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
**Symbols:**

```
ffffffff81037d60-ffffffff81037e3b: map_irq_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81039968)
Location: arch/x86/kernel/irq_64.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff8103f24d)
Location: arch/x86/kernel/irq_64.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81046879)
Location: arch/x86/kernel/irq_64.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff810508e9)
Location: arch/x86/kernel/irq_64.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81051619)
Location: arch/x86/kernel/irq_64.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81058839)
Location: arch/x86/kernel/irq_64.c:35
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81034f58)
Location: arch/x86/kernel/irq_64.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81024898)
Location: arch/x86/kernel/irq_64.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81034db8)
Location: arch/x86/kernel/irq_64.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81035cf8)
Location: arch/x86/kernel/irq_64.c:33
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
