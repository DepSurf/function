# Function: <code>trace_raw_output_vector_alloc</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102ed90)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff8102ed90-ffffffff8102edeb: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102fdc0)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff8102fdc0-ffffffff8102fe1b: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81031050)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff81031050-ffffffff810310ab: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81032da0)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff81032da0-ffffffff81032dfa: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81033660)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff81033660-ffffffff810336ba: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810354b0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff810354b0-ffffffff8103550a: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810366c0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff810366c0-ffffffff8103671a: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810380d0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff810380d0-ffffffff81038128: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff8103d610-ffffffff8103d679: trace_raw_output_vector_alloc (STB_LOCAL)
ffffffff81c9839d-ffffffff81c983c3: trace_raw_output_vector_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff810451d0-ffffffff8104524b: trace_raw_output_vector_alloc (STB_LOCAL)
ffffffff81e478a2-ffffffff81e478c8: trace_raw_output_vector_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff8104f0b0-ffffffff8104f12b: trace_raw_output_vector_alloc (STB_LOCAL)
ffffffff82051fb0-ffffffff82051fd6: trace_raw_output_vector_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff8104fa60-ffffffff8104fadb: trace_raw_output_vector_alloc (STB_LOCAL)
ffffffff820d04db-ffffffff820d0501: trace_raw_output_vector_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:219
Inline: False
```
**Symbols:**

```
ffffffff81056cb0-ffffffff81056d2b: trace_raw_output_vector_alloc (STB_LOCAL)
ffffffff821aaff0-ffffffff821ab016: trace_raw_output_vector_alloc.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810337c0)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff810337c0-ffffffff8103381a: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81023100)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff81023100-ffffffff8102315a: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81033620)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff81033620-ffffffff8103367a: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81034580)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff81034580-ffffffff810345da: trace_raw_output_vector_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
