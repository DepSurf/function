# Function: <code>do_timerfd_settime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81258750)
Location: fs/timerfd.c:418
Inline: False
Direct callers:
  - fs/timerfd.c:SyS_timerfd_settime
  - fs/timerfd.c:compat_SyS_timerfd_settime
```
**Symbols:**

```
ffffffff81258750-ffffffff81258b1f: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81281050)
Location: fs/timerfd.c:423
Inline: False
Direct callers:
  - fs/timerfd.c:compat_SyS_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_settime
```
**Symbols:**

```
ffffffff81281050-ffffffff8128146c: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81294b80)
Location: fs/timerfd.c:423
Inline: False
Direct callers:
  - fs/timerfd.c:compat_SyS_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_settime
```
**Symbols:**

```
ffffffff81294b80-ffffffff81294f92: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812a1e10)
Location: fs/timerfd.c:434
Inline: False
Direct callers:
  - fs/timerfd.c:compat_SyS_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_settime
```
**Symbols:**

```
ffffffff812a1e10-ffffffff812a2201: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812c5130)
Location: fs/timerfd.c:435
Inline: False
Direct callers:
  - fs/timerfd.c:compat_SyS_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_settime
```
**Symbols:**

```
ffffffff812c5130-ffffffff812c5527: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812ee4a0)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__x32_compat_sys_timerfd_settime
  - fs/timerfd.c:__ia32_compat_sys_timerfd_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff812ee4a0-ffffffff812ee8e5: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81302e30)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__x32_compat_sys_timerfd_settime
  - fs/timerfd.c:__ia32_compat_sys_timerfd_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81302e30-ffffffff81303275: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (ffffffff81324070)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81324070-ffffffff81324485: do_timerfd_settime.part.0 (STB_LOCAL)
ffffffff81324490-ffffffff813244d0: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (ffffffff81336dd0)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81336dd0-ffffffff813371e5: do_timerfd_settime.part.0 (STB_LOCAL)
ffffffff813371f0-ffffffff81337230: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81370c50)
Location: fs/timerfd.c:438
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81370c50-ffffffff8137115b: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8137e9d0)
Location: fs/timerfd.c:438
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8137e9d0-ffffffff8137eedf: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81385650)
Location: fs/timerfd.c:438
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81385650-ffffffff81385b5f: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (0)
Location: fs/timerfd.c:454
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff813d27d0-ffffffff813d2ca2: do_timerfd_settime (STB_LOCAL)
ffffffff81cc55fb-ffffffff81cc562c: do_timerfd_settime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (0)
Location: fs/timerfd.c:454
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8145b040-ffffffff8145b539: do_timerfd_settime (STB_LOCAL)
ffffffff81e77faa-ffffffff81e77ff9: do_timerfd_settime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (0)
Location: fs/timerfd.c:454
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff814ea650-ffffffff814eab49: do_timerfd_settime (STB_LOCAL)
ffffffff82069f30-ffffffff82069f7f: do_timerfd_settime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (0)
Location: fs/timerfd.c:454
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff815213f0-ffffffff815218ec: do_timerfd_settime (STB_LOCAL)
ffffffff820e9ebe-ffffffff820e9f0d: do_timerfd_settime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (0)
Location: fs/timerfd.c:454
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81555a30-ffffffff81555f2c: do_timerfd_settime (STB_LOCAL)
ffffffff821c69ab-ffffffff821c69fa: do_timerfd_settime.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (ffff8000103f4b98)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__arm64_sys_timerfd_settime32
  - fs/timerfd.c:__arm64_sys_timerfd_settime
```
**Symbols:**

```
ffff8000103f4b98-ffff8000103f5074: do_timerfd_settime.part.0 (STB_LOCAL)
ffff8000103f5078-ffff8000103f5108: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (c05c9b44)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_settime32
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
c05c9b44-c05c9fb0: do_timerfd_settime.part.0 (STB_LOCAL)
c05c9fb0-c05ca01c: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (c0000000004fcc90)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_settime32
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
c0000000004fcc90-c0000000004fd284: do_timerfd_settime.part.0 (STB_LOCAL)
c0000000004fd290-c0000000004fd2f8: do_timerfd_settime (STB_LOCAL)
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
In fs/timerfd.c (ffffffe0002a5de4)
Location: fs/timerfd.c:435
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (ffffffff8132f3b0)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8132f3b0-ffffffff8132f7c5: do_timerfd_settime.part.0 (STB_LOCAL)
ffffffff8132f7d0-ffffffff8132f810: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (ffffffff8131ffe0)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8131ffe0-ffffffff813203e9: do_timerfd_settime.part.0 (STB_LOCAL)
ffffffff813203f0-ffffffff81320430: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (ffffffff8132ce80)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8132ce80-ffffffff8132d295: do_timerfd_settime.part.0 (STB_LOCAL)
ffffffff8132d2a0-ffffffff8132d2e0: do_timerfd_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/timerfd.c (ffffffff8133f990)
Location: fs/timerfd.c:435
Inline: True
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8133f990-ffffffff8133fd8d: do_timerfd_settime.part.0 (STB_LOCAL)
ffffffff8133fd90-ffffffff8133fdd0: do_timerfd_settime (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct itimerspec *new</code> ➡️ <code>const struct itimerspec64 *new</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct itimerspec *old</code> ➡️ <code>struct itimerspec64 *old</code>
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
