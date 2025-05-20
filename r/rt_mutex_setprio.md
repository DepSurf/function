# Function: <code>rt_mutex_setprio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad3c0)
Location: kernel/sched/core.c:3365
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:__rt_mutex_adjust_prio
```
**Symbols:**

```
ffffffff810ad3c0-ffffffff810ad782: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afda0)
Location: kernel/sched/core.c:3613
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:__rt_mutex_adjust_prio
```
**Symbols:**

```
ffffffff810afda0-ffffffff810b0134: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5f20)
Location: kernel/sched/core.c:3644
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:__rt_mutex_adjust_prio
```
**Symbols:**

```
ffffffff810b5f20-ffffffff810b62ce: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b21c0)
Location: kernel/sched/core.c:3617
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810b21c0-ffffffff810b2547: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b95a0)
Location: kernel/sched/core.c:3661
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810b95a0-ffffffff810b9943: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1060)
Location: kernel/sched/core.c:3771
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810c1060-ffffffff810c1403: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca3c0)
Location: kernel/sched/core.c:3755
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810ca3c0-ffffffff810ca771: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:4174
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810d45c2-ffffffff810d45e8: rt_mutex_setprio.cold (STB_LOCAL)
ffffffff810d2060-ffffffff810d2424: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc040)
Location: kernel/sched/core.c:4376
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810dc040-ffffffff810dc89b: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4fe0)
Location: kernel/sched/core.c:4609
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810e4fe0-ffffffff810e541b: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2ad0)
Location: kernel/sched/core.c:5379
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810e2ad0-ffffffff810e2ecd: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e49a0)
Location: kernel/sched/core.c:5593
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810e49a0-ffffffff810e4d98: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fb880)
Location: kernel/sched/core.c:6756
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810fb880-ffffffff810fbc74: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81117cc0)
Location: kernel/sched/core.c:6836
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff81117cc0-ffffffff8111810b: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113f2f0)
Location: kernel/sched/core.c:6977
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff8113f2f0-ffffffff8113f746: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114b820)
Location: kernel/sched/core.c:7078
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff8114b820-ffffffff8114bc98: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811575d0)
Location: kernel/sched/core.c:7129
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff811575d0-ffffffff81157a48: rt_mutex_setprio (STB_GLOBAL)
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
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013c050)
Location: kernel/sched/core.c:4376
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffff80001013c050-ffff80001013c3c4: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038b7c4)
Location: kernel/sched/core.c:4376
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
c038b7c4-c038c034: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018a050)
Location: kernel/sched/core.c:4376
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
c00000000018a050-c00000000018a9e4: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000eb462)
Location: kernel/sched/core.c:4376
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffe0000eb462-ffffffe0000eb770: rt_mutex_setprio (STB_GLOBAL)
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
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d64b0)
Location: kernel/sched/core.c:4376
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810d64b0-ffffffff810d6aad: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4b40)
Location: kernel/sched/core.c:4376
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810c4b40-ffffffff810c539b: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d32e0)
Location: kernel/sched/core.c:4376
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810d32e0-ffffffff810d36e5: rt_mutex_setprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct *p, struct task_struct *pi_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dddd0)
Location: kernel/sched/core.c:4376
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810dddd0-ffffffff810de66d: rt_mutex_setprio (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *pi_task</code>
</li>
<li>
<b>Param removed. </b>
<code>int prio</code>
</li>
</ul>
</details>
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
