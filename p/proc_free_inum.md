# Function: <code>proc_free_inum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f1c0)
Location: fs/proc/generic.c:220
Inline: False
Direct callers:
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - fs/proc/generic.c:pde_put
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff8127f1c0-ffffffff8127f203: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac200)
Location: fs/proc/generic.c:224
Inline: False
Direct callers:
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - fs/proc/generic.c:pde_put
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff812ac200-ffffffff812ac243: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c1af0)
Location: fs/proc/generic.c:224
Inline: False
Direct callers:
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - fs/proc/generic.c:pde_put
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff812c1af0-ffffffff812c1b33: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812cf2d2)
Location: fs/proc/generic.c:210
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_put
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff812cf1d0-ffffffff812cf1ed: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3a43)
Location: fs/proc/generic.c:212
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_put
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff812f3940-ffffffff812f395d: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320716)
Location: fs/proc/generic.c:217
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff81320520-ffffffff8132053d: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8133780c)
Location: fs/proc/generic.c:217
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff81337610-ffffffff8133762d: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135f97a)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff8135f750-ffffffff8135f76d: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377bda)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff813779b0-ffffffff813779cd: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c09df)
Location: fs/proc/generic.c:220
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff813c0820-ffffffff813c083d: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d282f)
Location: fs/proc/generic.c:220
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff813d2670-ffffffff813d268d: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d96e8)
Location: fs/proc/generic.c:215
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff813d9470-ffffffff813d948d: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142ae18)
Location: fs/proc/generic.c:215
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff8142aba0-ffffffff8142abbd: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4470)
Location: fs/proc/generic.c:215
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff814a41b0-ffffffff814a41d5: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815398d0)
Location: fs/proc/generic.c:215
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff815395e0-ffffffff81539605: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571b31)
Location: fs/proc/generic.c:214
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff81571820-ffffffff81571845: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa4e1)
Location: fs/proc/generic.c:214
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff815aa1d0-ffffffff815aa1f5: proc_free_inum (STB_GLOBAL)
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
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443974)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffff8000104436a0-ffff8000104436d8: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608c24)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
c06089a8-c06089d4: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0000000005590a8)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:put_pid_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
c000000000558d70-c000000000558db8: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da4fa)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffe0002da06a-ffffffe0002da0a0: proc_free_inum (STB_GLOBAL)
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
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813701ba)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff8136ff90-ffffffff8136ffad: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360c4a)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff81360a20-ffffffff81360a3d: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136dc8a)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff8136da60-ffffffff8136da7d: proc_free_inum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void proc_free_inum(unsigned int inum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813815c4)
Location: fs/proc/generic.c:218
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
Direct callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:net_ns_net_exit
```
**Symbols:**

```
ffffffff81381390-ffffffff813813ad: proc_free_inum (STB_GLOBAL)
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
