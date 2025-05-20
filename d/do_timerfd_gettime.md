# Function: <code>do_timerfd_gettime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812585d0)
Location: fs/timerfd.c:482
Inline: False
Direct callers:
  - fs/timerfd.c:SyS_timerfd_gettime
  - fs/timerfd.c:compat_SyS_timerfd_gettime
```
**Symbols:**

```
ffffffff812585d0-ffffffff8125874c: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81280ed0)
Location: fs/timerfd.c:492
Inline: False
Direct callers:
  - fs/timerfd.c:compat_SyS_timerfd_gettime
  - fs/timerfd.c:SyS_timerfd_gettime
```
**Symbols:**

```
ffffffff81280ed0-ffffffff81281044: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81294a00)
Location: fs/timerfd.c:492
Inline: False
Direct callers:
  - fs/timerfd.c:compat_SyS_timerfd_gettime
  - fs/timerfd.c:SyS_timerfd_gettime
```
**Symbols:**

```
ffffffff81294a00-ffffffff81294b76: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812a1c90)
Location: fs/timerfd.c:502
Inline: False
Direct callers:
  - fs/timerfd.c:compat_SyS_timerfd_gettime
  - fs/timerfd.c:SyS_timerfd_gettime
```
**Symbols:**

```
ffffffff812a1c90-ffffffff812a1e02: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812c4fb0)
Location: fs/timerfd.c:503
Inline: False
Direct callers:
  - fs/timerfd.c:compat_SyS_timerfd_gettime
  - fs/timerfd.c:SyS_timerfd_gettime
```
**Symbols:**

```
ffffffff812c4fb0-ffffffff812c5128: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812ee070)
Location: fs/timerfd.c:503
Inline: False
Direct callers:
  - fs/timerfd.c:__x32_compat_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_compat_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff812ee070-ffffffff812ee1d8: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81302b00)
Location: fs/timerfd.c:503
Inline: False
Direct callers:
  - fs/timerfd.c:__x32_compat_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_compat_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff81302b00-ffffffff81302c68: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81324750)
Location: fs/timerfd.c:503
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff81324750-ffffffff813248b9: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813374b0)
Location: fs/timerfd.c:507
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff813374b0-ffffffff81337619: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813707c0)
Location: fs/timerfd.c:510
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff813707c0-ffffffff81370989: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8137e530)
Location: fs/timerfd.c:510
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff8137e530-ffffffff8137e704: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813851b0)
Location: fs/timerfd.c:510
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff813851b0-ffffffff81385384: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813d2430)
Location: fs/timerfd.c:526
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff813d2430-ffffffff813d2604: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8145bfd0)
Location: fs/timerfd.c:526
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff8145bfd0-ffffffff8145c1a2: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff814eb6a0)
Location: fs/timerfd.c:526
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff814eb6a0-ffffffff814eb872: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81522440)
Location: fs/timerfd.c:526
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff81522440-ffffffff81522615: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81556a60)
Location: fs/timerfd.c:526
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff81556a60-ffffffff81556c35: do_timerfd_gettime (STB_LOCAL)
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
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffff8000103f48d0)
Location: fs/timerfd.c:507
Inline: False
Direct callers:
  - fs/timerfd.c:__arm64_sys_timerfd_gettime32
  - fs/timerfd.c:__arm64_sys_timerfd_gettime
```
**Symbols:**

```
ffff8000103f48d0-ffff8000103f4a94: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (c05c9984)
Location: fs/timerfd.c:507
Inline: False
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime32
  - fs/timerfd.c:__se_sys_timerfd_gettime
```
**Symbols:**

```
c05c9984-c05c9b44: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (c0000000004fd4c0)
Location: fs/timerfd.c:507
Inline: False
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime32
  - fs/timerfd.c:__se_sys_timerfd_gettime
```
**Symbols:**

```
c0000000004fd4c0-c0000000004fd6f8: do_timerfd_gettime (STB_LOCAL)
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
In fs/timerfd.c (ffffffe0002a6224)
Location: fs/timerfd.c:507
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime
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
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132fa90)
Location: fs/timerfd.c:507
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff8132fa90-ffffffff8132fbf9: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813206b0)
Location: fs/timerfd.c:507
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff813206b0-ffffffff81320813: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132d560)
Location: fs/timerfd.c:507
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff8132d560-ffffffff8132d6c9: do_timerfd_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8133f230)
Location: fs/timerfd.c:507
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
```
**Symbols:**

```
ffffffff8133f230-ffffffff8133f390: do_timerfd_gettime (STB_LOCAL)
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
<code>struct itimerspec *t</code> ➡️ <code>struct itimerspec64 *t</code>
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
