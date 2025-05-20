# Function: <code>t_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81140f60)
Location: kernel/trace/ftrace.c:3104
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
```
```
In kernel/trace/trace.c (ffffffff8114a840)
Location: kernel/trace/trace.c:3272
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff81156520)
Location: kernel/trace/trace_printk.c:287
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff81157d70)
Location: kernel/trace/trace_stack.c:297
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff8115d680)
Location: kernel/trace/trace_events.c:860
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff81282010)
Location: fs/proc/proc_tty.c:110
Inline: False
```
**Symbols:**

```
ffffffff81140f60-ffffffff81141098: t_next (STB_LOCAL)
ffffffff8114a840-ffffffff8114a885: t_next (STB_LOCAL)
ffffffff81156520-ffffffff811565e0: t_next (STB_LOCAL)
ffffffff81157d70-ffffffff81157da8: t_next (STB_LOCAL)
ffffffff8115d680-ffffffff8115d6c4: t_next (STB_LOCAL)
ffffffff81282010-ffffffff8128202a: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81149870)
Location: kernel/trace/ftrace.c:3124
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
```
```
In kernel/trace/trace.c (ffffffff811533ba)
Location: kernel/trace/trace.c:3609
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff8115f870)
Location: kernel/trace/trace_printk.c:292
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811625f0)
Location: kernel/trace/trace_stack.c:301
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811686a5)
Location: kernel/trace/trace_events.c:895
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff812af0c0)
Location: fs/proc/proc_tty.c:110
Inline: False
```
**Symbols:**

```
ffffffff81149870-ffffffff811499a8: t_next (STB_LOCAL)
ffffffff81153260-ffffffff811532a6: t_next (STB_LOCAL)
ffffffff8115f870-ffffffff8115f888: t_next (STB_LOCAL)
ffffffff811625f0-ffffffff81162628: t_next (STB_LOCAL)
ffffffff81167fd0-ffffffff81168014: t_next (STB_LOCAL)
ffffffff812af0c0-ffffffff812af0da: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81153710)
Location: kernel/trace/ftrace.c:3142
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
```
```
In kernel/trace/trace.c (ffffffff8115d484)
Location: kernel/trace/trace.c:3833
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff8116a2d0)
Location: kernel/trace/trace_printk.c:292
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8116d930)
Location: kernel/trace/trace_stack.c:301
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81173a52)
Location: kernel/trace/trace_events.c:864
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff812c4a90)
Location: fs/proc/proc_tty.c:110
Inline: False
```
**Symbols:**

```
ffffffff81153710-ffffffff81153845: t_next (STB_LOCAL)
ffffffff8115d330-ffffffff8115d373: t_next (STB_LOCAL)
ffffffff8116a2d0-ffffffff8116a2e8: t_next (STB_LOCAL)
ffffffff8116d930-ffffffff8116d962: t_next (STB_LOCAL)
ffffffff81173420-ffffffff81173461: t_next (STB_LOCAL)
ffffffff812c4a90-ffffffff812c4aaa: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81156d00)
Location: kernel/trace/ftrace.c:3390
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811604b7)
Location: kernel/trace/trace.c:4063
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff8116d280)
Location: kernel/trace/trace_printk.c:292
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff81170cb0)
Location: kernel/trace/trace_stack.c:307
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811766d1)
Location: kernel/trace/trace_events.c:904
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff812d1cb0)
Location: fs/proc/proc_tty.c:110
Inline: False
```
**Symbols:**

```
ffffffff81156d00-ffffffff81156dde: t_next (STB_LOCAL)
ffffffff81160360-ffffffff811603a1: t_next (STB_LOCAL)
ffffffff8116d280-ffffffff8116d298: t_next (STB_LOCAL)
ffffffff81170cb0-ffffffff81170ce2: t_next (STB_LOCAL)
ffffffff811761c0-ffffffff81176201: t_next (STB_LOCAL)
ffffffff812d1cb0-ffffffff812d1cca: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81163870)
Location: kernel/trace/ftrace.c:3358
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8116d577)
Location: kernel/trace/trace.c:4078
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff8117a330)
Location: kernel/trace/trace_printk.c:292
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8117de70)
Location: kernel/trace/trace_stack.c:297
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81183e91)
Location: kernel/trace/trace_events.c:904
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff812f64d0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff81163870-ffffffff8116394e: t_next (STB_LOCAL)
ffffffff8116d420-ffffffff8116d461: t_next (STB_LOCAL)
ffffffff8117a330-ffffffff8117a348: t_next (STB_LOCAL)
ffffffff8117de70-ffffffff8117dea2: t_next (STB_LOCAL)
ffffffff81183950-ffffffff81183991: t_next (STB_LOCAL)
ffffffff812f64d0-ffffffff812f64ea: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811726a0)
Location: kernel/trace/ftrace.c:3347
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8117c704)
Location: kernel/trace/trace.c:4084
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff81189510)
Location: kernel/trace/trace_printk.c:292
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8118cfd0)
Location: kernel/trace/trace_stack.c:297
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81192fd1)
Location: kernel/trace/trace_events.c:902
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff81323990)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff811726a0-ffffffff81172783: t_next (STB_LOCAL)
ffffffff8117c460-ffffffff8117c49b: t_next (STB_LOCAL)
ffffffff81189510-ffffffff81189528: t_next (STB_LOCAL)
ffffffff8118cfd0-ffffffff8118cffc: t_next (STB_LOCAL)
ffffffff81192ad0-ffffffff81192b0c: t_next (STB_LOCAL)
ffffffff81323990-ffffffff813239aa: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81180110)
Location: kernel/trace/ftrace.c:3306
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81189f04)
Location: kernel/trace/trace.c:4088
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff81196dc0)
Location: kernel/trace/trace_printk.c:293
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8119a950)
Location: kernel/trace/trace_stack.c:297
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811a1141)
Location: kernel/trace/trace_events.c:903
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff8133aae0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff81180110-ffffffff811801f3: t_next (STB_LOCAL)
ffffffff81189c60-ffffffff81189c9b: t_next (STB_LOCAL)
ffffffff81196dc0-ffffffff81196dd8: t_next (STB_LOCAL)
ffffffff8119a950-ffffffff8119a97c: t_next (STB_LOCAL)
ffffffff811a0c40-ffffffff811a0c7c: t_next (STB_LOCAL)
ffffffff8133aae0-ffffffff8133aafa: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d2f0)
Location: kernel/trace/ftrace.c:3312
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811973b9)
Location: kernel/trace/trace.c:4293
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff811a4c60)
Location: kernel/trace/trace_printk.c:293
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811a85b0)
Location: kernel/trace/trace_stack.c:271
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811af0c1)
Location: kernel/trace/trace_events.c:896
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff81362c90)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff8118d2f0-ffffffff8118d3d6: t_next (STB_LOCAL)
ffffffff81197250-ffffffff8119728b: t_next (STB_LOCAL)
ffffffff811a4c60-ffffffff811a4c78: t_next (STB_LOCAL)
ffffffff811a85b0-ffffffff811a85d1: t_next (STB_LOCAL)
ffffffff811aead0-ffffffff811aeb0f: t_next (STB_LOCAL)
ffffffff81362c90-ffffffff81362caa: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81198f00)
Location: kernel/trace/ftrace.c:3313
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811a2d79)
Location: kernel/trace/trace.c:4322
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff811b0460)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811b3dc0)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811bab21)
Location: kernel/trace/trace_events.c:897
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff8137aef0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff81198f00-ffffffff81198fe6: t_next (STB_LOCAL)
ffffffff811a2c10-ffffffff811a2c4b: t_next (STB_LOCAL)
ffffffff811b0460-ffffffff811b0478: t_next (STB_LOCAL)
ffffffff811b3dc0-ffffffff811b3de1: t_next (STB_LOCAL)
ffffffff811ba200-ffffffff811ba23f: t_next (STB_LOCAL)
ffffffff8137aef0-ffffffff8137af0a: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af2f0)
Location: kernel/trace/ftrace.c:3432
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811bba09)
Location: kernel/trace/trace.c:4509
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff811c8580)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811cc6d0)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811d4801)
Location: kernel/trace/trace_events.c:971
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff813c4260)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff811af2f0-ffffffff811af3d1: t_next (STB_LOCAL)
ffffffff811bba60-ffffffff811bba9b: t_next (STB_LOCAL)
ffffffff811c8580-ffffffff811c8642: t_next (STB_LOCAL)
ffffffff811cc6d0-ffffffff811cc6f1: t_next (STB_LOCAL)
ffffffff811d3090-ffffffff811d30cf: t_next (STB_LOCAL)
ffffffff813c4260-ffffffff813c427a: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811acca0)
Location: kernel/trace/ftrace.c:3510
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811b9619)
Location: kernel/trace/trace.c:4577
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff811c5c60)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811c9c10)
Location: kernel/trace/trace_stack.c:388
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811d1861)
Location: kernel/trace/trace_events.c:972
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff813d61c0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff811acca0-ffffffff811acd81: t_next (STB_LOCAL)
ffffffff811b9670-ffffffff811b96ab: t_next (STB_LOCAL)
ffffffff811c5c60-ffffffff811c5d22: t_next (STB_LOCAL)
ffffffff811c9c10-ffffffff811c9c31: t_next (STB_LOCAL)
ffffffff811d01e0-ffffffff811d021f: t_next (STB_LOCAL)
ffffffff813d61c0-ffffffff813d61da: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ad810)
Location: kernel/trace/ftrace.c:3510
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811b9d19)
Location: kernel/trace/trace.c:4915
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff811c6e50)
Location: kernel/trace/trace_printk.c:305
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811cafc0)
Location: kernel/trace/trace_stack.c:388
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811d2f31)
Location: kernel/trace/trace_events.c:1179
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff813dd0c0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff811ad810-ffffffff811ad8f2: t_next (STB_LOCAL)
ffffffff811b9d70-ffffffff811b9dab: t_next (STB_LOCAL)
ffffffff811c6e50-ffffffff811c6f0d: t_next (STB_LOCAL)
ffffffff811cafc0-ffffffff811cafe1: t_next (STB_LOCAL)
ffffffff811d1490-ffffffff811d14cf: t_next (STB_LOCAL)
ffffffff813dd0c0-ffffffff813dd0da: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d7570)
Location: kernel/trace/ftrace.c:3511
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811e460b)
Location: kernel/trace/trace.c:4989
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff811f24f0)
Location: kernel/trace/trace_printk.c:305
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811f71f0)
Location: kernel/trace/trace_stack.c:388
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811ffe01)
Location: kernel/trace/trace_events.c:1180
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff8142e7b0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff811d7570-ffffffff811d7652: t_next (STB_LOCAL)
ffffffff811e4540-ffffffff811e45a4: t_next (STB_LOCAL)
ffffffff81cb4cde-ffffffff81cb4cfa: t_next.cold (STB_LOCAL)
ffffffff811f24f0-ffffffff811f25ad: t_next (STB_LOCAL)
ffffffff811f71f0-ffffffff811f7211: t_next (STB_LOCAL)
ffffffff811fe160-ffffffff811fe19f: t_next (STB_LOCAL)
ffffffff8142e7b0-ffffffff8142e7ca: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120c890)
Location: kernel/trace/ftrace.c:3523
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8121b97b)
Location: kernel/trace/trace.c:4990
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff8122aff0)
Location: kernel/trace/trace_printk.c:305
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff81230d00)
Location: kernel/trace/trace_stack.c:388
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff8123b481)
Location: kernel/trace/trace_events.c:1200
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff814a82b0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff8120c890-ffffffff8120c984: t_next (STB_LOCAL)
ffffffff8121b8a0-ffffffff8121b918: t_next (STB_LOCAL)
ffffffff81e65d04-ffffffff81e65d20: t_next.cold (STB_LOCAL)
ffffffff8122aff0-ffffffff8122b0f8: t_next (STB_LOCAL)
ffffffff81230d00-ffffffff81230d35: t_next (STB_LOCAL)
ffffffff81238b40-ffffffff81238b8b: t_next (STB_LOCAL)
ffffffff814a82b0-ffffffff814a82d4: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812555e0)
Location: kernel/trace/ftrace.c:3543
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8126553b)
Location: kernel/trace/trace.c:5014
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff81276960)
Location: kernel/trace/trace_printk.c:305
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8127d120)
Location: kernel/trace/trace_stack.c:388
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff81287f81)
Location: kernel/trace/trace_events.c:1215
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff8153dba0)
Location: fs/proc/proc_tty.c:110
Inline: False
```
**Symbols:**

```
ffffffff812555e0-ffffffff812556d4: t_next (STB_LOCAL)
ffffffff81265450-ffffffff812654c8: t_next (STB_LOCAL)
ffffffff8205d2ce-ffffffff8205d2ea: t_next.cold (STB_LOCAL)
ffffffff81276960-ffffffff81276a68: t_next (STB_LOCAL)
ffffffff8127d120-ffffffff8127d155: t_next (STB_LOCAL)
ffffffff81285a40-ffffffff81285a8b: t_next (STB_LOCAL)
ffffffff8153dba0-ffffffff8153dbc4: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126c960)
Location: kernel/trace/ftrace.c:3635
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8127c65b)
Location: kernel/trace/trace.c:5118
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff8128e350)
Location: kernel/trace/trace_printk.c:305
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff81299bc0)
Location: kernel/trace/trace_stack.c:388
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff812a4ca1)
Location: kernel/trace/trace_events.c:1211
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff81575e70)
Location: fs/proc/proc_tty.c:110
Inline: False
```
**Symbols:**

```
ffffffff8126c960-ffffffff8126ca54: t_next (STB_LOCAL)
ffffffff8127c570-ffffffff8127c5e8: t_next (STB_LOCAL)
ffffffff820dbc85-ffffffff820dbca1: t_next.cold (STB_LOCAL)
ffffffff8128e350-ffffffff8128e458: t_next (STB_LOCAL)
ffffffff81299bc0-ffffffff81299bf5: t_next (STB_LOCAL)
ffffffff812a2700-ffffffff812a274b: t_next (STB_LOCAL)
ffffffff81575e70-ffffffff81575e94: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81286f50)
Location: kernel/trace/ftrace.c:3601
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8129734b)
Location: kernel/trace/trace.c:5136
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff812a97d0)
Location: kernel/trace/trace_printk.c:305
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff812b5240)
Location: kernel/trace/trace_stack.c:388
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff812c06c1)
Location: kernel/trace/trace_events.c:1220
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff815ae7c0)
Location: fs/proc/proc_tty.c:110
Inline: False
```
**Symbols:**

```
ffffffff81286f50-ffffffff81287044: t_next (STB_LOCAL)
ffffffff81297260-ffffffff812972d8: t_next (STB_LOCAL)
ffffffff821b7ae0-ffffffff821b7afc: t_next.cold (STB_LOCAL)
ffffffff812a97d0-ffffffff812a98d8: t_next (STB_LOCAL)
ffffffff812b5240-ffffffff812b5275: t_next (STB_LOCAL)
ffffffff812bdf00-ffffffff812bdf4b: t_next (STB_LOCAL)
ffffffff815ae7c0-ffffffff815ae7e4: t_next (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff8000102119e0)
Location: kernel/trace/ftrace.c:3313
Inline: False
```
```
In kernel/trace/trace.c (ffff80001021e0d8)
Location: kernel/trace/trace.c:4322
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffff80001022db38)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (ffff8000102320d8)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (ffff800010239198)
Location: kernel/trace/trace_events.c:897
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffff800010447508)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffff8000102119e0-ffff800010211b04: t_next (STB_LOCAL)
ffff80001021df98-ffff80001021dfd8: t_next (STB_LOCAL)
ffff80001022db38-ffff80001022db5c: t_next (STB_LOCAL)
ffff8000102320d8-ffff800010232104: t_next (STB_LOCAL)
ffff800010238ab0-ffff800010238b08: t_next (STB_LOCAL)
ffff800010447508-ffff800010447544: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0450490)
Location: kernel/trace/ftrace.c:3313
Inline: False
```
```
In kernel/trace/trace.c (c045bff4)
Location: kernel/trace/trace.c:4322
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (c046ada4)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (c046de48)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (c0474d9c)
Location: kernel/trace/trace_events.c:897
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (c060c438)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
c0450490-c0450578: t_next (STB_LOCAL)
c045bcec-c045bd48: t_next (STB_LOCAL)
c046ada4-c046add8: t_next (STB_LOCAL)
c046de48-c046de8c: t_next (STB_LOCAL)
c047463c-c04746b4: t_next (STB_LOCAL)
c060c438-c060c460: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000291590)
Location: kernel/trace/ftrace.c:3313
Inline: False
```
```
In kernel/trace/trace.c (c0000000002a0e88)
Location: kernel/trace/trace.c:4322
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (c0000000002b6b40)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (c0000000002bc910)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (c0000000002c65e8)
Location: kernel/trace/trace_events.c:897
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (c00000000055d700)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
c000000000291590-c000000000291714: t_next (STB_LOCAL)
c0000000002a0c40-c0000000002a0ca8: t_next (STB_LOCAL)
c0000000002b6b40-c0000000002b6b5c: t_next (STB_LOCAL)
c0000000002bc910-c0000000002bc948: t_next (STB_LOCAL)
c0000000002c5010-c0000000002c506c: t_next (STB_LOCAL)
c00000000055d700-c00000000055d740: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000171e52)
Location: kernel/trace/ftrace.c:3313
Inline: False
```
```
In kernel/trace/trace.c (ffffffe00017ab8e)
Location: kernel/trace/trace.c:4322
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffe000187534)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffe000189a5c)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffe00019013a)
Location: kernel/trace/trace_events.c:897
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffe0002dd204)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffe000171e52-ffffffe000171f30: t_next (STB_LOCAL)
ffffffe00017a9d0-ffffffe00017aa08: t_next (STB_LOCAL)
ffffffe000187534-ffffffe000187556: t_next (STB_LOCAL)
ffffffe000189a5c-ffffffe000189a8a: t_next (STB_LOCAL)
ffffffe00018f882-ffffffe00018f8bc: t_next (STB_LOCAL)
ffffffe0002dd204-ffffffe0002dd23e: t_next (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191520)
Location: kernel/trace/ftrace.c:3313
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8119b399)
Location: kernel/trace/trace.c:4322
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff811a8a80)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811ac3e0)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811b3141)
Location: kernel/trace/trace_events.c:897
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff813734d0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff81191520-ffffffff81191606: t_next (STB_LOCAL)
ffffffff8119b230-ffffffff8119b26b: t_next (STB_LOCAL)
ffffffff811a8a80-ffffffff811a8a98: t_next (STB_LOCAL)
ffffffff811ac3e0-ffffffff811ac401: t_next (STB_LOCAL)
ffffffff811b2820-ffffffff811b285f: t_next (STB_LOCAL)
ffffffff813734d0-ffffffff813734ea: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184630)
Location: kernel/trace/ftrace.c:3313
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8118e419)
Location: kernel/trace/trace.c:4322
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff8119ba00)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff8119f2b0)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811a5f41)
Location: kernel/trace/trace_events.c:897
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff81363fa0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff81184630-ffffffff81184716: t_next (STB_LOCAL)
ffffffff8118e2b0-ffffffff8118e2eb: t_next (STB_LOCAL)
ffffffff8119ba00-ffffffff8119ba18: t_next (STB_LOCAL)
ffffffff8119f2b0-ffffffff8119f2d1: t_next (STB_LOCAL)
ffffffff811a5630-ffffffff811a566f: t_next (STB_LOCAL)
ffffffff81363fa0-ffffffff81363fba: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f2f0)
Location: kernel/trace/ftrace.c:3313
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81199169)
Location: kernel/trace/trace.c:4322
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff811a6850)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811aa1b0)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811b0f11)
Location: kernel/trace/trace_events.c:897
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff81370fa0)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff8118f2f0-ffffffff8118f3d6: t_next (STB_LOCAL)
ffffffff81199000-ffffffff8119903b: t_next (STB_LOCAL)
ffffffff811a6850-ffffffff811a6868: t_next (STB_LOCAL)
ffffffff811aa1b0-ffffffff811aa1d1: t_next (STB_LOCAL)
ffffffff811b05f0-ffffffff811b062f: t_next (STB_LOCAL)
ffffffff81370fa0-ffffffff81370fba: t_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void *t_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119cea0)
Location: kernel/trace/ftrace.c:3313
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811a6dc9)
Location: kernel/trace/trace.c:4322
Inline: True
Inline callers:
  - kernel/trace/trace.c:t_start
```
```
In kernel/trace/trace_printk.c (ffffffff811b45f0)
Location: kernel/trace/trace_printk.c:294
Inline: False
```
```
In kernel/trace/trace_stack.c (ffffffff811b7ff0)
Location: kernel/trace/trace_stack.c:389
Inline: False
```
```
In kernel/trace/trace_events.c (ffffffff811befa1)
Location: kernel/trace/trace_events.c:897
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:t_start
```
```
In fs/proc/proc_tty.c (ffffffff81384980)
Location: fs/proc/proc_tty.c:112
Inline: False
```
**Symbols:**

```
ffffffff8119cea0-ffffffff8119cf86: t_next (STB_LOCAL)
ffffffff811a6c80-ffffffff811a6cbb: t_next (STB_LOCAL)
ffffffff811b45f0-ffffffff811b4608: t_next (STB_LOCAL)
ffffffff811b7ff0-ffffffff811b8011: t_next (STB_LOCAL)
ffffffff811be680-ffffffff811be6bf: t_next (STB_LOCAL)
ffffffff81384980-ffffffff8138499a: t_next (STB_LOCAL)
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
