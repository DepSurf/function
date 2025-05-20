# Function: <code>task_clear_jobctl_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108da40)
Location: kernel/signal.c:300
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:task_participate_group_stop
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff8108da40-ffffffff8108daae: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090ac0)
Location: kernel/signal.c:300
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81090ac0-ffffffff81090b2e: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095a30)
Location: kernel/signal.c:300
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81095a30-ffffffff81095a9e: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092a40)
Location: kernel/signal.c:306
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81092a40-ffffffff81092aae: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099940)
Location: kernel/signal.c:308
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81099940-ffffffff81099989: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d910)
Location: kernel/signal.c:310
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff8109d910-ffffffff8109d959: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5bd0)
Location: kernel/signal.c:327
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810a5bd0-ffffffff810a5c19: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa8a0)
Location: kernel/signal.c:337
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810aa8a0-ffffffff810aa8e8: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0ea0)
Location: kernel/signal.c:337
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810b0ea0-ffffffff810b0ee8: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba8dd)
Location: kernel/signal.c:337
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810b9b10-ffffffff810b9b80: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5b9d)
Location: kernel/signal.c:337
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810b4dc0-ffffffff810b4e30: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b779d)
Location: kernel/signal.c:335
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810b69d0-ffffffff810b6a40: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cadd7)
Location: kernel/signal.c:336
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810c9860-ffffffff810c98d0: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e1675)
Location: kernel/signal.c:336
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff810e1290-ffffffff810e1314: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81101955)
Location: kernel/signal.c:336
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff811014e0-ffffffff81101564: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110db55)
Location: kernel/signal.c:337
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff8110d640-ffffffff8110d6c4: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81117477)
Location: kernel/signal.c:328
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff81116f80-ffffffff81117004: task_clear_jobctl_pending (STB_GLOBAL)
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
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010c910)
Location: kernel/signal.c:337
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffff80001010c910-ffff80001010c990: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0364c50)
Location: kernel/signal.c:337
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
c0364c50-c0364cb4: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153870)
Location: kernel/signal.c:337
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
c000000000153870-c0000000001538f4: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cdff6)
Location: kernel/signal.c:337
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffe0000cdff6-ffffffe0000ce074: task_clear_jobctl_pending (STB_GLOBAL)
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
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab210)
Location: kernel/signal.c:337
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810ab210-ffffffff810ab258: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099bb0)
Location: kernel/signal.c:337
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff81099bb0-ffffffff81099bf8: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa770)
Location: kernel/signal.c:337
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810aa770-ffffffff810aa7b8: task_clear_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2850)
Location: kernel/signal.c:337
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/coredump.c:zap_process
```
**Symbols:**

```
ffffffff810b2850-ffffffff810b2898: task_clear_jobctl_pending (STB_GLOBAL)
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
