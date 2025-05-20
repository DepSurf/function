# Function: <code>dec_ucount</code>

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
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ad9d0)
Location: kernel/ucount.c:213
Inline: False
Direct callers:
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810ad9d0-ffffffff810ada67: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810aa5b0)
Location: kernel/ucount.c:218
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810aa5b0-ffffffff810aa604: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b0e10)
Location: kernel/ucount.c:218
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810b0e10-ffffffff810b0e64: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b7c20)
Location: kernel/ucount.c:219
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810b7c20-ffffffff810b7c74: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c0d10)
Location: kernel/ucount.c:219
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810c0d10-ffffffff810c0d69: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c6e10)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810c6e10-ffffffff810c6e59: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810cfee0)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810cfee0-ffffffff810cff29: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d9df0)
Location: kernel/ucount.c:215
Inline: False
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:clone_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810d9df0-ffffffff810d9e3f: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d4fa0)
Location: kernel/ucount.c:215
Inline: False
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:clone_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810d4fa0-ffffffff810d4fef: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d6c80)
Location: kernel/ucount.c:252
Inline: False
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810d6c80-ffffffff810d6cc9: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ea290)
Location: kernel/ucount.c:250
Inline: False
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810ea290-ffffffff810ea2dd: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81104f10)
Location: kernel/ucount.c:256
Inline: False
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81104f10-ffffffff81104f6e: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112a8f0)
Location: kernel/ucount.c:252
Inline: False
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8112a8f0-ffffffff8112a97f: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81137970)
Location: kernel/ucount.c:252
Inline: False
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81137970-ffffffff811379ff: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff81142b80)
Location: kernel/ucount.c:253
Inline: False
Direct callers:
  - kernel/time/namespace.c:free_time_ns
  - kernel/time/namespace.c:copy_time_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:clone_uts_ns
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81142b80-ffffffff81142c0f: dec_ucount (STB_GLOBAL)
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
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffff800010130340)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffff800010130340-ffff8000101303e8: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c037fcc4)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
c037fcc4-c037fd88: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c000000000179aa0)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
c000000000179aa0-c000000000179b18: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffe0000e3978)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffe0000e3978-ffffffe0000e39ea: dec_ucount (STB_GLOBAL)
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
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ca260)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810ca260-ffffffff810ca2a9: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b8a70)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810b8a70-ffffffff810b8ab9: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c9790)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810c9790-ffffffff810c97d9: dec_ucount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dec_ucount(struct ucounts *ucounts, enum ucount_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d1cd0)
Location: kernel/ucount.c:212
Inline: False
Direct callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff810d1cd0-ffffffff810d1d19: dec_ucount (STB_GLOBAL)
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
