# Function: <code>stop_one_cpu_nowait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81120640)
Location: kernel/stop_machine.c:306
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff81120640-ffffffff81120672: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81128590)
Location: kernel/stop_machine.c:312
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff81128590-ffffffff811285c2: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81132240)
Location: kernel/stop_machine.c:328
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff81132240-ffffffff81132272: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81133800)
Location: kernel/stop_machine.c:328
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff81133800-ffffffff81133832: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811405b0)
Location: kernel/stop_machine.c:328
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff811405b0-ffffffff811405e2: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114eef0)
Location: kernel/stop_machine.c:356
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff8114eef0-ffffffff8114ef22: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115bbd0)
Location: kernel/stop_machine.c:356
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff8115bbd0-ffffffff8115bc02: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81168290)
Location: kernel/stop_machine.c:364
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81168290-ffffffff811682c5: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81174150)
Location: kernel/stop_machine.c:366
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81174150-ffffffff81174185: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81186040)
Location: kernel/stop_machine.c:367
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81186040-ffffffff81186075: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811831d0)
Location: kernel/stop_machine.c:384
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff811831d0-ffffffff81183209: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811842f0)
Location: kernel/stop_machine.c:384
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff811842f0-ffffffff81184329: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811ac5d0)
Location: kernel/stop_machine.c:384
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff811ac5d0-ffffffff811ac609: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811de080)
Location: kernel/stop_machine.c:384
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff811de080-ffffffff811de0cb: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81223b80)
Location: kernel/stop_machine.c:384
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81223b80-ffffffff81223bcb: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8123a1e0)
Location: kernel/stop_machine.c:384
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff8123a1e0-ffffffff8123a22b: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81253eb0)
Location: kernel/stop_machine.c:384
Inline: False
Direct callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81253eb0-ffffffff81253efb: stop_one_cpu_nowait (STB_GLOBAL)
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
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e8968)
Location: kernel/stop_machine.c:366
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffff8000101e8968-ffff8000101e89b8: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0428a2c)
Location: kernel/stop_machine.c:366
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
c0428a2c-c0428a64: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c000000000259450)
Location: kernel/stop_machine.c:366
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
c000000000259450-c000000000259484: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015d940)
Location: kernel/stop_machine.c:366
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffe00015d940-ffffffe00015d992: stop_one_cpu_nowait (STB_GLOBAL)
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
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116c770)
Location: kernel/stop_machine.c:366
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff8116c770-ffffffff8116c7a5: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115f930)
Location: kernel/stop_machine.c:366
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff8115f930-ffffffff8115f965: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116a540)
Location: kernel/stop_machine.c:366
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff8116a540-ffffffff8116a575: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool stop_one_cpu_nowait(unsigned int cpu, cpu_stop_fn_t fn, void *arg, struct cpu_stop_work *work_buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81177cb0)
Location: kernel/stop_machine.c:366
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff81177cb0-ffffffff81177ce5: stop_one_cpu_nowait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
