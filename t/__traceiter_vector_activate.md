# Function: <code>__traceiter_vector_activate</code>

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
int __traceiter_vector_activate(void *__data, unsigned int irq, bool is_managed, bool can_reserve, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81035890)
Location: arch/x86/include/asm/trace/irq_vectors.h:300
Inline: False
```
**Symbols:**

```
ffffffff81035890-ffffffff810358ee: __traceiter_vector_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_vector_activate(void *__data, unsigned int irq, bool is_managed, bool can_reserve, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810372c0)
Location: arch/x86/include/asm/trace/irq_vectors.h:300
Inline: False
```
**Symbols:**

```
ffffffff810372c0-ffffffff8103731c: __traceiter_vector_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_vector_activate(void *__data, unsigned int irq, bool is_managed, bool can_reserve, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8103c590)
Location: arch/x86/include/asm/trace/irq_vectors.h:300
Inline: False
```
**Symbols:**

```
ffffffff8103c590-ffffffff8103c5ec: __traceiter_vector_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_vector_activate(void *__data, unsigned int irq, bool is_managed, bool can_reserve, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810437f0)
Location: arch/x86/include/asm/trace/irq_vectors.h:300
Inline: False
```
**Symbols:**

```
ffffffff810437f0-ffffffff8104385b: __traceiter_vector_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_vector_activate(void *__data, unsigned int irq, bool is_managed, bool can_reserve, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104d430)
Location: arch/x86/include/asm/trace/irq_vectors.h:300
Inline: False
```
**Symbols:**

```
ffffffff8104d430-ffffffff8104d49b: __traceiter_vector_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_vector_activate(void *__data, unsigned int irq, bool is_managed, bool can_reserve, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104dd60)
Location: arch/x86/include/asm/trace/irq_vectors.h:300
Inline: False
```
**Symbols:**

```
ffffffff8104dd60-ffffffff8104ddcb: __traceiter_vector_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_vector_activate(void *__data, unsigned int irq, bool is_managed, bool can_reserve, bool reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81054fe0)
Location: arch/x86/include/asm/trace/irq_vectors.h:300
Inline: False
```
**Symbols:**

```
ffffffff81054fe0-ffffffff8105504b: __traceiter_vector_activate (STB_GLOBAL)
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
