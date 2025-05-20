# Function: <code>do_setitimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff810f05b0)
Location: kernel/time/itimer.c:190
Inline: False
Direct callers:
  - kernel/time/itimer.c:alarm_setitimer
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810f05b0-ffffffff810f07de: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff810f75e0)
Location: kernel/time/itimer.c:190
Inline: False
Direct callers:
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:alarm_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff810f75e0-ffffffff810f7807: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81109ca0)
Location: kernel/time/itimer.c:190
Inline: False
Direct callers:
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_alarm
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81109ca0-ffffffff81109ec7: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8110bb20)
Location: kernel/time/itimer.c:190
Inline: False
Direct callers:
  - kernel/time/itimer.c:compat_SyS_setitimer
  - kernel/time/itimer.c:compat_SyS_setitimer
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_alarm
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8110bb20-ffffffff8110bd57: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81116d70)
Location: kernel/time/itimer.c:191
Inline: False
Direct callers:
  - kernel/time/itimer.c:compat_SyS_setitimer
  - kernel/time/itimer.c:compat_SyS_setitimer
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_alarm
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81116d70-ffffffff81116faa: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811236d0)
Location: kernel/time/itimer.c:191
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:alarm_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff811236d0-ffffffff81123912: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8112eda0)
Location: kernel/time/itimer.c:190
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:alarm_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8112eda0-ffffffff8112efe2: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81139830)
Location: kernel/time/itimer.c:190
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:alarm_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81139830-ffffffff81139a58: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811454b0)
Location: kernel/time/itimer.c:185
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:alarm_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff811454b0-ffffffff811456da: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerspec64 *value, struct itimerspec64 *ovalue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81154b00)
Location: kernel/time/itimer.c:210
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
```
**Symbols:**

```
ffffffff81154b00-ffffffff81154d1c: do_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerspec64 *value, struct itimerspec64 *ovalue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81150d80)
Location: kernel/time/itimer.c:206
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
```
**Symbols:**

```
ffffffff81150d80-ffffffff81150f8a: do_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerspec64 *value, struct itimerspec64 *ovalue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811521b0)
Location: kernel/time/itimer.c:206
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
```
**Symbols:**

```
ffffffff811521b0-ffffffff811523ba: do_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerspec64 *value, struct itimerspec64 *ovalue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81176780)
Location: kernel/time/itimer.c:206
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x64_compat_sys_setitimer
  - kernel/time/itimer.c:__x64_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
```
**Symbols:**

```
ffffffff81176780-ffffffff81176987: do_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerspec64 *value, struct itimerspec64 *ovalue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811abbf0)
Location: kernel/time/itimer.c:206
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
```
**Symbols:**

```
ffffffff811abbf0-ffffffff811abe14: do_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerspec64 *value, struct itimerspec64 *ovalue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811ebe90)
Location: kernel/time/itimer.c:206
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
```
**Symbols:**

```
ffffffff811ebe90-ffffffff811ec0b4: do_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerspec64 *value, struct itimerspec64 *ovalue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff812005c0)
Location: kernel/time/itimer.c:206
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
```
**Symbols:**

```
ffffffff812005c0-ffffffff812007e7: do_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerspec64 *value, struct itimerspec64 *ovalue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81216a60)
Location: kernel/time/itimer.c:206
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
  - kernel/time/itimer.c:clear_itimer
```
**Symbols:**

```
ffffffff81216a60-ffffffff81216c87: do_setitimer (STB_LOCAL)
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
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffff8000101afd30)
Location: kernel/time/itimer.c:185
Inline: False
Direct callers:
  - kernel/time/itimer.c:__arm64_compat_sys_setitimer
  - kernel/time/itimer.c:__arm64_compat_sys_setitimer
  - kernel/time/itimer.c:__arm64_sys_setitimer
  - kernel/time/itimer.c:__arm64_sys_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffff8000101afd30-ffff8000101b0010: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (c03faa34)
Location: kernel/time/itimer.c:185
Inline: False
Direct callers:
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
c03faa34-c03facf0: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (c000000000214680)
Location: kernel/time/itimer.c:185
Inline: False
Direct callers:
  - kernel/time/itimer.c:__se_compat_sys_setitimer
  - kernel/time/itimer.c:__se_compat_sys_setitimer
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_alarm
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
c000000000214680-c000000000214a30: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffe000139064)
Location: kernel/time/itimer.c:185
Inline: False
Direct callers:
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffe000139064-ffffffe0001392aa: do_setitimer (STB_GLOBAL)
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
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113dc60)
Location: kernel/time/itimer.c:185
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:alarm_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8113dc60-ffffffff8113de8a: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81130790)
Location: kernel/time/itimer.c:185
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:alarm_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81130790-ffffffff811309ae: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113b980)
Location: kernel/time/itimer.c:185
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:alarm_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff8113b980-ffffffff8113bbaa: do_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_setitimer(int which, struct itimerval *value, struct itimerval *ovalue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81148450)
Location: kernel/time/itimer.c:185
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:alarm_setitimer
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81148450-ffffffff81148681: do_setitimer (STB_GLOBAL)
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
<li>
<b>Param type changed. </b>
<code>struct itimerval *ovalue</code> ➡️ <code>struct itimerspec64 *ovalue</code>
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
