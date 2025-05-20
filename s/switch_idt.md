# Function: <code>switch_idt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void switch_idt(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tracepoint.c (ffffffff810663b0)
Location: arch/x86/kernel/tracepoint.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc
```
**Symbols:**

```
ffffffff810663b0-ffffffff8106641b: switch_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void switch_idt(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tracepoint.c (ffffffff81066140)
Location: arch/x86/kernel/tracepoint.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc
```
**Symbols:**

```
ffffffff81066140-ffffffff810661ab: switch_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void switch_idt(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tracepoint.c (ffffffff81069660)
Location: arch/x86/kernel/tracepoint.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc
```
**Symbols:**

```
ffffffff81069660-ffffffff810696cb: switch_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void switch_idt(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tracepoint.c (ffffffff810688d0)
Location: arch/x86/kernel/tracepoint.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc
  - arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc
```
**Symbols:**

```
ffffffff810688d0-ffffffff8106893b: switch_idt (STB_LOCAL)
```
</details>
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
</ul>
