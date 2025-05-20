# Function: <code>__bpf_trace_sched_switch</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba270)
Location: include/trace/events/sched.h:128
Inline: False
```
**Symbols:**

```
ffffffff810ba270-ffffffff810ba27f: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3370)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
ffffffff810c3370-ffffffff810c337f: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c9460)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
ffffffff810c9460-ffffffff810c946f: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2530)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
ffffffff810d2530-ffffffff810d253f: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc440)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
ffffffff810dc440-ffffffff810dc44f: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8c90)
Location: include/trace/events/sched.h:222
Inline: False
```
**Symbols:**

```
ffffffff810d8c90-ffffffff810d8c9f: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da610)
Location: include/trace/events/sched.h:222
Inline: False
```
**Symbols:**

```
ffffffff810da610-ffffffff810da61f: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810edff0)
Location: include/trace/events/sched.h:220
Inline: False
```
**Symbols:**

```
ffffffff810edff0-ffffffff810edfff: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next, unsigned int prev_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110a710)
Location: include/trace/events/sched.h:222
Inline: False
```
**Symbols:**

```
ffffffff8110a710-ffffffff8110a731: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next, unsigned int prev_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112f470)
Location: include/trace/events/sched.h:222
Inline: False
```
**Symbols:**

```
ffffffff8112f470-ffffffff8112f491: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next, unsigned int prev_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113cd40)
Location: include/trace/events/sched.h:222
Inline: False
```
**Symbols:**

```
ffffffff8113cd40-ffffffff8113cd61: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next, unsigned int prev_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81147e80)
Location: include/trace/events/sched.h:222
Inline: False
```
**Symbols:**

```
ffffffff81147e80-ffffffff81147ea1: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010132a20)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
ffff800010132a20-ffff800010132a38: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0382080)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
c0382080-c03820b8: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017d000)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
c00000000017d000-c00000000017d02c: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
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
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc8b0)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
ffffffff810cc8b0-ffffffff810cc8bf: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb0b0)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
ffffffff810bb0b0-ffffffff810bb0bf: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbdd0)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
ffffffff810cbdd0-ffffffff810cbddf: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_sched_switch(void *__data, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4330)
Location: include/trace/events/sched.h:138
Inline: False
```
**Symbols:**

```
ffffffff810d4330-ffffffff810d433f: __bpf_trace_sched_switch (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int prev_state</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
