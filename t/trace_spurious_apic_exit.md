# Function: <code>trace_spurious_apic_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810541fe)
Location: arch/x86/include/asm/trace/irq_vectors.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810543ae)
Location: arch/x86/include/asm/trace/irq_vectors.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810570a9)
Location: arch/x86/include/asm/trace/irq_vectors.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8190ea06)
Location: arch/x86/include/asm/trace/irq_vectors.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81a02eba)
Location: arch/x86/include/asm/trace/irq_vectors.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81a025f8)
Location: arch/x86/include/asm/trace/irq_vectors.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c026a8)
Location: arch/x86/include/asm/trace/irq_vectors.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c028ef)
Location: arch/x86/include/asm/trace/irq_vectors.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff81c0291f)
Location: arch/x86/include/asm/trace/irq_vectors.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_spurious_apic_exit(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106dfbc)
Location: arch/x86/include/asm/trace/irq_vectors.h:46
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
**Symbols:**

```
ffffffff8106dfbc-ffffffff8106e00f: trace_spurious_apic_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_spurious_apic_exit(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81bd6d33)
Location: arch/x86/include/asm/trace/irq_vectors.h:46
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
```
**Symbols:**

```
ffffffff81bd6d33-ffffffff81bd6d77: trace_spurious_apic_exit (STB_LOCAL)
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
In arch/x86/kernel/apic/apic.c (ffffffff81bc8ff0)
Location: arch/x86/include/asm/trace/irq_vectors.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff81c9da4d)
Location: arch/x86/include/asm/trace/irq_vectors.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff81e4ceac)
Location: arch/x86/include/asm/trace/irq_vectors.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff8109d71a)
Location: arch/x86/include/asm/trace/irq_vectors.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff810a06fa)
Location: arch/x86/include/asm/trace/irq_vectors.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff810a7c2f)
Location: arch/x86/include/asm/trace/irq_vectors.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff81c028ff)
Location: arch/x86/include/asm/trace/irq_vectors.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff81c027af)
Location: arch/x86/include/asm/trace/irq_vectors.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff81c0286f)
Location: arch/x86/include/asm/trace/irq_vectors.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
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
In arch/x86/kernel/apic/apic.c (ffffffff81c02aef)
Location: arch/x86/include/asm/trace/irq_vectors.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
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
