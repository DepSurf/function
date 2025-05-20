# Function: <code>idle_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad930)
Location: kernel/sched/core.c:3591
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff810ad930-ffffffff810ad955: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b02e0)
Location: kernel/sched/core.c:3844
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff810b02e0-ffffffff810b0305: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6470)
Location: kernel/sched/core.c:3881
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff810b6470-ffffffff810b6495: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b26f0)
Location: kernel/sched/core.c:3887
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff810b26f0-ffffffff810b2715: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9af0)
Location: kernel/sched/core.c:3931
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff810b9af0-ffffffff810b9b15: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1520)
Location: kernel/sched/core.c:4058
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff810c1520-ffffffff810c1545: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca850)
Location: kernel/sched/core.c:4043
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:register_ftrace_graph
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff810ca850-ffffffff810ca875: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2500)
Location: kernel/sched/core.c:4462
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810d2500-ffffffff810d2525: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc970)
Location: kernel/sched/core.c:4664
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810dc970-ffffffff810dc995: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e54f0)
Location: kernel/sched/core.c:4897
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810e54f0-ffffffff810e5515: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2fa0)
Location: kernel/sched/core.c:5670
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810e2fa0-ffffffff810e2fc5: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4e70)
Location: kernel/sched/core.c:5885
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810e4e70-ffffffff810e4e95: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fbd90)
Location: kernel/sched/core.c:7048
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810fbd90-ffffffff810fbdd5: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81118240)
Location: kernel/sched/core.c:7140
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff81118240-ffffffff8111828d: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113f8d0)
Location: kernel/sched/core.c:7281
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff8113f8d0-ffffffff8113f91d: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114be20)
Location: kernel/sched/core.c:7382
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff8114be20-ffffffff8114be6d: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81157bd0)
Location: kernel/sched/core.c:7432
Inline: False
Direct callers:
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_holdout_task
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff81157bd0-ffffffff81157c1d: idle_task (STB_GLOBAL)
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
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013c4e8)
Location: kernel/sched/core.c:4664
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffff80001013c4e8-ffff80001013c528: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038c1f0)
Location: kernel/sched/core.c:4664
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
c038c1f0-c038c224: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018ab40)
Location: kernel/sched/core.c:4664
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
c00000000018ab40-c00000000018ab74: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000eb85c)
Location: kernel/sched/core.c:4664
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffe0000eb85c-ffffffe0000eb89c: idle_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6b80)
Location: kernel/sched/core.c:4664
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810d6b80-ffffffff810d6ba5: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5470)
Location: kernel/sched/core.c:4664
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810c5470-ffffffff810c5495: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d37c0)
Location: kernel/sched/core.c:4664
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810d37c0-ffffffff810d37e5: idle_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *idle_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de740)
Location: kernel/sched/core.c:4664
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff810de740-ffffffff810de765: idle_task (STB_GLOBAL)
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
