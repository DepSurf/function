# Function: <code>get_task_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a2560)
Location: kernel/cred.c:187
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cgroup.c:__cgroup_procs_write
  - fs/proc/array.c:proc_pid_status
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810a2560-ffffffff810a25a9: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a5ca0)
Location: kernel/cred.c:187
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:proc_pid_status
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810a5ca0-ffffffff810a5ce9: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ab900)
Location: kernel/cred.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:proc_pid_status
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810ab900-ffffffff810ab949: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a8500)
Location: kernel/cred.c:188
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - fs/proc/array.c:proc_pid_status
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810a8500-ffffffff810a852b: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810aeca0)
Location: kernel/cred.c:188
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:proc_pid_status
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810aeca0-ffffffff810aeccb: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b5a10)
Location: kernel/cred.c:188
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:proc_pid_status
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810b5a10-ffffffff810b5a3b: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810be850)
Location: kernel/cred.c:189
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:proc_pid_status
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810be850-ffffffff810be87b: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c4850)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810c4850-ffffffff810c4894: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cd900)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810cd900-ffffffff810cd944: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d7560)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810d7560-ffffffff810d75a4: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d2220)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810d2220-ffffffff810d2272: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d3e00)
Location: kernel/cred.c:196
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810d3e00-ffffffff810d3e52: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e6ed0)
Location: kernel/cred.c:196
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810e6ed0-ffffffff810e6f22: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81101170)
Location: kernel/cred.c:196
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff81101170-ffffffff811011c1: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81126280)
Location: kernel/cred.c:196
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81126280-ffffffff811262d1: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81133730)
Location: kernel/cred.c:196
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81133730-ffffffff81133781: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113e6a0)
Location: kernel/cred.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff8113e6a0-ffffffff8113e6f5: get_task_cred (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffff80001012cb90)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffff80001012cb90-ffff80001012cc1c: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c037cf14)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
c037cf14-c037cf7c: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c000000000175a50)
Location: kernel/cred.c:193
Inline: False
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
c000000000175a50-c000000000175aa8: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffe0000e173a)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffe0000e173a-ffffffe0000e1784: get_task_cred (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c7c80)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810c7c80-ffffffff810c7cc4: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b64a0)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810b64a0-ffffffff810b64e4: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c71d0)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810c71d0-ffffffff810c7214: get_task_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct cred *get_task_cred(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cf700)
Location: kernel/cred.c:193
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/cred.c:prepare_kernel_cred
  - fs/proc/array.c:task_state
  - security/apparmor/lsm.c:apparmor_getprocattr
```
**Symbols:**

```
ffffffff810cf700-ffffffff810cf75a: get_task_cred (STB_GLOBAL)
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
