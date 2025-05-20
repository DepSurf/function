# Function: <code>__traceiter_signal_generate</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b23b0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810b23b0-ffffffff810b241b: __traceiter_signal_generate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b39f0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810b39f0-ffffffff810b3a59: __traceiter_signal_generate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c5be0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810c5be0-ffffffff810c5c49: __traceiter_signal_generate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dd1d0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810dd1d0-ffffffff810dd24f: __traceiter_signal_generate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fd500)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff810fd500-ffffffff810fd57f: __traceiter_signal_generate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81109530)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff81109530-ffffffff811095af: __traceiter_signal_generate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_signal_generate(void *__data, int sig, struct kernel_siginfo *info, struct task_struct *task, int group, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81112ed0)
Location: include/trace/events/signal.h:50
Inline: False
```
**Symbols:**

```
ffffffff81112ed0-ffffffff81112f4f: __traceiter_signal_generate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
