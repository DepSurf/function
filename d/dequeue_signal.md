# Function: <code>dequeue_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108d620)
Location: kernel/signal.c:559
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8108d620-ffffffff8108d77c: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810904f0)
Location: kernel/signal.c:559
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff810904f0-ffffffff8109064a: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095470)
Location: kernel/signal.c:561
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81095470-ffffffff810955c9: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810926f0)
Location: kernel/signal.c:574
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff810926f0-ffffffff81092875: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099580)
Location: kernel/signal.c:576
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81099580-ffffffff8109970b: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d690)
Location: kernel/signal.c:579
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8109d690-ffffffff8109d82b: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5900)
Location: kernel/signal.c:613
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff810a5900-ffffffff810a5a93: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa5e0)
Location: kernel/signal.c:623
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff810aa5e0-ffffffff810aa763: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0be0)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff810b0be0-ffffffff810b0d65: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8ec0)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
**Symbols:**

```
ffffffff810b8ec0-ffffffff810b90a8: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4170)
Location: kernel/signal.c:629
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
**Symbols:**

```
ffffffff810b4170-ffffffff810b4358: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5d80)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
**Symbols:**

```
ffffffff810b5d80-ffffffff810b5f68: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:629
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
**Symbols:**

```
ffffffff81ca481f-ffffffff81ca4834: dequeue_signal.cold (STB_LOCAL)
ffffffff810c8c00-ffffffff810c8df7: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info, enum pid_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:629
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
**Symbols:**

```
ffffffff81e5403a-ffffffff81e5404f: dequeue_signal.cold (STB_LOCAL)
ffffffff810e0180-ffffffff810e037c: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info, enum pid_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:629
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
**Symbols:**

```
ffffffff820560f3-ffffffff82056108: dequeue_signal.cold (STB_LOCAL)
ffffffff81100810-ffffffff81100a0c: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info, enum pid_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:634
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
**Symbols:**

```
ffffffff820d4683-ffffffff820d4698: dequeue_signal.cold (STB_LOCAL)
ffffffff8110c910-ffffffff8110cb0f: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info, enum pid_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:625
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
**Symbols:**

```
ffffffff821af57c-ffffffff821af591: dequeue_signal.cold (STB_LOCAL)
ffffffff811162f0-ffffffff811164ef: dequeue_signal (STB_GLOBAL)
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
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010b788)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffff80001010b788-ffff80001010b984: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03649a0)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
c03649a0-c0364b7c: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153380)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
c000000000153380-c000000000153640: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cdd92)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffe0000cdd92-ffffffe0000cdf28: dequeue_signal (STB_GLOBAL)
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
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aaf50)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff810aaf50-ffffffff810ab0d5: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810998f0)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff810998f0-ffffffff81099a75: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa4b0)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff810aa4b0-ffffffff810aa635: dequeue_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct *tsk, sigset_t *mask, kernel_siginfo_t *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2590)
Location: kernel/signal.c:628
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff810b2590-ffffffff810b2713: dequeue_signal (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>siginfo_t *info</code> ➡️ <code>kernel_siginfo_t *info</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pid_type *type</code>
</li>
</ul>
</details>
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
