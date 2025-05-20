# Function: <code>task_set_jobctl_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108d990)
Location: kernel/signal.c:248
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff8108d990-ffffffff8108d9f5: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090a10)
Location: kernel/signal.c:248
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff81090a10-ffffffff81090a75: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095990)
Location: kernel/signal.c:248
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff81095990-ffffffff810959f0: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092990)
Location: kernel/signal.c:254
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff81092990-ffffffff810929f5: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099890)
Location: kernel/signal.c:256
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff81099890-ffffffff810998f5: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d860)
Location: kernel/signal.c:258
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff8109d860-ffffffff8109d8c9: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5b20)
Location: kernel/signal.c:275
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810a5b20-ffffffff810a5b89: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa7f0)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810aa7f0-ffffffff810aa855: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0df0)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810b0df0-ffffffff810b0e55: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8e42)
Location: kernel/signal.c:285
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810b9a60-ffffffff810b9ac5: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b40f2)
Location: kernel/signal.c:285
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810b4d10-ffffffff810b4d75: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4f52)
Location: kernel/signal.c:283
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810b6920-ffffffff810b6985: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c7012)
Location: kernel/signal.c:284
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:task_join_group_stop
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff810c97b0-ffffffff810c9815: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dee83)
Location: kernel/signal.c:284
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810e11b0-ffffffff810e1229: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ff473)
Location: kernel/signal.c:284
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff811013e0-ffffffff81101459: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110b4c3)
Location: kernel/signal.c:285
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff8110d540-ffffffff8110d5b9: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81114e73)
Location: kernel/signal.c:276
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_trap_notify
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff81116e80-ffffffff81116ef9: task_set_jobctl_pending (STB_GLOBAL)
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
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010c838)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffff80001010c838-ffff80001010c8c0: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0364b7c)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
c0364b7c-c0364c10: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153780)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
c000000000153780-c000000000153804: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cdf28)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffe0000cdf28-ffffffe0000cdfa2: task_set_jobctl_pending (STB_GLOBAL)
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
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab160)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810ab160-ffffffff810ab1c5: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099b00)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff81099b00-ffffffff81099b65: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa6c0)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810aa6c0-ffffffff810aa725: task_set_jobctl_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool task_set_jobctl_pending(struct task_struct *task, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b27a0)
Location: kernel/signal.c:285
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:task_join_group_stop
```
**Symbols:**

```
ffffffff810b27a0-ffffffff810b2805: task_set_jobctl_pending (STB_GLOBAL)
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
