# Function: <code>schedule_preempt_disabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81820690)
Location: kernel/sched/core.c:3239
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81820690-ffffffff818206a0: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8189aaf0)
Location: kernel/sched/core.c:3457
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff8189aaf0-ffffffff8189ab00: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff818cf100)
Location: kernel/sched/core.c:3488
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/sched/idle.c:do_idle
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff818cf100-ffffffff818cf110: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff819066a0)
Location: kernel/sched/core.c:3446
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff819066a0-ffffffff819066b0: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81990720)
Location: kernel/sched/core.c:3490
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff81990720-ffffffff81990730: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff819ecf20)
Location: kernel/sched/core.c:3600
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff819ecf20-ffffffff819ecf30: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a28150)
Location: kernel/sched/core.c:3584
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff81a28150-ffffffff81a28160: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a988e0)
Location: kernel/sched/core.c:4003
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff81a988e0-ffffffff81a988f0: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ad0230)
Location: kernel/sched/core.c:4206
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff81ad0230-ffffffff81ad0240: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bc8bd0)
Location: kernel/sched/core.c:4438
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
**Symbols:**

```
ffffffff81bc8bd0-ffffffff81bc8be0: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c419b0)
Location: kernel/sched/core.c:5208
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
**Symbols:**

```
ffffffff81c419b0-ffffffff81c419c0: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c33920)
Location: kernel/sched/core.c:5284
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
**Symbols:**

```
ffffffff81c33920-ffffffff81c33930: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81d522e0)
Location: kernel/sched/core.c:6435
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
**Symbols:**

```
ffffffff81d522e0-ffffffff81d522f0: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81f229a0)
Location: kernel/sched/core.c:6600
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
**Symbols:**

```
ffffffff81f229a0-ffffffff81f229c2: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff820cd2d0)
Location: kernel/sched/core.c:6741
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff820cd2d0-ffffffff820cd2f2: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82151750)
Location: kernel/sched/core.c:6842
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff82151750-ffffffff82151772: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82234590)
Location: kernel/sched/core.c:6871
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
**Symbols:**

```
ffffffff82234590-ffffffff822345b2: schedule_preempt_disabled (STB_GLOBAL)
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
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010da1fb0)
Location: kernel/sched/core.c:4206
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffff800010da1fb0-ffff800010da1fcc: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0e9a128)
Location: kernel/sched/core.c:4206
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
c0e9a128-c0e9a144: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000ee33d0)
Location: kernel/sched/core.c:4206
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
c000000000ee33d0-c000000000ee3400: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0008c56da)
Location: kernel/sched/core.c:4206
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffe0008c56da-ffffffe0008c56fc: schedule_preempt_disabled (STB_GLOBAL)
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
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a6f0a0)
Location: kernel/sched/core.c:4206
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff81a6f0a0-ffffffff81a6f0b0: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a2b4b0)
Location: kernel/sched/core.c:4206
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff81a2b4b0-ffffffff81a2b4c0: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81adb4b0)
Location: kernel/sched/core.c:4206
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff81adb4b0-ffffffff81adb4c0: schedule_preempt_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void schedule_preempt_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ae7a40)
Location: kernel/sched/core.c:4206
Inline: False
Direct callers:
  - init/main.c:rest_init
```
**Symbols:**

```
ffffffff81ae7a40-ffffffff81ae7a5e: schedule_preempt_disabled (STB_GLOBAL)
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
