# Function: <code>proc_alloc_inum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f0e0)
Location: fs/proc/generic.c:193
Inline: False
Direct callers:
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff8127f0e0-ffffffff8127f1bf: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac120)
Location: fs/proc/generic.c:197
Inline: False
Direct callers:
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff812ac120-ffffffff812ac1ff: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c1a10)
Location: fs/proc/generic.c:197
Inline: False
Direct callers:
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff812c1a10-ffffffff812c1aef: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ceb36)
Location: fs/proc/generic.c:197
Inline: True
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff812cf190-ffffffff812cf1c5: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3316)
Location: fs/proc/generic.c:199
Inline: True
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff812f3900-ffffffff812f3935: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320615)
Location: fs/proc/generic.c:204
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff813204e0-ffffffff81320515: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337705)
Location: fs/proc/generic.c:204
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff813375d0-ffffffff81337605: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135f845)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff8135f710-ffffffff8135f745: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377aa5)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff81377970-ffffffff813779a5: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0955)
Location: fs/proc/generic.c:207
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:clone_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff813c07e0-ffffffff813c0818: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d27b8)
Location: fs/proc/generic.c:207
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:clone_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff813d2630-ffffffff813d2668: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d95be)
Location: fs/proc/generic.c:202
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff813d9430-ffffffff813d9468: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142acee)
Location: fs/proc/generic.c:202
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff8142ab60-ffffffff8142ab98: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4349)
Location: fs/proc/generic.c:202
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff814a4160-ffffffff814a41a4: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815397a9)
Location: fs/proc/generic.c:202
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff81539580-ffffffff815395c4: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571a29)
Location: fs/proc/generic.c:201
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff815717c0-ffffffff81571804: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa3d9)
Location: fs/proc/generic.c:201
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff815aa170-ffffffff815aa1b4: proc_alloc_inum (STB_GLOBAL)
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
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff80001044388c)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffff800010443650-ffff8000104436a0: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608af4)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
c0608964-c06089a8: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000558f38)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
c000000000558d00-c000000000558d6c: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da406)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffe0002da01e-ffffffe0002da06a: proc_alloc_inum (STB_GLOBAL)
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
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81370085)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff8136ff50-ffffffff8136ff85: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360b15)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff813609e0-ffffffff81360a15: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136db55)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff8136da20-ffffffff8136da55: proc_alloc_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int proc_alloc_inum(unsigned int *inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381485)
Location: fs/proc/generic.c:205
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/proc/self.c:proc_self_init
  - fs/proc/thread_self.c:proc_thread_self_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_init
```
**Symbols:**

```
ffffffff81381350-ffffffff81381385: proc_alloc_inum (STB_GLOBAL)
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
