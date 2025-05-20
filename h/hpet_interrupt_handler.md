# Function: <code>hpet_interrupt_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t hpet_interrupt_handler(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062ae0)
Location: arch/x86/kernel/hpet.c:523
Inline: True
```
**Symbols:**

```
ffffffff81062ae0-ffffffff81062b11: hpet_interrupt_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t hpet_interrupt_handler(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062780)
Location: arch/x86/kernel/hpet.c:523
Inline: True
```
**Symbols:**

```
ffffffff81062780-ffffffff810627b1: hpet_interrupt_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t hpet_interrupt_handler(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810657f0)
Location: arch/x86/kernel/hpet.c:524
Inline: True
```
**Symbols:**

```
ffffffff810657f0-ffffffff81065821: hpet_interrupt_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t hpet_interrupt_handler(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810648c0)
Location: arch/x86/kernel/hpet.c:519
Inline: True
```
**Symbols:**

```
ffffffff810648c0-ffffffff810648f1: hpet_interrupt_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t hpet_interrupt_handler(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81068a50)
Location: arch/x86/kernel/hpet.c:519
Inline: True
```
**Symbols:**

```
ffffffff81068a50-ffffffff81068a84: hpet_interrupt_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t hpet_interrupt_handler(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:520
Inline: True
```
**Symbols:**

```
ffffffff8106b530-ffffffff8106b554: hpet_interrupt_handler (STB_LOCAL)
ffffffff8106bde9-ffffffff8106be00: hpet_interrupt_handler.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t hpet_interrupt_handler(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81071b79)
Location: arch/x86/kernel/hpet.c:516
Inline: True
```
**Symbols:**

```
ffffffff810712c0-ffffffff810712e4: hpet_interrupt_handler (STB_LOCAL)
ffffffff81071b79-ffffffff81071b90: hpet_interrupt_handler.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
</ul>
