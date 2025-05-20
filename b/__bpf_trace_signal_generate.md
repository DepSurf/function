# Function: <code>__bpf_trace_signal_generate</code>

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
void __bpf_trace_signal_generate(void *__data, int sig, struct siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c5a0)
Location: include/trace/events/signal.h:51
Inline: False
```
**Symbols:**

```
ffffffff8109c5a0-ffffffff8109c5b3: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a4800)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810a4800-ffffffff810a4813: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9480)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810a9480-ffffffff810a9493: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afa50)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810afa50-ffffffff810afa63: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7760)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810b7760-ffffffff810b7773: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b29f0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810b29f0-ffffffff810b2a03: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4030)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810b4030-ffffffff810b4043: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c6240)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810c6240-ffffffff810c6253: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dda20)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810dda20-ffffffff810dda45: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fdb30)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810fdb30-ffffffff810fdb55: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81109ba0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff81109ba0-ffffffff81109bc5: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81113540)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff81113540-ffffffff81113565: __bpf_trace_signal_generate (STB_LOCAL)
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
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010aa28)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffff80001010aa28-ffff80001010aa48: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0363bf0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
c0363bf0-c0363c3c: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000151ed0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
c000000000151ed0-c000000000151f08: __bpf_trace_signal_generate (STB_LOCAL)
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
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9dc0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810a9dc0-ffffffff810a9dd3: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098770)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff81098770-ffffffff81098783: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9320)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810a9320-ffffffff810a9333: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1470)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810b1470-ffffffff810b1483: __bpf_trace_signal_generate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct siginfo *info</code> ➡️ <code>struct kernel_siginfo *info</code>
</li>
</ul>
</details>
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
