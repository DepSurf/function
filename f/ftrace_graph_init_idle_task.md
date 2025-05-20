# Function: <code>ftrace_graph_init_idle_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81145bc0)
Location: kernel/trace/ftrace.c:5928
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff81145bc0-ffffffff81145c88: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114e400)
Location: kernel/trace/ftrace.c:5961
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff8114e400-ffffffff8114e4c8: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81158340)
Location: kernel/trace/ftrace.c:6010
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff81158340-ffffffff81158408: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115b690)
Location: kernel/trace/ftrace.c:6791
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff8115b690-ffffffff8115b752: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81168780)
Location: kernel/trace/ftrace.c:7079
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff81168780-ffffffff8116883c: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81177450)
Location: kernel/trace/ftrace.c:7066
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff81177450-ffffffff81177509: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a0730)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff811a0730-ffffffff811a07ea: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811ae5dd)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811aea86-ffffffff811aea9f: ftrace_graph_init_idle_task.cold (STB_LOCAL)
ffffffff811ae590-ffffffff811ae652: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b9d20)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811b9d20-ffffffff811b9dda: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d2cc0)
Location: kernel/trace/fgraph.c:505
Inline: False
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811d2cc0-ffffffff811d2d7a: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811cfe30)
Location: kernel/trace/fgraph.c:502
Inline: False
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811cfe30-ffffffff811cfee0: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d0fa0)
Location: kernel/trace/fgraph.c:502
Inline: False
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811d0fa0-ffffffff811d1050: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811fdc20)
Location: kernel/trace/fgraph.c:502
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811fdc20-ffffffff811fdd4d: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812385a0)
Location: kernel/trace/fgraph.c:515
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff812385a0-ffffffff812386dd: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff81285420)
Location: kernel/trace/fgraph.c:515
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff81285420-ffffffff8128555d: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812a20d0)
Location: kernel/trace/fgraph.c:540
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff812a20d0-ffffffff812a220d: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812bd800)
Location: kernel/trace/fgraph.c:540
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff812bd800-ffffffff812bd96f: ftrace_graph_init_idle_task (STB_GLOBAL)
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
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffff8000102384a0)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffff8000102384a0-ffff800010238568: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c04740b0)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
c04740b0-c04741a0: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0000000002c4820)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
c0000000002c4820-c0000000002c4948: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffe00018f3b8)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffe00018f3b8-ffffffe00018f472: ftrace_graph_init_idle_task (STB_GLOBAL)
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
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b2340)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811b2340-ffffffff811b23fa: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a5150)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811a5150-ffffffff811a520a: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b0110)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811b0110-ffffffff811b01ca: ftrace_graph_init_idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ftrace_graph_init_idle_task(struct task_struct *t, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811be180)
Location: kernel/trace/fgraph.c:477
Inline: True
Direct callers:
  - kernel/sched/core.c:init_idle
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811be180-ffffffff811be23a: ftrace_graph_init_idle_task (STB_GLOBAL)
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
