# Function: <code>task_participate_group_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108dab0)
Location: kernel/signal.c:329
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff8108dab0-ffffffff8108db78: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090b30)
Location: kernel/signal.c:329
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81090b30-ffffffff81090bf8: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095aa0)
Location: kernel/signal.c:329
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81095aa0-ffffffff81095b8b: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092ab0)
Location: kernel/signal.c:335
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81092ab0-ffffffff81092b34: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099990)
Location: kernel/signal.c:337
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81099990-ffffffff81099a14: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d960)
Location: kernel/signal.c:339
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff8109d960-ffffffff8109d9e4: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5c20)
Location: kernel/signal.c:356
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810a5c20-ffffffff810a5ca4: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810aa8f0-ffffffff810aa974: task_participate_group_stop (STB_LOCAL)
ffffffff810b0f6f-ffffffff810b0f85: task_participate_group_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0ef0)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810b0ef0-ffffffff810b0f74: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8580)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810b8580-ffffffff810b8646: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3830)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810b3830-ffffffff810b38f6: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4d50)
Location: kernel/signal.c:364
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810b4d50-ffffffff810b4e16: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c6e00)
Location: kernel/signal.c:365
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810c6e00-ffffffff810c6ec6: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dec40)
Location: kernel/signal.c:365
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff810dec40-ffffffff810ded21: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fefd0)
Location: kernel/signal.c:365
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff810fefd0-ffffffff810ff0b1: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110aff0)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff8110aff0-ffffffff8110b0d1: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81114c00)
Location: kernel/signal.c:357
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff81114c00-ffffffff81114ce1: task_participate_group_stop (STB_LOCAL)
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
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010c990)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffff80001010c990-ffff80001010ca48: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0364cb4)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
c0364cb4-c0364dc8: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153900)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
c000000000153900-c0000000001539f8: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce074)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffe0000ce074-ffffffe0000ce10e: task_participate_group_stop (STB_LOCAL)
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
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab260)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810ab260-ffffffff810ab2e4: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099c00)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81099c00-ffffffff81099c84: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa7c0)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810aa7c0-ffffffff810aa844: task_participate_group_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool task_participate_group_stop(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b28a0)
Location: kernel/signal.c:366
Inline: False
Direct callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810b28a0-ffffffff810b2924: task_participate_group_stop (STB_LOCAL)
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
