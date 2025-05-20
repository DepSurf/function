# Function: <code>inc_ucount</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ad7c0)
Location: kernel/ucount.c:190
Inline: False
Direct callers:
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810ad7c0-ffffffff810ad9c2: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810aa3a0)
Location: kernel/ucount.c:195
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810aa3a0-ffffffff810aa5aa: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b0c00)
Location: kernel/ucount.c:195
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810b0c00-ffffffff810b0e0a: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b7a00)
Location: kernel/ucount.c:196
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810b7a00-ffffffff810b7c1b: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c0b00)
Location: kernel/ucount.c:196
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810c0b00-ffffffff810c0d10: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c6c00)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810c6c00-ffffffff810c6e07: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810cfcd0)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810cfcd0-ffffffff810cfedb: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d9d60)
Location: kernel/ucount.c:192
Inline: False
Direct callers:
  - kernel/time/namespace.c:clone_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810d9d60-ffffffff810d9def: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d4f10)
Location: kernel/ucount.c:192
Inline: False
Direct callers:
  - kernel/time/namespace.c:clone_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810d4f10-ffffffff810d4fa0: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d6bf0)
Location: kernel/ucount.c:229
Inline: False
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810d6bf0-ffffffff810d6c7f: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ea1f0)
Location: kernel/ucount.c:227
Inline: False
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810ea1f0-ffffffff810ea288: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81104e60)
Location: kernel/ucount.c:233
Inline: False
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81104e60-ffffffff81104f10: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112a790)
Location: kernel/ucount.c:229
Inline: False
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8112a790-ffffffff8112a8d3: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137810)
Location: kernel/ucount.c:229
Inline: False
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81137810-ffffffff81137953: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142a20)
Location: kernel/ucount.c:230
Inline: False
Direct callers:
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81142a20-ffffffff81142b63: inc_ucount (STB_GLOBAL)
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
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffff800010130230)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffff800010130230-ffff800010130340: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c037fa50)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
c037fa50-c037fcc4: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c000000000179750)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
c000000000179750-c000000000179aa0: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffe0000e373c)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffe0000e373c-ffffffe0000e3978: inc_ucount (STB_GLOBAL)
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
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ca050)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810ca050-ffffffff810ca25b: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b8870)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810b8870-ffffffff810b8a6f: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c9580)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810c9580-ffffffff810c978b: inc_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ucounts *inc_ucount(struct user_namespace *ns, kuid_t uid, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d1ae0)
Location: kernel/ucount.c:189
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810d1ae0-ffffffff810d1cca: inc_ucount (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
