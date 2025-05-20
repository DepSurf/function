# Function: <code>timespec64_add_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct timespec timespec64_add_safe(const struct timespec lhs, const struct timespec rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f2260)
Location: kernel/time/time.c:778
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff810f2260-ffffffff810f22bc: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timespec timespec64_add_safe(const struct timespec lhs, const struct timespec rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f93e0)
Location: kernel/time/time.c:778
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff810f93e0-ffffffff810f943c: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct timespec timespec64_add_safe(const struct timespec lhs, const struct timespec rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fb8f0)
Location: kernel/time/time.c:878
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff810fb8f0-ffffffff810fb955: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct timespec timespec64_add_safe(const struct timespec lhs, const struct timespec rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811061e0)
Location: kernel/time/time.c:827
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff811061e0-ffffffff81106245: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81111720)
Location: kernel/time/time.c:839
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81111720-ffffffff8111177f: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ce30)
Location: kernel/time/time.c:777
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8111ce30-ffffffff8111ce8f: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81127ad0)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81127ad0-ffffffff81127b2f: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81133a70)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81133a70-ffffffff81133acf: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81142d00)
Location: kernel/time/time.c:765
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81142d00-ffffffff81142d5f: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113ef10)
Location: kernel/time/time.c:765
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff8113ef10-ffffffff8113ef6f: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81140140)
Location: kernel/time/time.c:765
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff81140140-ffffffff8114019f: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811635d0)
Location: kernel/time/time.c:765
Inline: False
Direct callers:
  - fs/select.c:__x64_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x64_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/eventpoll.c:__x64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff811635d0-ffffffff8116362f: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81196630)
Location: kernel/time/time.c:765
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff81196630-ffffffff811966a9: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d4660)
Location: kernel/time/time.c:765
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff811d4660-ffffffff811d46d9: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e8950)
Location: kernel/time/time.c:765
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff811e8950-ffffffff811e89c9: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fe680)
Location: kernel/time/time.c:846
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff811fe680-ffffffff811fe6f9: timespec64_add_safe (STB_GLOBAL)
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
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019c140)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffff80001019c140-ffff80001019c1ec: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e5d78)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
c03e5d78-c03e5e78: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fbbf0)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
c0000000001fbbf0-c0000000001fbc70: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012ac6e)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_set_mstimeout
```
**Symbols:**

```
ffffffe00012ac6e-ffffffe00012acf4: timespec64_add_safe (STB_GLOBAL)
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
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112c220)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8112c220-ffffffff8112c27f: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ea90)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8111ea90-ffffffff8111eaef: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129f40)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81129f40-ffffffff81129f9f: timespec64_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct timespec64 timespec64_add_safe(const struct timespec64 lhs, const struct timespec64 rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81136590)
Location: kernel/time/time.c:855
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81136590-ffffffff811365ef: timespec64_add_safe (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec lhs</code> ➡️ <code>const struct timespec64 lhs</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct timespec rhs</code> ➡️ <code>const struct timespec64 rhs</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct timespec</code> ➡️ <code>struct timespec64</code>
</li>
</ul>
</details>
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
