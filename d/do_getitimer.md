# Function: <code>do_getitimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff810f03e0)
Location: kernel/time/itimer.c:79
Inline: False
Direct callers:
  - kernel/time/itimer.c:SyS_getitimer
  - kernel/compat.c:compat_SyS_getitimer
```
**Symbols:**

```
ffffffff810f03e0-ffffffff810f04ae: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff810f7410)
Location: kernel/time/itimer.c:79
Inline: False
Direct callers:
  - kernel/time/itimer.c:SyS_getitimer
  - kernel/compat.c:compat_SyS_getitimer
```
**Symbols:**

```
ffffffff810f7410-ffffffff810f74de: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81109ad0)
Location: kernel/time/itimer.c:79
Inline: False
Direct callers:
  - kernel/time/itimer.c:SyS_getitimer
  - kernel/compat.c:compat_SyS_getitimer
```
**Symbols:**

```
ffffffff81109ad0-ffffffff81109b9e: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8110b8b0)
Location: kernel/time/itimer.c:82
Inline: False
Direct callers:
  - kernel/time/itimer.c:compat_SyS_getitimer
  - kernel/time/itimer.c:SyS_getitimer
```
**Symbols:**

```
ffffffff8110b8b0-ffffffff8110b98c: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81116b00)
Location: kernel/time/itimer.c:83
Inline: False
Direct callers:
  - kernel/time/itimer.c:compat_SyS_getitimer
  - kernel/time/itimer.c:SyS_getitimer
```
**Symbols:**

```
ffffffff81116b00-ffffffff81116bdc: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811233a0)
Location: kernel/time/itimer.c:83
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff811233a0-ffffffff8112346e: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8112ea70)
Location: kernel/time/itimer.c:81
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff8112ea70-ffffffff8112eb3e: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81139500)
Location: kernel/time/itimer.c:81
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff81139500-ffffffff811395c5: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81145180)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff81145180-ffffffff81145245: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerspec64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81155360)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff81155360-ffffffff81155469: do_getitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerspec64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811515d0)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff811515d0-ffffffff811516d9: do_getitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerspec64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81152a40)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff81152a40-ffffffff81152b49: do_getitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerspec64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81177050)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x64_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff81177050-ffffffff81177159: do_getitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerspec64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811ab4a0)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff811ab4a0-ffffffff811ab5a7: do_getitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerspec64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811eb6e0)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff811eb6e0-ffffffff811eb7e7: do_getitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerspec64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811ffe30)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff811ffe30-ffffffff811fff1e: do_getitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerspec64 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff812162d0)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff812162d0-ffffffff812163be: do_getitimer (STB_LOCAL)
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
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffff8000101afa20)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__arm64_compat_sys_getitimer
  - kernel/time/itimer.c:__arm64_sys_getitimer
```
**Symbols:**

```
ffff8000101afa20-ffff8000101afb50: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (c03fa784)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__se_sys_getitimer
```
**Symbols:**

```
c03fa784-c03fa8a0: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (c000000000214290)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__se_compat_sys_getitimer
  - kernel/time/itimer.c:__se_sys_getitimer
```
**Symbols:**

```
c000000000214290-c00000000021441c: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffe000138e76)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__se_sys_getitimer
```
**Symbols:**

```
ffffffe000138e76-ffffffe000138f80: do_getitimer (STB_GLOBAL)
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
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113d930)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff8113d930-ffffffff8113d9f5: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81130470)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff81130470-ffffffff8113052f: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113b650)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff8113b650-ffffffff8113b715: do_getitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81148120)
Location: kernel/time/itimer.c:76
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
```
**Symbols:**

```
ffffffff81148120-ffffffff811481dc: do_getitimer (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct itimerval *value</code> ➡️ <code>struct itimerspec64 *value</code>
</li>
</ul>
</details>
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
