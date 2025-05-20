# Function: <code>handle_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool handle_irq(struct irq_desc *desc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81031140)
Location: arch/x86/kernel/irq_64.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
**Symbols:**

```
ffffffff81031140-ffffffff81031164: handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool handle_irq(struct irq_desc *desc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81030200)
Location: arch/x86/kernel/irq_64.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
**Symbols:**

```
ffffffff81030200-ffffffff81030224: handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool handle_irq(struct irq_desc *desc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff810301b0)
Location: arch/x86/kernel/irq_64.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
**Symbols:**

```
ffffffff810301b0-ffffffff810301d4: handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool handle_irq(struct irq_desc *desc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff8102e410)
Location: arch/x86/kernel/irq_64.c:69
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
**Symbols:**

```
ffffffff8102e410-ffffffff8102e434: handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool handle_irq(struct irq_desc *desc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81030290)
Location: arch/x86/kernel/irq_64.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
**Symbols:**

```
ffffffff81030290-ffffffff810302ba: handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool handle_irq(struct irq_desc *desc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff81031520)
Location: arch/x86/kernel/irq_64.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
**Symbols:**

```
ffffffff81031520-ffffffff8103154a: handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool handle_irq(struct irq_desc *desc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff810327c0)
Location: arch/x86/kernel/irq_64.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
**Symbols:**

```
ffffffff810327c0-ffffffff810327ea: handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool handle_irq(struct irq_desc *desc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq_64.c (ffffffff810344d0)
Location: arch/x86/kernel/irq_64.c:29
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:do_IRQ
```
**Symbols:**

```
ffffffff810344d0-ffffffff810344fa: handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81bbd9d6)
Location: arch/x86/kernel/irq.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:common_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81c36134)
Location: arch/x86/kernel/irq.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:common_interrupt
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
In arch/x86/kernel/irq.c (ffffffff81038467)
Location: arch/x86/kernel/irq.c:227
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8103d546)
Location: arch/x86/kernel/irq.c:227
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
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
In arch/x86/kernel/irq.c (ffffffff81045129)
Location: arch/x86/kernel/irq.c:227
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8104efd9)
Location: arch/x86/kernel/irq.c:227
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8104f989)
Location: arch/x86/kernel/irq.c:234
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
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
In arch/x86/kernel/irq.c (ffffffff81056bf8)
Location: arch/x86/kernel/irq.c:234
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__common_interrupt
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
