# Function: <code>retarget_shared_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108dfc0)
Location: kernel/signal.c:2356
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff8108dfc0-ffffffff8108e03a: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091040)
Location: kernel/signal.c:2356
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff81091040-ffffffff810910ba: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095fb0)
Location: kernel/signal.c:2362
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff81095fb0-ffffffff81096026: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092f90)
Location: kernel/signal.c:2383
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff81092f90-ffffffff81093006: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099e70)
Location: kernel/signal.c:2384
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff81099e70-ffffffff81099ee6: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109de70)
Location: kernel/signal.c:2517
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff8109de70-ffffffff8109dee8: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a6180)
Location: kernel/signal.c:2624
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810a6180-ffffffff810a61f8: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aae60)
Location: kernel/signal.c:2783
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810aae60-ffffffff810aaee6: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1460)
Location: kernel/signal.c:2788
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810b1460-ffffffff810b14e6: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810b8460)
Location: kernel/signal.c:2806
Inline: True
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810b8460-ffffffff810b8505: retarget_shared_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810b3710)
Location: kernel/signal.c:2826
Inline: True
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810b3710-ffffffff810b37b5: retarget_shared_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810b4c30)
Location: kernel/signal.c:2848
Inline: True
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810b4c30-ffffffff810b4cd5: retarget_shared_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810c6ed0)
Location: kernel/signal.c:2933
Inline: True
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810c6ed0-ffffffff810c6f75: retarget_shared_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810de850)
Location: kernel/signal.c:2913
Inline: True
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810de850-ffffffff810de911: retarget_shared_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810fedd0)
Location: kernel/signal.c:2915
Inline: True
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810fedd0-ffffffff810fee91: retarget_shared_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff8110adf0)
Location: kernel/signal.c:2937
Inline: True
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff8110adf0-ffffffff8110aeb1: retarget_shared_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff81114830)
Location: kernel/signal.c:2949
Inline: True
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff81114830-ffffffff81114908: retarget_shared_pending.isra.0 (STB_LOCAL)
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
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010d088)
Location: kernel/signal.c:2788
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffff80001010d088-ffff80001010d124: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03652ec)
Location: kernel/signal.c:2788
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
c03652ec-c03653a0: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000154130)
Location: kernel/signal.c:2788
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
c000000000154130-c0000000001541f4: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce5cc)
Location: kernel/signal.c:2788
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffe0000ce5cc-ffffffe0000ce652: retarget_shared_pending (STB_LOCAL)
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
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab7d0)
Location: kernel/signal.c:2788
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810ab7d0-ffffffff810ab856: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a170)
Location: kernel/signal.c:2788
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff8109a170-ffffffff8109a1f6: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aad30)
Location: kernel/signal.c:2788
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810aad30-ffffffff810aadb6: retarget_shared_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void retarget_shared_pending(struct task_struct *tsk, sigset_t *which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2e10)
Location: kernel/signal.c:2788
Inline: False
Direct callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
```
**Symbols:**

```
ffffffff810b2e10-ffffffff810b2e96: retarget_shared_pending (STB_LOCAL)
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
