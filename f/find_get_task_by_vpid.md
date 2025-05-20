# Function: <code>find_get_task_by_vpid</code>

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
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b1070)
Location: kernel/pid.c:346
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810b1070-ffffffff810b1089: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ba1b0)
Location: kernel/pid.c:355
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810ba1b0-ffffffff810ba1c9: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c00c0)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810c00c0-ffffffff810c00df: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c6490)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810c6490-ffffffff810c64af: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ce350)
Location: kernel/pid.c:424
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - kernel/taskstats.c:fill_stats_for_pid
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810ce350-ffffffff810ce3f0: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8e10)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - kernel/taskstats.c:fill_stats_for_pid
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810c8e10-ffffffff810c8ebb: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca8b0)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - kernel/taskstats.c:cmd_attr_pid
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810ca8b0-ffffffff810ca95b: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd800)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/ptrace.c:__x64_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/taskstats.c:cmd_attr_pid
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810dd800-ffffffff810dd8ab: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f7160)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/taskstats.c:cmd_attr_pid
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810f7160-ffffffff810f7220: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811198d0)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/taskstats.c:cmd_attr_pid
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff811198d0-ffffffff81119990: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126db0)
Location: kernel/pid.c:428
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/taskstats.c:cmd_attr_pid
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff81126db0-ffffffff81126e70: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81131390)
Location: kernel/pid.c:428
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/taskstats.c:cmd_attr_pid
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff81131390-ffffffff81131450: find_get_task_by_vpid (STB_GLOBAL)
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
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124ce8)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__arm64_compat_sys_ptrace
  - kernel/ptrace.c:__arm64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - kernel/taskstats.c:taskstats_user_cmd
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffff800010124ce8-ffff800010124d28: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377c80)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - kernel/taskstats.c:taskstats_user_cmd
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
c0377c80-c0377cb0: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016eb10)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_compat_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - kernel/taskstats.c:taskstats_user_cmd
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
c00000000016eb10-c00000000016eb5c: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dcc70)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - kernel/taskstats.c:taskstats_user_cmd
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffe0000dcc70-ffffffe0000dcca6: find_get_task_by_vpid (STB_GLOBAL)
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
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c0810)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810c0810-ffffffff810c082f: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810af010)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810af010-ffffffff810af02f: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfd60)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810bfd60-ffffffff810bfd7f: find_get_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *find_get_task_by_vpid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8170)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/futex.c:attach_to_pi_owner
  - security/yama/yama_lsm.c:yama_task_prctl
```
**Symbols:**

```
ffffffff810c8170-ffffffff810c81a9: find_get_task_by_vpid (STB_GLOBAL)
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
