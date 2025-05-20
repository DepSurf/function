# Function: <code>__traceiter_vector_free_moved</code>

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
int __traceiter_vector_free_moved(void *__data, unsigned int irq, unsigned int cpu, unsigned int vector, bool is_managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81035a10)
Location: arch/x86/include/asm/trace/irq_vectors.h:347
Inline: False
```
**Symbols:**

```
ffffffff81035a10-ffffffff81035a6c: __traceiter_vector_free_moved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_vector_free_moved(void *__data, unsigned int irq, unsigned int cpu, unsigned int vector, bool is_managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81037430)
Location: arch/x86/include/asm/trace/irq_vectors.h:347
Inline: False
```
**Symbols:**

```
ffffffff81037430-ffffffff8103748a: __traceiter_vector_free_moved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_vector_free_moved(void *__data, unsigned int irq, unsigned int cpu, unsigned int vector, bool is_managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8103c700)
Location: arch/x86/include/asm/trace/irq_vectors.h:347
Inline: False
```
**Symbols:**

```
ffffffff8103c700-ffffffff8103c75a: __traceiter_vector_free_moved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_vector_free_moved(void *__data, unsigned int irq, unsigned int cpu, unsigned int vector, bool is_managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81043990)
Location: arch/x86/include/asm/trace/irq_vectors.h:347
Inline: False
```
**Symbols:**

```
ffffffff81043990-ffffffff810439f9: __traceiter_vector_free_moved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_vector_free_moved(void *__data, unsigned int irq, unsigned int cpu, unsigned int vector, bool is_managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104d610)
Location: arch/x86/include/asm/trace/irq_vectors.h:347
Inline: False
```
**Symbols:**

```
ffffffff8104d610-ffffffff8104d679: __traceiter_vector_free_moved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_vector_free_moved(void *__data, unsigned int irq, unsigned int cpu, unsigned int vector, bool is_managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104dfa0)
Location: arch/x86/include/asm/trace/irq_vectors.h:347
Inline: False
```
**Symbols:**

```
ffffffff8104dfa0-ffffffff8104e009: __traceiter_vector_free_moved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_vector_free_moved(void *__data, unsigned int irq, unsigned int cpu, unsigned int vector, bool is_managed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81055220)
Location: arch/x86/include/asm/trace/irq_vectors.h:347
Inline: False
```
**Symbols:**

```
ffffffff81055220-ffffffff81055289: __traceiter_vector_free_moved (STB_GLOBAL)
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
