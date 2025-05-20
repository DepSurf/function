# Function: <code>security_task_getscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e740)
Location: security/security.c:977
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:SyS_sched_rr_get_interval
```
**Symbols:**

```
ffffffff8133e740-ffffffff8133e783: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373d50)
Location: security/security.c:1001
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
```
**Symbols:**

```
ffffffff81373d50-ffffffff81373d93: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a680)
Location: security/security.c:1022
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff8138a680-ffffffff8138a6c3: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139fbd0)
Location: security/security.c:1665
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff8139fbd0-ffffffff8139fc13: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5810)
Location: security/security.c:1627
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff813c5810-ffffffff813c5859: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5810)
Location: security/security.c:1131
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff813f5810-ffffffff813f584a: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410e40)
Location: security/security.c:1739
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff81410e40-ffffffff81410e7a: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e660)
Location: security/security.c:1758
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff8143e660-ffffffff8143e6a1: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458080)
Location: security/security.c:1797
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff81458080-ffffffff814580ba: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aaf10)
Location: security/security.c:1993
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff814aaf10-ffffffff814aaf4a: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8510)
Location: security/security.c:2010
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff814c8510-ffffffff814c854a: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ceb50)
Location: security/security.c:2073
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff814ceb50-ffffffff814ceb8a: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527810)
Location: security/security.c:2081
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff81527810-ffffffff8152784a: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc6c0)
Location: security/security.c:2087
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff815bc6c0-ffffffff815bc70d: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668730)
Location: security/security.c:2139
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff81668730-ffffffff8166877d: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0d80)
Location: security/security.c:3521
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff816a0d80-ffffffff816a0dcd: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd750)
Location: security/security.c:3580
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff816dd750-ffffffff816dd79d: security_task_getscheduler (STB_GLOBAL)
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
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543e48)
Location: security/security.c:1797
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__arm64_sys_sched_getattr
  - kernel/sched/core.c:__arm64_sys_sched_getparam
  - kernel/sched/core.c:__arm64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffff800010543e48-ffff800010543e98: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9d98)
Location: security/security.c:1797
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
c06f9d98-c06f9dec: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000698650)
Location: security/security.c:1797
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
c000000000698650-c0000000006986f8: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0170)
Location: security/security.c:1797
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffe0003a0170-ffffffe0003a01ac: security_task_getscheduler (STB_GLOBAL)
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
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450660)
Location: security/security.c:1797
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff81450660-ffffffff8145069a: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814410b0)
Location: security/security.c:1797
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff814410b0-ffffffff814410ea: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c700)
Location: security/security.c:1797
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff8144c700-ffffffff8144c73a: security_task_getscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463ad0)
Location: security/security.c:1797
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - fs/proc/base.c:timerslack_ns_show
```
**Symbols:**

```
ffffffff81463ad0-ffffffff81463b0a: security_task_getscheduler (STB_GLOBAL)
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
