# Function: <code>do_clock_adjtime</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811369a0)
Location: kernel/time/posix-timers.c:1043
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811369a0-ffffffff81136a05: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81142a50)
Location: kernel/time/posix-timers.c:1078
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81142a50-ffffffff81142ab5: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811521f6)
Location: kernel/time/posix-timers.c:1100
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811524b0-ffffffff81152515: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114e476)
Location: kernel/time/posix-timers.c:1100
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8114e730-ffffffff8114e795: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114ef68)
Location: kernel/time/posix-timers.c:1100
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8114fbd0-ffffffff8114fc35: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811730f8)
Location: kernel/time/posix-timers.c:1100
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81173db0-ffffffff81173e4a: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a8695)
Location: kernel/time/posix-timers.c:1109
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811a8a10-ffffffff811a8abd: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e8445)
Location: kernel/time/posix-timers.c:1109
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811e8820-ffffffff811e88cd: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811fca35)
Location: kernel/time/posix-timers.c:1150
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811fce30-ffffffff811fcedd: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81212c25)
Location: kernel/time/posix-timers.c:1150
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81213020-ffffffff812130cd: do_clock_adjtime (STB_GLOBAL)
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101acb40)
Location: kernel/time/posix-timers.c:1078
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffff8000101acb40-ffff8000101acbe8: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f73cc)
Location: kernel/time/posix-timers.c:1078
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
c03f73cc-c03f745c: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c000000000210a20)
Location: kernel/time/posix-timers.c:1078
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
c000000000210a20-c000000000210af0: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe000136b94)
Location: kernel/time/posix-timers.c:1078
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffe000136b94-ffffffe000136c20: do_clock_adjtime (STB_GLOBAL)
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8113b200)
Location: kernel/time/posix-timers.c:1078
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8113b200-ffffffff8113b265: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112dc40)
Location: kernel/time/posix-timers.c:1078
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8112dc40-ffffffff8112dca5: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81138f20)
Location: kernel/time/posix-timers.c:1078
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81138f20-ffffffff81138f85: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex *ktx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811459c0)
Location: kernel/time/posix-timers.c:1078
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811459c0-ffffffff81145a25: do_clock_adjtime (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
