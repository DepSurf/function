# Function: <code>synchronize_rcu_tasks</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e9326)
Location: kernel/rcu/update.c:592
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff810e9370-ffffffff810e9380: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f01f6)
Location: kernel/rcu/update.c:595
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff810f0240-ffffffff810f0250: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f0200)
Location: kernel/rcu/update.c:654
Inline: True
```
**Symbols:**

```
ffffffff810f0200-ffffffff810f024e: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f9ec6)
Location: kernel/rcu/update.c:653
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff810f9f10-ffffffff810f9f20: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81102453)
Location: kernel/rcu/update.c:605
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81102480-ffffffff81102490: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8110de43)
Location: kernel/rcu/update.c:601
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff8110de70-ffffffff8110de80: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81117533)
Location: kernel/rcu/update.c:546
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff811174c0-ffffffff8111750e: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81123903)
Location: kernel/rcu/update.c:573
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81123890-ffffffff811238de: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:529
Inline: True
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff81130680-ffffffff811306cf: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811742e0)
Location: kernel/rcu/tasks.h:917
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811742e0-ffffffff8117434d: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a9db0)
Location: kernel/rcu/tasks.h:968
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811a9db0-ffffffff811a9dcd: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bbca0)
Location: kernel/rcu/tasks.h:1005
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811bbca0-ffffffff811bbcbd: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cc140)
Location: kernel/rcu/tasks.h:1098
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811cc140-ffffffff811cc15d: synchronize_rcu_tasks (STB_GLOBAL)
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
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffff800010188a10)
Location: kernel/rcu/update.c:573
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffff800010188a40-ffff800010188a58: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c03d7384)
Location: kernel/rcu/update.c:573
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
c03d73b8-c03d73d8: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c0000000001e2cfc)
Location: kernel/rcu/update.c:573
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
c0000000001e2c40-c0000000001e2cb4: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffe00011df6e)
Location: kernel/rcu/update.c:573
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffe00011df96-ffffffe00011dfb6: synchronize_rcu_tasks (STB_GLOBAL)
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
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8111bee3)
Location: kernel/rcu/update.c:573
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff8111be70-ffffffff8111bebe: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8110cf53)
Location: kernel/rcu/update.c:573
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff8110cee0-ffffffff8110cf2e: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81119dd3)
Location: kernel/rcu/update.c:573
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff81119d60-ffffffff81119dae: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81125533)
Location: kernel/rcu/update.c:573
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
Direct callers:
  - kernel/kprobes.c:kprobe_optimizer
```
**Symbols:**

```
ffffffff811254c0-ffffffff8112550e: synchronize_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
