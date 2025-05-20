# Function: <code>probe_wakeup_sched_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff81157590)
Location: kernel/trace/trace_sched_wakeup.c:427
Inline: True
```
**Symbols:**

```
ffffffff81157590-ffffffff811577f2: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161e10)
Location: kernel/trace/trace_sched_wakeup.c:427
Inline: True
```
**Symbols:**

```
ffffffff81161e10-ffffffff8116206d: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c970)
Location: kernel/trace/trace_sched_wakeup.c:439
Inline: True
```
**Symbols:**

```
ffffffff8116c970-ffffffff8116cbcc: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff81170170)
Location: kernel/trace/trace_sched_wakeup.c:439
Inline: True
```
**Symbols:**

```
ffffffff81170170-ffffffff811703da: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117d2f0)
Location: kernel/trace/trace_sched_wakeup.c:440
Inline: True
```
**Symbols:**

```
ffffffff8117d2f0-ffffffff8117d5b6: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bed0)
Location: kernel/trace/trace_sched_wakeup.c:440
Inline: True
```
**Symbols:**

```
ffffffff8118bed0-ffffffff8118c191: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199d00)
Location: kernel/trace/trace_sched_wakeup.c:428
Inline: True
```
**Symbols:**

```
ffffffff81199d00-ffffffff81199fbf: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a7940)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffffffff811a7940-ffffffff811a7c1a: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b3130)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffffffff811b3130-ffffffff811b340a: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb840)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffffffff811cba10-ffffffff811cba50: probe_wakeup_sched_switch (STB_LOCAL)
ffffffff811cb840-ffffffff811cba06: probe_wakeup_sched_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8f20)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffffffff811c90f0-ffffffff811c9130: probe_wakeup_sched_switch (STB_LOCAL)
ffffffff811c8f20-ffffffff811c90e6: probe_wakeup_sched_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ca310)
Location: kernel/trace/trace_sched_wakeup.c:428
Inline: True
```
**Symbols:**

```
ffffffff811ca5c0-ffffffff811ca600: probe_wakeup_sched_switch (STB_LOCAL)
ffffffff811ca310-ffffffff811ca5c0: probe_wakeup_sched_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5f70)
Location: kernel/trace/trace_sched_wakeup.c:428
Inline: True
```
**Symbols:**

```
ffffffff811f62b0-ffffffff811f62f0: probe_wakeup_sched_switch (STB_LOCAL)
ffffffff811f5f70-ffffffff811f62a7: probe_wakeup_sched_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next, unsigned int prev_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f9e0)
Location: kernel/trace/trace_sched_wakeup.c:428
Inline: True
```
**Symbols:**

```
ffffffff8122fd40-ffffffff8122fd99: probe_wakeup_sched_switch (STB_LOCAL)
ffffffff8122f9e0-ffffffff8122fd40: probe_wakeup_sched_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next, unsigned int prev_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127bb80)
Location: kernel/trace/trace_sched_wakeup.c:428
Inline: True
```
**Symbols:**

```
ffffffff8127bf00-ffffffff8127bf59: probe_wakeup_sched_switch (STB_LOCAL)
ffffffff8127bb80-ffffffff8127bee6: probe_wakeup_sched_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next, unsigned int prev_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff812936a0)
Location: kernel/trace/trace_sched_wakeup.c:430
Inline: True
```
**Symbols:**

```
ffffffff81293a20-ffffffff81293a79: probe_wakeup_sched_switch (STB_LOCAL)
ffffffff812936a0-ffffffff81293a06: probe_wakeup_sched_switch.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next, unsigned int prev_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff812aecf0)
Location: kernel/trace/trace_sched_wakeup.c:430
Inline: True
```
**Symbols:**

```
ffffffff812af080-ffffffff812af0d9: probe_wakeup_sched_switch (STB_LOCAL)
ffffffff812aecf0-ffffffff812af06d: probe_wakeup_sched_switch.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffff800010230f18)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffff800010230f18-ffff8000102312c8: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (c046cf24)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
c046cf24-c046d2f4: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (c0000000002bb870)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
c0000000002bb870-c0000000002bbcd0: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffe000188ce6)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffffffe000188ce6-ffffffe000188fdc: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab750)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffffffff811ab750-ffffffff811aba2a: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e650)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffffffff8119e650-ffffffff8119e914: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a9520)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffffffff811a9520-ffffffff811a97fa: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void probe_wakeup_sched_switch(void *ignore, bool preempt, struct task_struct *prev, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b7360)
Location: kernel/trace/trace_sched_wakeup.c:431
Inline: True
```
**Symbols:**

```
ffffffff811b7360-ffffffff811b763a: probe_wakeup_sched_switch (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
