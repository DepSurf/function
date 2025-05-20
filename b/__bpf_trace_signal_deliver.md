# Function: <code>__bpf_trace_signal_deliver</code>

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
void __bpf_trace_signal_deliver(void *__data, int sig, struct siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c5c0)
Location: include/trace/events/signal.h:97
Inline: False
```
**Symbols:**

```
ffffffff8109c5c0-ffffffff8109c5cd: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a4820)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810a4820-ffffffff810a482d: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a94a0)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810a94a0-ffffffff810a94ad: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afa70)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810afa70-ffffffff810afa7d: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7780)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810b7780-ffffffff810b778d: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2a10)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810b2a10-ffffffff810b2a1d: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4050)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810b4050-ffffffff810b405d: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c6260)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810c6260-ffffffff810c626d: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dda50)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810dda50-ffffffff810dda69: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fdb70)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810fdb70-ffffffff810fdb89: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81109be0)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff81109be0-ffffffff81109bf9: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81113580)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff81113580-ffffffff81113599: __bpf_trace_signal_deliver (STB_LOCAL)
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
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010aa48)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffff80001010aa48-ffff80001010aa60: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0363c3c)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
c0363c3c-c0363c74: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000151f10)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
c000000000151f10-c000000000151f40: __bpf_trace_signal_deliver (STB_LOCAL)
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
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9de0)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810a9de0-ffffffff810a9ded: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098790)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff81098790-ffffffff8109879d: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9340)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810a9340-ffffffff810a934d: __bpf_trace_signal_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1490)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810b1490-ffffffff810b149d: __bpf_trace_signal_deliver (STB_LOCAL)
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
