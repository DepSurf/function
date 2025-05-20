# Function: <code>__traceiter_vector_alloc</code>

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
int __traceiter_vector_alloc(void *__data, unsigned int irq, unsigned int vector, bool reserved, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810357d0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff810357d0-ffffffff8103582c: __traceiter_vector_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_vector_alloc(void *__data, unsigned int irq, unsigned int vector, bool reserved, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81037210)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff81037210-ffffffff8103726a: __traceiter_vector_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_vector_alloc(void *__data, unsigned int irq, unsigned int vector, bool reserved, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8103c4e0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff8103c4e0-ffffffff8103c53a: __traceiter_vector_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_vector_alloc(void *__data, unsigned int irq, unsigned int vector, bool reserved, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81043720)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff81043720-ffffffff81043789: __traceiter_vector_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_vector_alloc(void *__data, unsigned int irq, unsigned int vector, bool reserved, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104d340)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff8104d340-ffffffff8104d3a9: __traceiter_vector_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_vector_alloc(void *__data, unsigned int irq, unsigned int vector, bool reserved, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104dc30)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff8104dc30-ffffffff8104dc99: __traceiter_vector_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_vector_alloc(void *__data, unsigned int irq, unsigned int vector, bool reserved, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81054eb0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff81054eb0-ffffffff81054f19: __traceiter_vector_alloc (STB_GLOBAL)
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
