# Function: <code>__on_sig_stack</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81035670)
Location: include/linux/sched/signal.h:541
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810967aa)
Location: include/linux/sched/signal.h:541
Inline: True
```
```
In kernel/signal.c (ffffffff810bbe87)
Location: include/linux/sched/signal.h:541
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8103a950)
Location: include/linux/sched/signal.h:539
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a674a)
Location: include/linux/sched/signal.h:539
Inline: True
```
```
In kernel/signal.c (ffffffff810ce8e7)
Location: include/linux/sched/signal.h:539
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81041bbb)
Location: include/linux/sched/signal.h:579
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bb9eb)
Location: include/linux/sched/signal.h:579
Inline: True
```
```
In kernel/signal.c (ffffffff810de0c4)
Location: include/linux/sched/signal.h:579
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104b309)
Location: include/linux/sched/signal.h:580
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (ffffffff810fe544)
Location: include/linux/sched/signal.h:580
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104bba7)
Location: include/linux/sched/signal.h:580
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (ffffffff8110a5b4)
Location: include/linux/sched/signal.h:580
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81052e27)
Location: include/linux/sched/signal.h:571
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (ffffffff81113f54)
Location: include/linux/sched/signal.h:571
Inline: True
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
