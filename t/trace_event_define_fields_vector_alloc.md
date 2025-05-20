# Function: <code>trace_event_define_fields_vector_alloc</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int trace_event_define_fields_vector_alloc(struct trace_event_call *event_call);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff826afc05)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: True
```
**Symbols:**

```
ffffffff826afc05-ffffffff826afcbf: trace_event_define_fields_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int trace_event_define_fields_vector_alloc(struct trace_event_call *event_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff826d930b)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff826d930b-ffffffff826d93c5: trace_event_define_fields_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int trace_event_define_fields_vector_alloc(struct trace_event_call *event_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8288f6ef)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff8288f6ef-ffffffff8288f7a9: trace_event_define_fields_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int trace_event_define_fields_vector_alloc(struct trace_event_call *event_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff828a6c14)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff828a6c14-ffffffff828a6ccf: trace_event_define_fields_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int trace_event_define_fields_vector_alloc(struct trace_event_call *event_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff828a9c43)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff828a9c43-ffffffff828a9cfe: trace_event_define_fields_vector_alloc (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int trace_event_define_fields_vector_alloc(struct trace_event_call *event_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff82897c53)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff82897c53-ffffffff82897d0e: trace_event_define_fields_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int trace_event_define_fields_vector_alloc(struct trace_event_call *event_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8288ff7d)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff8288ff7d-ffffffff82890038: trace_event_define_fields_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int trace_event_define_fields_vector_alloc(struct trace_event_call *event_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff828aac43)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff828aac43-ffffffff828aacfe: trace_event_define_fields_vector_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int trace_event_define_fields_vector_alloc(struct trace_event_call *event_call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff828aac53)
Location: arch/x86/include/asm/trace/irq_vectors.h:234
Inline: False
```
**Symbols:**

```
ffffffff828aac53-ffffffff828aad0e: trace_event_define_fields_vector_alloc (STB_LOCAL)
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
