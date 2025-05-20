# Function: <code>do_timer_gettime</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81107a50)
Location: kernel/time/posix-timers.c:716
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_gettime
```
**Symbols:**

```
ffffffff81107a50-ffffffff81107b02: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81112bc0)
Location: kernel/time/posix-timers.c:722
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_gettime
```
**Symbols:**

```
ffffffff81112bc0-ffffffff81112c75: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111e680)
Location: kernel/time/posix-timers.c:731
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_gettime
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_gettime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff8111e680-ffffffff8111e735: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81129e50)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_gettime
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_gettime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff81129e50-ffffffff81129f05: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811348d0)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff811348d0-ffffffff81134985: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811408e0)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff811408e0-ffffffff81140995: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114fde0)
Location: kernel/time/posix-timers.c:715
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff8114fde0-ffffffff8114fe95: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114c060)
Location: kernel/time/posix-timers.c:715
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff8114c060-ffffffff8114c115: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d520)
Location: kernel/time/posix-timers.c:715
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff8114d520-ffffffff8114d5d5: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811712d0)
Location: kernel/time/posix-timers.c:715
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff811712d0-ffffffff81171385: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a5a00)
Location: kernel/time/posix-timers.c:715
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff811a5a00-ffffffff811a5ac9: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e54c0)
Location: kernel/time/posix-timers.c:715
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff811e54c0-ffffffff811e5589: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9b20)
Location: kernel/time/posix-timers.c:696
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff811f9b20-ffffffff811f9be9: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120fd10)
Location: kernel/time/posix-timers.c:696
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff8120fd10-ffffffff8120fdd9: do_timer_gettime (STB_LOCAL)
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101abad8)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__arm64_sys_timer_gettime
```
**Symbols:**

```
ffff8000101abad8-ffff8000101abb94: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f5948)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_gettime32
  - kernel/time/posix-timers.c:__se_sys_timer_gettime
```
**Symbols:**

```
c03f5948-c03f5a38: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020ea20)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_gettime32
  - kernel/time/posix-timers.c:__se_sys_timer_gettime
```
**Symbols:**

```
c00000000020ea20-c00000000020eb0c: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe00013662c)
Location: kernel/time/posix-timers.c:695
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_gettime
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
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81139090)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff81139090-ffffffff81139145: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112bae0)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff8112bae0-ffffffff8112bb95: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81136db0)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff81136db0-ffffffff81136e65: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_timer_gettime(timer_t timer_id, struct itimerspec64 *setting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81143840)
Location: kernel/time/posix-timers.c:695
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
```
**Symbols:**

```
ffffffff81143840-ffffffff811438f5: do_timer_gettime (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct itimerspec *setting</code> ➡️ <code>struct itimerspec64 *setting</code>
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
