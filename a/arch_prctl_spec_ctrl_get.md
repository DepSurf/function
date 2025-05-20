# Function: <code>arch_prctl_spec_ctrl_get</code>

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
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81043960)
Location: arch/x86/kernel/cpu/bugs.c:625
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81043960-ffffffff810439cd: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810451f0)
Location: arch/x86/kernel/cpu/bugs.c:921
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810451f0-ffffffff810452ac: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047cd0)
Location: arch/x86/kernel/cpu/bugs.c:1131
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81047cd0-ffffffff81047d9c: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048520)
Location: arch/x86/kernel/cpu/bugs.c:1261
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81048520-ffffffff810485ec: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c150)
Location: arch/x86/kernel/cpu/bugs.c:1378
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8104c150-ffffffff8104c252: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b670)
Location: arch/x86/kernel/cpu/bugs.c:1386
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
```
**Symbols:**

```
ffffffff8104b670-ffffffff8104b77b: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d320)
Location: arch/x86/kernel/cpu/bugs.c:1386
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
```
**Symbols:**

```
ffffffff8104d320-ffffffff8104d42c: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054a50)
Location: arch/x86/kernel/cpu/bugs.c:1539
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
```
**Symbols:**

```
ffffffff81054a50-ffffffff81054b83: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060790)
Location: arch/x86/kernel/cpu/bugs.c:2041
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
```
**Symbols:**

```
ffffffff81060790-ffffffff81060920: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f000)
Location: arch/x86/kernel/cpu/bugs.c:2092
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
```
**Symbols:**

```
ffffffff8106f000-ffffffff8106f198: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810708d0)
Location: arch/x86/kernel/cpu/bugs.c:2203
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
```
**Symbols:**

```
ffffffff810708d0-ffffffff81070a3a: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810781b0)
Location: arch/x86/kernel/cpu/bugs.c:2345
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
```
**Symbols:**

```
ffffffff810781b0-ffffffff81078355: arch_prctl_spec_ctrl_get (STB_GLOBAL)
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
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ssbd.c (ffff8000100ac128)
Location: arch/arm64/kernel/ssbd.c:121
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffff8000100ac128-ffff8000100ac1d0: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *t, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036e308)
Location: kernel/sys.c:2266
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c036e308-c036e324: arch_prctl_spec_ctrl_get (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *t, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c0000000001616e0)
Location: kernel/sys.c:2266
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c0000000001616e0-c0000000001616f0: arch_prctl_spec_ctrl_get (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *t, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d49a4)
Location: kernel/sys.c:2266
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffe0000d49a4-ffffffe0000d49c0: arch_prctl_spec_ctrl_get (STB_WEAK)
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
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048690)
Location: arch/x86/kernel/cpu/bugs.c:1261
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81048690-ffffffff8104875c: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810379f0)
Location: arch/x86/kernel/cpu/bugs.c:1261
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810379f0-ffffffff81037abc: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810484d0)
Location: arch/x86/kernel/cpu/bugs.c:1261
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810484d0-ffffffff8104859c: arch_prctl_spec_ctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct *task, long unsigned int which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810498e0)
Location: arch/x86/kernel/cpu/bugs.c:1261
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810498e0-ffffffff810499ac: arch_prctl_spec_ctrl_get (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
</ul>
</details>
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
