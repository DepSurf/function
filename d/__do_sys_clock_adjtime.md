# Function: <code>__do_sys_clock_adjtime</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111e740)
Location: kernel/time/posix-timers.c:1084
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8111e740-ffffffff8111e84b: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81129f10)
Location: kernel/time/posix-timers.c:1050
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81129f10-ffffffff8112a01b: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81136a10)
Location: kernel/time/posix-timers.c:1055
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81136a10-ffffffff81136aa7: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81142ac0)
Location: kernel/time/posix-timers.c:1090
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81142ac0-ffffffff81142b57: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81151b90)
Location: kernel/time/posix-timers.c:1112
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81151b90-ffffffff81151c9c: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114de10)
Location: kernel/time/posix-timers.c:1112
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8114de10-ffffffff8114df1c: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114e900)
Location: kernel/time/posix-timers.c:1112
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8114e900-ffffffff8114ea0c: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811729b0)
Location: kernel/time/posix-timers.c:1112
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811729b0-ffffffff81172add: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a7ec0)
Location: kernel/time/posix-timers.c:1121
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811a7ec0-ffffffff811a7ffd: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e7bc0)
Location: kernel/time/posix-timers.c:1121
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811e7bc0-ffffffff811e7cfd: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811fc1b0)
Location: kernel/time/posix-timers.c:1162
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811fc1b0-ffffffff811fc2ed: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff812123a0)
Location: kernel/time/posix-timers.c:1162
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff812123a0-ffffffff812124dd: __do_sys_clock_adjtime (STB_LOCAL)
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101acbe8)
Location: kernel/time/posix-timers.c:1090
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_sys_clock_adjtime
```
**Symbols:**

```
ffff8000101acbe8-ffff8000101acda0: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f745c)
Location: kernel/time/posix-timers.c:1090
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_clock_adjtime
```
**Symbols:**

```
c03f745c-c03f757c: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c000000000210af0)
Location: kernel/time/posix-timers.c:1090
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_clock_adjtime
```
**Symbols:**

```
c000000000210af0-c000000000210bb0: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe000136c20)
Location: kernel/time/posix-timers.c:1090
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_clock_adjtime
```
**Symbols:**

```
ffffffe000136c20-ffffffe000136c7c: __do_sys_clock_adjtime (STB_LOCAL)
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
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8113b270)
Location: kernel/time/posix-timers.c:1090
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8113b270-ffffffff8113b307: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112dcb0)
Location: kernel/time/posix-timers.c:1090
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8112dcb0-ffffffff8112dd47: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81138f90)
Location: kernel/time/posix-timers.c:1090
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81138f90-ffffffff81139027: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *utx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81145a30)
Location: kernel/time/posix-timers.c:1090
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x64_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81145a30-ffffffff81145ac7: __do_sys_clock_adjtime (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timex *utx</code> ➡️ <code>struct __kernel_timex *utx</code>
</li>
</ul>
</details>
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
