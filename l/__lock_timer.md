# Function: <code>__lock_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f09c0)
Location: kernel/time/posix-timers.c:693
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:do_schedule_next_timer
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_delete
```
**Symbols:**

```
ffffffff810f09c0-ffffffff810f0a80: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f79e0)
Location: kernel/time/posix-timers.c:693
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
**Symbols:**

```
ffffffff810f79e0-ffffffff810f7a95: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81105380)
Location: kernel/time/posix-timers.c:693
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
**Symbols:**

```
ffffffff81105380-ffffffff81105435: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81107340)
Location: kernel/time/posix-timers.c:609
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff81107340-ffffffff811073fa: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81112470)
Location: kernel/time/posix-timers.c:615
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff81112470-ffffffff8111252a: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111de60)
Location: kernel/time/posix-timers.c:624
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff8111de60-ffffffff8111df25: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81129600)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff81129600-ffffffff811296c5: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81134090)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff81134090-ffffffff81134143: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81140030)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff81140030-ffffffff811400e3: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114fca0)
Location: kernel/time/posix-timers.c:614
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff8114fca0-ffffffff8114fd52: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114bf20)
Location: kernel/time/posix-timers.c:614
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff8114bf20-ffffffff8114bfe0: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d3d0)
Location: kernel/time/posix-timers.c:614
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff8114d3d0-ffffffff8114d492: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81170b90)
Location: kernel/time/posix-timers.c:614
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff81170b90-ffffffff81170c52: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a51c0)
Location: kernel/time/posix-timers.c:614
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff811a51c0-ffffffff811a529a: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e4b20)
Location: kernel/time/posix-timers.c:614
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff811e4b20-ffffffff811e4bfa: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9180)
Location: kernel/time/posix-timers.c:560
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff811f9180-ffffffff811f925d: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120f370)
Location: kernel/time/posix-timers.c:560
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff8120f370-ffffffff8120f44d: __lock_timer (STB_LOCAL)
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
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101ab8f8)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__arm64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffff8000101ab8f8-ffff8000101aba44: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f5730)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__se_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
c03f5730-c03f5810: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020dad0)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__se_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
c00000000020dad0-c00000000020dc34: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe0001357de)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__se_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__se_sys_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffe0001357de-ffffffe000135894: __lock_timer (STB_LOCAL)
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
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811387e0)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff811387e0-ffffffff81138893: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112b230)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff8112b230-ffffffff8112b2e3: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81136500)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff81136500-ffffffff811365b3: __lock_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct k_itimer *__lock_timer(timer_t timer_id, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81142ff0)
Location: kernel/time/posix-timers.c:588
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:timer_wait_running
  - kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun
  - kernel/time/posix-timers.c:__x64_sys_timer_getoverrun
  - kernel/time/posix-timers.c:do_timer_gettime
  - kernel/time/posix-timers.c:posixtimer_rearm
```
**Symbols:**

```
ffffffff81142ff0-ffffffff811430ba: __lock_timer (STB_LOCAL)
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
