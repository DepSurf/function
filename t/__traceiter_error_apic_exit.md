# Function: <code>__traceiter_error_apic_exit</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_error_apic_exit(void *__data, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810351b0)
Location: arch/x86/include/asm/trace/irq_vectors.h:51
Inline: False
```
**Symbols:**

```
ffffffff810351b0-ffffffff810351ed: __traceiter_error_apic_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_error_apic_exit(void *__data, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81036bf0)
Location: arch/x86/include/asm/trace/irq_vectors.h:51
Inline: False
```
**Symbols:**

```
ffffffff81036bf0-ffffffff81036c2b: __traceiter_error_apic_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_error_apic_exit(void *__data, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8103bec0)
Location: arch/x86/include/asm/trace/irq_vectors.h:51
Inline: False
```
**Symbols:**

```
ffffffff8103bec0-ffffffff8103befb: __traceiter_error_apic_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_error_apic_exit(void *__data, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81042fc0)
Location: arch/x86/include/asm/trace/irq_vectors.h:51
Inline: False
```
**Symbols:**

```
ffffffff81042fc0-ffffffff81043003: __traceiter_error_apic_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_error_apic_exit(void *__data, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104ca80)
Location: arch/x86/include/asm/trace/irq_vectors.h:51
Inline: False
```
**Symbols:**

```
ffffffff8104ca80-ffffffff8104cac3: __traceiter_error_apic_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_error_apic_exit(void *__data, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104d310)
Location: arch/x86/include/asm/trace/irq_vectors.h:51
Inline: False
```
**Symbols:**

```
ffffffff8104d310-ffffffff8104d353: __traceiter_error_apic_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_error_apic_exit(void *__data, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81054590)
Location: arch/x86/include/asm/trace/irq_vectors.h:51
Inline: False
```
**Symbols:**

```
ffffffff81054590-ffffffff810545d3: __traceiter_error_apic_exit (STB_GLOBAL)
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
