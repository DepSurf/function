# Function: <code>recalc_sigpending_tsk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108d110)
Location: kernel/signal.c:132
Inline: False
Direct callers:
  - kernel/signal.c:recalc_sigpending_and_wake
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff8108d110-ffffffff8108d15a: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810902d0)
Location: kernel/signal.c:132
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff810902d0-ffffffff8109031a: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095250)
Location: kernel/signal.c:132
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff81095250-ffffffff81095295: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092280)
Location: kernel/signal.c:138
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff81092280-ffffffff810922c5: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099110)
Location: kernel/signal.c:140
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff81099110-ffffffff81099155: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ccb0)
Location: kernel/signal.c:141
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff8109ccb0-ffffffff8109ccf4: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a4bf0)
Location: kernel/signal.c:145
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff810a4bf0-ffffffff810a4c34: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a98e0)
Location: kernel/signal.c:154
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff810a98e0-ffffffff810a9932: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afe70)
Location: kernel/signal.c:154
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff810afe70-ffffffff810afec2: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b79f0)
Location: kernel/signal.c:154
Inline: True
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810b79f0-ffffffff810b7a45: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2c80)
Location: kernel/signal.c:154
Inline: True
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810b2c80-ffffffff810b2cd5: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b42b0)
Location: kernel/signal.c:153
Inline: True
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810b42b0-ffffffff810b4305: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c6460)
Location: kernel/signal.c:154
Inline: True
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810c6460-ffffffff810c64b5: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dddc0)
Location: kernel/signal.c:154
Inline: True
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810dddc0-ffffffff810dde25: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fe280)
Location: kernel/signal.c:154
Inline: True
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810fe280-ffffffff810fe2e2: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110a2f0)
Location: kernel/signal.c:155
Inline: True
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff8110a2f0-ffffffff8110a352: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81113c90)
Location: kernel/signal.c:156
Inline: True
```
**Symbols:**

```
ffffffff81113c90-ffffffff81113cf2: recalc_sigpending_tsk (STB_LOCAL)
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
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010b310)
Location: kernel/signal.c:154
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffff80001010b310-ffff80001010b39c: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0363c74)
Location: kernel/signal.c:154
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
c0363c74-c0363d00: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001516c0)
Location: kernel/signal.c:154
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
c0000000001516c0-c000000000151728: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cfa72)
Location: kernel/signal.c:154
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
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
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa1e0)
Location: kernel/signal.c:154
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff810aa1e0-ffffffff810aa232: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098bf0)
Location: kernel/signal.c:154
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff81098bf0-ffffffff81098c42: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9740)
Location: kernel/signal.c:154
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff810a9740-ffffffff810a9792: recalc_sigpending_tsk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool recalc_sigpending_tsk(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1ad0)
Location: kernel/signal.c:154
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
**Symbols:**

```
ffffffff810b1ad0-ffffffff810b1b22: recalc_sigpending_tsk (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
