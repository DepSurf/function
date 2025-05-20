# Function: <code>task_clear_jobctl_trapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108da00)
Location: kernel/signal.c:276
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff8108da00-ffffffff8108da3b: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091b8f)
Location: kernel/signal.c:276
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff81090a80-ffffffff81090abb: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096b13)
Location: kernel/signal.c:276
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff810959f0-ffffffff81095a2b: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093e23)
Location: kernel/signal.c:282
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff81092a00-ffffffff81092a3c: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099900)
Location: kernel/signal.c:284
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81099900-ffffffff8109993f: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d8d0)
Location: kernel/signal.c:286
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff8109d8d0-ffffffff8109d90e: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5b90)
Location: kernel/signal.c:303
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810a5b90-ffffffff810a5bce: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa860)
Location: kernel/signal.c:313
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810aa860-ffffffff810aa89e: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0e60)
Location: kernel/signal.c:313
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810b0e60-ffffffff810b0e9e: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bc01f)
Location: kernel/signal.c:313
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff810b9ad0-ffffffff810b9b0e: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b730f)
Location: kernel/signal.c:313
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff810b4d80-ffffffff810b4dbe: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b890f)
Location: kernel/signal.c:311
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff810b6990-ffffffff810b69ce: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cafc6)
Location: kernel/signal.c:312
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff810c9820-ffffffff810c985e: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e168d)
Location: kernel/signal.c:312
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff810e1230-ffffffff810e1282: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110196d)
Location: kernel/signal.c:312
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff81101470-ffffffff811014c2: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110db6d)
Location: kernel/signal.c:313
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff8110d5d0-ffffffff8110d622: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111748f)
Location: kernel/signal.c:304
Inline: True
Inline callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffff81116f10-ffffffff81116f62: task_clear_jobctl_trapping (STB_GLOBAL)
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
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010f4b0)
Location: kernel/signal.c:313
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffff80001010c8c0-ffff80001010c910: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0367194)
Location: kernel/signal.c:313
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
c0364c10-c0364c50: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000156984)
Location: kernel/signal.c:313
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:task_clear_jobctl_pending
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
c000000000153810-c000000000153868: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf96e)
Location: kernel/signal.c:313
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
```
**Symbols:**

```
ffffffe0000cdfa2-ffffffe0000cdff6: task_clear_jobctl_trapping (STB_GLOBAL)
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
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab1d0)
Location: kernel/signal.c:313
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810ab1d0-ffffffff810ab20e: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099b70)
Location: kernel/signal.c:313
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81099b70-ffffffff81099bae: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa730)
Location: kernel/signal.c:313
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810aa730-ffffffff810aa76e: task_clear_jobctl_trapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_clear_jobctl_trapping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2810)
Location: kernel/signal.c:313
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff810b2810-ffffffff810b284e: task_clear_jobctl_trapping (STB_GLOBAL)
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
