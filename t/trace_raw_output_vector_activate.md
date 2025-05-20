# Function: <code>trace_raw_output_vector_activate</code>

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
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102ee50)
Location: arch/x86/include/asm/trace/irq_vectors.h:283
Inline: False
```
**Symbols:**

```
ffffffff8102ee50-ffffffff8102eead: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102fe80)
Location: arch/x86/include/asm/trace/irq_vectors.h:283
Inline: False
```
**Symbols:**

```
ffffffff8102fe80-ffffffff8102fedd: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81031110)
Location: arch/x86/include/asm/trace/irq_vectors.h:283
Inline: False
```
**Symbols:**

```
ffffffff81031110-ffffffff8103116d: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81032e60)
Location: arch/x86/include/asm/trace/irq_vectors.h:283
Inline: False
```
**Symbols:**

```
ffffffff81032e60-ffffffff81032ebc: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81033720)
Location: arch/x86/include/asm/trace/irq_vectors.h:283
Inline: False
```
**Symbols:**

```
ffffffff81033720-ffffffff8103377c: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81035570)
Location: arch/x86/include/asm/trace/irq_vectors.h:268
Inline: False
```
**Symbols:**

```
ffffffff81035570-ffffffff810355cc: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81036780)
Location: arch/x86/include/asm/trace/irq_vectors.h:268
Inline: False
```
**Symbols:**

```
ffffffff81036780-ffffffff810367dc: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81038190)
Location: arch/x86/include/asm/trace/irq_vectors.h:268
Inline: False
```
**Symbols:**

```
ffffffff81038190-ffffffff810381ea: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:268
Inline: False
```
**Symbols:**

```
ffffffff8103d680-ffffffff8103d705: trace_raw_output_vector_activate (STB_LOCAL)
ffffffff81c983c3-ffffffff81c98432: trace_raw_output_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:268
Inline: False
```
**Symbols:**

```
ffffffff81045250-ffffffff810452e7: trace_raw_output_vector_activate (STB_LOCAL)
ffffffff81e478c8-ffffffff81e47937: trace_raw_output_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:268
Inline: False
```
**Symbols:**

```
ffffffff8104f140-ffffffff8104f1d7: trace_raw_output_vector_activate (STB_LOCAL)
ffffffff82051fd6-ffffffff82052045: trace_raw_output_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:268
Inline: False
```
**Symbols:**

```
ffffffff8104faf0-ffffffff8104fb87: trace_raw_output_vector_activate (STB_LOCAL)
ffffffff820d0501-ffffffff820d0570: trace_raw_output_vector_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/include/asm/trace/irq_vectors.h:268
Inline: False
```
**Symbols:**

```
ffffffff81056d40-ffffffff81056dd7: trace_raw_output_vector_activate (STB_LOCAL)
ffffffff821ab016-ffffffff821ab085: trace_raw_output_vector_activate.cold (STB_LOCAL)
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
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81033880)
Location: arch/x86/include/asm/trace/irq_vectors.h:283
Inline: False
```
**Symbols:**

```
ffffffff81033880-ffffffff810338dc: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810231c0)
Location: arch/x86/include/asm/trace/irq_vectors.h:283
Inline: False
```
**Symbols:**

```
ffffffff810231c0-ffffffff8102321c: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810336e0)
Location: arch/x86/include/asm/trace/irq_vectors.h:283
Inline: False
```
**Symbols:**

```
ffffffff810336e0-ffffffff8103373c: trace_raw_output_vector_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_vector_activate(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81034640)
Location: arch/x86/include/asm/trace/irq_vectors.h:283
Inline: False
```
**Symbols:**

```
ffffffff81034640-ffffffff8103469c: trace_raw_output_vector_activate (STB_LOCAL)
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
