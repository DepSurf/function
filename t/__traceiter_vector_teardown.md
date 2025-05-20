# Function: <code>__traceiter_vector_teardown</code>

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
int __traceiter_vector_teardown(void *__data, unsigned int irq, bool is_managed, bool has_reserved);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81035950)
Location: arch/x86/include/asm/trace/irq_vectors.h:303
Inline: False
```
**Symbols:**

```
ffffffff81035950-ffffffff810359a3: __traceiter_vector_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_vector_teardown(void *__data, unsigned int irq, bool is_managed, bool has_reserved);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81037380)
Location: arch/x86/include/asm/trace/irq_vectors.h:303
Inline: False
```
**Symbols:**

```
ffffffff81037380-ffffffff810373d1: __traceiter_vector_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_vector_teardown(void *__data, unsigned int irq, bool is_managed, bool has_reserved);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8103c650)
Location: arch/x86/include/asm/trace/irq_vectors.h:303
Inline: False
```
**Symbols:**

```
ffffffff8103c650-ffffffff8103c6a1: __traceiter_vector_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_vector_teardown(void *__data, unsigned int irq, bool is_managed, bool has_reserved);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810438d0)
Location: arch/x86/include/asm/trace/irq_vectors.h:303
Inline: False
```
**Symbols:**

```
ffffffff810438d0-ffffffff8104392d: __traceiter_vector_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_vector_teardown(void *__data, unsigned int irq, bool is_managed, bool has_reserved);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104d530)
Location: arch/x86/include/asm/trace/irq_vectors.h:303
Inline: False
```
**Symbols:**

```
ffffffff8104d530-ffffffff8104d58d: __traceiter_vector_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_vector_teardown(void *__data, unsigned int irq, bool is_managed, bool has_reserved);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104de80)
Location: arch/x86/include/asm/trace/irq_vectors.h:303
Inline: False
```
**Symbols:**

```
ffffffff8104de80-ffffffff8104dedd: __traceiter_vector_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_vector_teardown(void *__data, unsigned int irq, bool is_managed, bool has_reserved);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81055100)
Location: arch/x86/include/asm/trace/irq_vectors.h:303
Inline: False
```
**Symbols:**

```
ffffffff81055100-ffffffff8105515d: __traceiter_vector_teardown (STB_GLOBAL)
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
