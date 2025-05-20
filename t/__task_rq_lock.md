# Function: <code>__task_rq_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810abb9d)
Location: kernel/sched/sched.h:1431
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:rt_mutex_setprio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810abfd0)
Location: kernel/sched/core.c:177
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810abfd0-ffffffff810ac049: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b20b0)
Location: kernel/sched/core.c:177
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810b20b0-ffffffff810b2123: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae070)
Location: kernel/sched/core.c:92
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810ae070-ffffffff810ae102: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5200)
Location: kernel/sched/core.c:94
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810b5200-ffffffff810b5293: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bcc00)
Location: kernel/sched/core.c:72
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810bcc00-ffffffff810bcc97: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5e20)
Location: kernel/sched/core.c:66
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810c5e20-ffffffff810c5eb5: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cba40)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810cba40-ffffffff810cbac9: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4d10)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810d4d10-ffffffff810d4d99: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df680)
Location: kernel/sched/core.c:81
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810df680-ffffffff810df709: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc8f0)
Location: kernel/sched/core.c:180
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810dc8f0-ffffffff810dc9b2: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de4c0)
Location: kernel/sched/core.c:190
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/deadline.c:dl_add_task_root_domain
```
**Symbols:**

```
ffffffff810de4c0-ffffffff810de582: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:543
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/deadline.c:dl_add_task_root_domain
```
**Symbols:**

```
ffffffff81ca5cbe-ffffffff81ca5cd2: __task_rq_lock.cold (STB_LOCAL)
ffffffff810f32a0-ffffffff810f33be: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:613
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/build_policy.c:dl_add_task_root_domain
```
**Symbols:**

```
ffffffff81e555e1-ffffffff81e555f6: __task_rq_lock.cold (STB_LOCAL)
ffffffff8110f290-ffffffff8110f3d0: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:606
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/build_policy.c:dl_add_task_root_domain
```
**Symbols:**

```
ffffffff82056a2a-ffffffff82056a3f: __task_rq_lock.cold (STB_LOCAL)
ffffffff811360d0-ffffffff81136210: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:627
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/build_policy.c:dl_add_task_root_domain
```
**Symbols:**

```
ffffffff820d50fa-ffffffff820d510f: __task_rq_lock.cold (STB_LOCAL)
ffffffff811450d0-ffffffff81145211: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:628
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/build_policy.c:dl_add_task_root_domain
```
**Symbols:**

```
ffffffff821b001d-ffffffff821b0032: __task_rq_lock.cold (STB_LOCAL)
ffffffff811505f0-ffffffff81150731: __task_rq_lock (STB_GLOBAL)
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
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010135838)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffff800010135838-ffff8000101358f0: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03847a8)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
c03847a8-c038488c: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000180560)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
c000000000180560-c0000000001806ac: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e719c)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffe0000e719c-ffffffe0000e7282: __task_rq_lock (STB_GLOBAL)
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
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf000)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810cf000-ffffffff810cf089: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bd8d0)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810bd8d0-ffffffff810bd959: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce430)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810ce430-ffffffff810ce4b9: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rq *__task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6b90)
Location: kernel/sched/core.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810d6b90-ffffffff810d6c17: __task_rq_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
