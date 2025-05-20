# Function: <code>__put_user_ns</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81130852)
Location: kernel/user_namespace.c:200
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/super.c:destroy_super
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8112fe30-ffffffff8112fe53: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81131e9e)
Location: kernel/user_namespace.c:201
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/super.c:destroy_super
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81131440-ffffffff81131463: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113ecbe)
Location: kernel/user_namespace.c:215
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8113e030-ffffffff8113e053: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8114cf05)
Location: kernel/user_namespace.c:215
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8114c9d0-ffffffff8114c9f3: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81159b25)
Location: kernel/user_namespace.c:215
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff811595f0-ffffffff81159613: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116627e)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81165d50-ffffffff81165d73: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8117213e)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81171c10-ffffffff81171c33: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811846bf)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/nsproxy.c:validate_nsset
  - kernel/cred.c:put_cred_rcu
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81184590-ffffffff811845b3: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8118171d)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/nsproxy.c:validate_nsset
  - kernel/cred.c:put_cred_rcu
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff811812f0-ffffffff81181313: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81182858)
Location: kernel/user_namespace.c:210
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/nsproxy.c:validate_nsset
  - kernel/cred.c:put_cred_rcu
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81182410-ffffffff81182433: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811aa828)
Location: kernel/user_namespace.c:226
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/nsproxy.c:validate_nsset
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:put_ucounts
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff811aa3e0-ffffffff811aa403: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811dbe75)
Location: kernel/user_namespace.c:231
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/nsproxy.c:validate_nsset
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:put_ucounts
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:free_ipc
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff811db9c0-ffffffff811db9ef: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812216c5)
Location: kernel/user_namespace.c:231
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/nsproxy.c:validate_nsset
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:put_ucounts
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:free_ipc
  - security/apparmor/notify.c:build_unotif
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff812211c0-ffffffff812211ef: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81237b75)
Location: kernel/user_namespace.c:231
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/nsproxy.c:validate_nsset
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:put_ucounts
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:free_ipc
  - security/apparmor/notify.c:build_v3_unotif
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81237670-ffffffff8123769f: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812513b9)
Location: kernel/user_namespace.c:234
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/nsproxy.c:validate_nsset
  - kernel/cred.c:put_cred_rcu
  - kernel/ucount.c:put_ucounts
  - kernel/time/namespace.c:free_time_ns
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/super.c:destroy_super_work
  - fs/exec.c:would_dump
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - fs/fuse/inode.c:delayed_release
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:free_ipc
  - security/apparmor/notify.c:build_v3_unotif
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81250ea0-ffffffff81250ecf: __put_user_ns (STB_GLOBAL)
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
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e6804)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffff8000101e5868-ffff8000101e58a0: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0426848)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
c0426224-c0426258: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0000000002566f0)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
c000000000255e90-c000000000255edc: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015bafc)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffe00015b4ca-ffffffe00015b500: __put_user_ns (STB_GLOBAL)
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
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116a75e)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8116a230-ffffffff8116a253: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115d95e)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8115d430-ffffffff8115d453: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116852e)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81168000-ffffffff81168023: __put_user_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __put_user_ns(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81175c1e)
Location: kernel/user_namespace.c:209
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - kernel/fork.c:__mmdrop
  - kernel/cred.c:put_cred_rcu
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/namespace.c:free_cgroup_ns
  - kernel/utsname.c:free_uts_ns
  - kernel/pid_namespace.c:delayed_free_pidns
  - fs/exec.c:would_dump
  - fs/namespace.c:free_mnt_ns
  - fs/fs_context.c:put_fs_context
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/sysfs/mount.c:sysfs_init_fs_context
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/namespace.c:copy_ipcs
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff811756a0-ffffffff811756c3: __put_user_ns (STB_GLOBAL)
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
