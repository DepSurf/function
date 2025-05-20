# Function: <code>timer_wait_running</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811401e0)
Location: kernel/time/posix-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
```
**Symbols:**

```
ffffffff811401e0-ffffffff81140233: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114ff80)
Location: kernel/time/posix-timers.c:839
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
```
**Symbols:**

```
ffffffff8114ff80-ffffffff8114ffd3: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114c200)
Location: kernel/time/posix-timers.c:839
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
```
**Symbols:**

```
ffffffff8114c200-ffffffff8114c258: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d6c0)
Location: kernel/time/posix-timers.c:839
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
```
**Symbols:**

```
ffffffff8114d6c0-ffffffff8114d718: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81170ce0)
Location: kernel/time/posix-timers.c:839
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
```
**Symbols:**

```
ffffffff81170ce0-ffffffff81170d38: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a5330)
Location: kernel/time/posix-timers.c:839
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
```
**Symbols:**

```
ffffffff811a5330-ffffffff811a5396: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e4cb0)
Location: kernel/time/posix-timers.c:839
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
```
**Symbols:**

```
ffffffff811e4cb0-ffffffff811e4d16: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9310)
Location: kernel/time/posix-timers.c:837
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
```
**Symbols:**

```
ffffffff811f9310-ffffffff811f9376: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120f500)
Location: kernel/time/posix-timers.c:837
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_settime
```
**Symbols:**

```
ffffffff8120f500-ffffffff8120f566: timer_wait_running (STB_LOCAL)
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
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101abc98)
Location: kernel/time/posix-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_delete
```
**Symbols:**

```
ffff8000101abc98-ffff8000101abd24: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f58c0)
Location: kernel/time/posix-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_delete
```
**Symbols:**

```
c03f58c0-c03f5948: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020ddd0)
Location: kernel/time/posix-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_delete
```
**Symbols:**

```
c00000000020ddd0-c00000000020de9c: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe000135920)
Location: kernel/time/posix-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:__se_sys_timer_settime
```
**Symbols:**

```
ffffffe000135920-ffffffe000135982: timer_wait_running (STB_LOCAL)
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
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81138990)
Location: kernel/time/posix-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
```
**Symbols:**

```
ffffffff81138990-ffffffff811389e3: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112b3e0)
Location: kernel/time/posix-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
```
**Symbols:**

```
ffffffff8112b3e0-ffffffff8112b433: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811366b0)
Location: kernel/time/posix-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
```
**Symbols:**

```
ffffffff811366b0-ffffffff81136703: timer_wait_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct k_itimer *timer_wait_running(struct k_itimer *timer, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81143140)
Location: kernel/time/posix-timers.c:819
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
```
**Symbols:**

```
ffffffff81143140-ffffffff8114319f: timer_wait_running (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
