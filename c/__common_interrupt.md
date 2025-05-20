# Function: <code>__common_interrupt</code>

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
In <code>5.3</code>: Absent ⚠️
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
In arch/x86/kernel/irq.c (ffffffff81bbd9b3)
Location: arch/x86/kernel/irq.c:239
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
In arch/x86/kernel/irq.c (ffffffff81c36124)
Location: arch/x86/kernel/irq.c:239
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:common_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __common_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:common_interrupt
```
**Symbols:**

```
ffffffff81038430-ffffffff810384cb: __common_interrupt (STB_LOCAL)
ffffffff81bc57b6-ffffffff81bc57d7: __common_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __common_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:common_interrupt
```
**Symbols:**

```
ffffffff8103d500-ffffffff8103d5d7: __common_interrupt (STB_LOCAL)
ffffffff81c9837b-ffffffff81c9839d: __common_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __common_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:common_interrupt
```
**Symbols:**

```
ffffffff810450e0-ffffffff810451c9: __common_interrupt (STB_LOCAL)
ffffffff81e47881-ffffffff81e478a2: __common_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __common_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104ef90)
Location: arch/x86/kernel/irq.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:common_interrupt
```
**Symbols:**

```
ffffffff8104ef90-ffffffff8104f095: __common_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __common_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104f940)
Location: arch/x86/kernel/irq.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:common_interrupt
```
**Symbols:**

```
ffffffff8104f940-ffffffff8104fa45: __common_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __common_interrupt(struct pt_regs *regs, u32 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81056bb0)
Location: arch/x86/kernel/irq.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:common_interrupt
```
**Symbols:**

```
ffffffff81056bb0-ffffffff81056c9a: __common_interrupt (STB_LOCAL)
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
