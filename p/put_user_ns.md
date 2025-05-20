# Function: <code>put_user_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a1f37)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup.c (ffffffff81114dba)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/cgroup.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8111db94)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8111ed82)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff8111f58f)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/pid_namespace.c:destroy_pid_namespace
```
```
In fs/super.c (ffffffff8120e884)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - fs/super.c:destroy_super
```
```
In fs/namespace.c (ffffffff8122bd29)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/proc/base.c (ffffffff8127b451)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_setgroups_open
```
```
In fs/fuse/inode.c (ffffffff8131b492)
Location: include/linux/user_namespace.h:59
Inline: True
```
```
In ipc/mqueue.c (ffffffff8132bf5d)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:remove_notification
```
```
In ipc/namespace.c (ffffffff8132ebb4)
Location: include/linux/user_namespace.h:59
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81710e56)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a56f0)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup.c (ffffffff8111b5da)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/cgroup.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81125a64)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81126cd5)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff811274cf)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - kernel/pid_namespace.c:destroy_pid_namespace
```
```
In fs/super.c (ffffffff812352b7)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - fs/super.c:destroy_super
```
```
In fs/namespace.c (ffffffff81254499)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/proc/base.c (ffffffff812a7fd1)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff8134ff61)
Location: include/linux/user_namespace.h:59
Inline: True
```
```
In ipc/mqueue.c (ffffffff81361a9e)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
```
```
In ipc/namespace.c (ffffffff81363706)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81778783)
Location: include/linux/user_namespace.h:59
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084030)
Location: include/linux/user_namespace.h:92
Inline: True
```
```
In kernel/cred.c (ffffffff810ab350)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup.c (ffffffff81123928)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - kernel/cgroup.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8112f475)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811307c5)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff811310b8)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff81247e57)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - fs/super.c:destroy_super
```
```
In fs/exec.c (ffffffff8124bf6c)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812679d7)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/proc/base.c (ffffffff812bd85e)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff81365891)
Location: include/linux/user_namespace.h:92
Inline: True
```
```
In ipc/mqueue.c (ffffffff8137829e)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
```
```
In ipc/namespace.c (ffffffff81379eec)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff817a57b4)
Location: include/linux/user_namespace.h:92
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080f80)
Location: include/linux/user_namespace.h:99
Inline: True
```
```
In kernel/cred.c (ffffffff810a7f07)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/namespace.c (ffffffff81128d0b)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81130af5)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81131e2e)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff81132838)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff81253677)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - fs/super.c:destroy_super
```
```
In fs/exec.c (ffffffff8125808c)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81275087)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/proc/base.c (ffffffff812ca7de)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff81379fc1)
Location: include/linux/user_namespace.h:99
Inline: True
```
```
In ipc/mqueue.c (ffffffff8138c04e)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
```
```
In ipc/namespace.c (ffffffff8138daf6)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff817c3a17)
Location: include/linux/user_namespace.h:99
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108787b)
Location: include/linux/user_namespace.h:109
Inline: True
```
```
In kernel/cred.c (ffffffff810ae6d7)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/namespace.c (ffffffff8113591b)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8113da45)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8113ec4e)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff8113f405)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff81275d38)
Location: include/linux/user_namespace.h:109
Inline: True
```
```
In fs/exec.c (ffffffff8127a2ec)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81297947)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/proc/base.c (ffffffff812ef06e)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff8139ee67)
Location: include/linux/user_namespace.h:109
Inline: True
```
```
In ipc/mqueue.c (ffffffff813b13fe)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
```
```
In ipc/namespace.c (ffffffff813b2f2c)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff8183d4d7)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108a8c7)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffffffff810b554b)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/namespace.c (ffffffff8114422b)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8114c3d5)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8114ce99)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff8114dd45)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff8129c2a2)
Location: include/linux/user_namespace.h:109
Inline: True
```
```
In fs/exec.c (ffffffff812a0e73)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812bda27)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/proc/base.c (ffffffff8131c19e)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff813ce1d7)
Location: include/linux/user_namespace.h:109
Inline: True
```
```
In ipc/mqueue.c (ffffffff813e0b8e)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
```
```
In ipc/namespace.c (ffffffff813e3645)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81887d7a)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81092867)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffffffff810be6ab)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/namespace.c (ffffffff8114fd3b)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81158ff5)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81159ab9)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff8115aa15)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff812b13e2)
Location: include/linux/user_namespace.h:109
Inline: True
```
```
In fs/exec.c (ffffffff812b5e73)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812d2ec7)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/proc/base.c (ffffffff813332ee)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff813e7b27)
Location: include/linux/user_namespace.h:109
Inline: True
```
```
In ipc/mqueue.c (ffffffff813fb37e)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
```
```
In ipc/namespace.c (ffffffff813fdffc)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff818a888a)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a459)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff81096723)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffffffff810c466b)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (ffffffff81157383)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115bc3d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81165727)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81166209)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff811670c5)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff812cde84)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (ffffffff812d2c0a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812eff99)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff8130a52d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff8135a30a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8135b21f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8136f5d7)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81413aeb)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (ffffffff814279de)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8142a631)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff818f3ec2)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b329)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff8109cdf5)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffffffff810cd77b)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (ffffffff811631ba)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8116785d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811715e7)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811720c9)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff81172f85)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff812df8bd)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (ffffffff812e471a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81301a69)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff8131d4fd)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff8137253a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8137366f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff81387937)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8142db13)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (ffffffff8144170e)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81444361)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81925e7d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fcc9)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810a3a25)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/nsproxy.c (ffffffff810d6125)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff810d741b)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/time/namespace.c (ffffffff8115a021)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff811712b8)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811790ed)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81183487)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8118464c)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff81184d85)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff81316670)
Location: include/linux/user_namespace.h:120
Inline: True
```
```
In fs/exec.c (ffffffff8131b90a)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff8133a929)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff8135757b)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff813ba859)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813bb7df)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813d25f7)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8147cd5f)
Location: include/linux/user_namespace.h:120
Inline: True
```
```
In ipc/mqueue.c (ffffffff81494d0d)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81495105)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In net/core/net_namespace.c (ffffffff819f86b9)
Location: include/linux/user_namespace.h:120
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ebcd)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff8109f869)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/nsproxy.c (ffffffff810d0c90)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff810d22eb)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/time/namespace.c (ffffffff81155f70)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff8116e059)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81175dfd)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81180387)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81181674)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff81181f25)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff81321b4c)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (ffffffff81326f33)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81346769)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff81363f31)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff813cc370)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813cd36f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813e4318)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81498166)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (ffffffff814b2680)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814b2b35)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:free_ipc
```
```
In net/core/net_namespace.c (ffffffff819f8148)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f3ed)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810a0999)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/nsproxy.c (ffffffff810d286c)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff810d3ed9)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/time/namespace.c (ffffffff81157370)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff8116ec55)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8117697d)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81181297)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81182798)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff81183075)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff81327c1c)
Location: include/linux/user_namespace.h:130
Inline: True
```
```
In fs/exec.c (ffffffff8132cfe5)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff8134f4c8)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:free_vfsmnt
```
```
In fs/fs_context.c (ffffffff8136a9b1)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff813d332c)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813d42ef)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813eaf18)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8149d396)
Location: include/linux/user_namespace.h:130
Inline: True
```
```
In ipc/mqueue.c (ffffffff814b84ec)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814b8725)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff819de6b7)
Location: include/linux/user_namespace.h:130
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068d3d)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810b1dbb)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/nsproxy.c (ffffffff810e59ac)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff810e7059)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/ucount.c (ffffffff810e9ee9)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/time/namespace.c (ffffffff8117c1c0)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff81194ee5)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8119e1fd)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811a9207)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811aa768)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff811ab125)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff813751ec)
Location: include/linux/user_namespace.h:153
Inline: True
```
```
In fs/exec.c (ffffffff8137a6e5)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff8139d797)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:free_vfsmnt
```
```
In fs/fs_context.c (ffffffff813b9671)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff8142487c)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff81425c2f)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8143cc98)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff814f4dea)
Location: include/linux/user_namespace.h:153
Inline: True
```
```
In ipc/mqueue.c (ffffffff81510d1c)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81510f55)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81a8e433)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075ead)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810c847f)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/nsproxy.c (ffffffff810ff788)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff81101339)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/ucount.c (ffffffff81104b6b)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/time/namespace.c (ffffffff811b192e)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff811c5b95)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811ce5ab)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811da655)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811dbda4)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff811dc865)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff813f44fc)
Location: include/linux/user_namespace.h:153
Inline: True
```
```
In fs/exec.c (ffffffff813fa461)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81420752)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:free_vfsmnt
```
```
In fs/fs_context.c (ffffffff8143f0ca)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff8149d48c)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8149f06e)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff814b84b8)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff815849c1)
Location: include/linux/user_namespace.h:153
Inline: True
```
```
In ipc/mqueue.c (ffffffff815a2f21)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff815a3405)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:free_ipc
```
```
In net/core/net_namespace.c (ffffffff81c04350)
Location: include/linux/user_namespace.h:153
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810860dd)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810e56e8)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/nsproxy.c (ffffffff811244b8)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff81126489)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/ucount.c (ffffffff8112a45b)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/time/namespace.c (ffffffff811f26fe)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff81208335)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81211deb)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8121fc35)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff812215f4)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff81222195)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff8147d58c)
Location: include/linux/user_namespace.h:162
Inline: True
```
```
In fs/exec.c (ffffffff81483f65)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff814accf4)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:free_vfsmnt
```
```
In fs/fs_context.c (ffffffff814cdd4a)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff81531f8c)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff81533ebe)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8154fac8)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8162ab01)
Location: include/linux/user_namespace.h:162
Inline: True
```
```
In ipc/mqueue.c (ffffffff8164ca81)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8164cff5)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:free_ipc
```
```
In security/apparmor/notify.c (ffffffff816ea292)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_unotif
```
```
In net/core/net_namespace.c (ffffffff81db3a60)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088bbd)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810f0d9e)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/nsproxy.c (ffffffff811317b8)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff81133939)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/ucount.c (ffffffff811374ab)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/time/namespace.c (ffffffff81206e7e)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff8121dad5)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8122774b)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81235e25)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237aa4)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff812387c5)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff814b2344)
Location: include/linux/user_namespace.h:162
Inline: True
```
```
In fs/exec.c (ffffffff814b87a7)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff814df6f1)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff81503f3a)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/mnt_idmapping.c (ffffffff81506bd1)
Location: include/linux/user_namespace.h:162
Inline: True
```
```
In fs/proc/root.c (ffffffff8156a15c)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8156bfde)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff81587728)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81662d21)
Location: include/linux/user_namespace.h:162
Inline: True
```
```
In ipc/mqueue.c (ffffffff816851e1)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81685797)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:free_ipc
```
```
In security/apparmor/notify.c (ffffffff8172378d)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
```
```
In net/core/net_namespace.c (ffffffff81e24110)
Location: include/linux/user_namespace.h:162
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108ec02)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810fa18e)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/nsproxy.c (ffffffff8113c5d1)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff8113e8a8)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/ucount.c (ffffffff8114268b)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/time/namespace.c (ffffffff8121e08e)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff81235726)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8123f55b)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8124faa5)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff812512f7)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff81252495)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff814e3a62)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - fs/super.c:destroy_super_work
```
```
In fs/exec.c (ffffffff814eacb7)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81512481)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff81538bfa)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff815a27dc)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff815a47ee)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff815c02e7)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8169d1a7)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - fs/fuse/inode.c:delayed_release
```
```
In ipc/mqueue.c (ffffffff816c1601)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff816c1bb7)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:free_ipc
```
```
In security/apparmor/notify.c (ffffffff81764a87)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
```
```
In net/core/net_namespace.c (ffffffff81ee2070)
Location: include/linux/user_namespace.h:170
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1da8)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffff80001012cc9c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (ffff8000101d48cc)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffff8000101da074)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffff8000101e51e8)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffff8000101e6768)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffff8000101e751c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffff800010386454)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (ffff80001038ce50)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffff8000103b4af0)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffff8000103d58d8)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffff80001043c944)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffff80001043e74c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffff800010457a5c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffff800010512148)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (ffff800010529db4)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffff80001052cd3c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffff800010bc1114)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350298)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (c037cc5c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (c041749c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (c041c9c4)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (c0425a94)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (c04267d8)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (c04276b8)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (c056f278)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (c0573f40)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (c0593030)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (c05af000)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (c0602964)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c0603e24)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (c06197e0)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (c06cd258)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (c06e3b68)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c06e5668)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (c0cdc284)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013778c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (c0000000001758e4)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (c00000000023fed4)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (c000000000247284)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (c000000000255578)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (c000000000256640)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (c000000000257af0)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (c00000000047c910)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (c000000000483b38)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (c0000000004b0074)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (c0000000004d8118)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (c0000000005506a0)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c000000000551eb8)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (c000000000571fa8)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (c000000000659990)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (c000000000677828)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c000000000678da4)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (c000000000c9bc14)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000be836)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffffffe0000e128a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (ffffffe00014dd5c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffe0001527fc)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffe00015ae22)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffe00015ba9a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffe00015c884)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffe000258dd2)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (ffffffe00025d58e)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffe000277964)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffe00028f3c4)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffe0002d4ab6)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffe0002d524e)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffe0002e8d9a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffe00037c0f2)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (ffffffe00038c524)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffe00038ec38)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffe00074de24)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105aea9)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff81096715)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffffffff810c7afb)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b7da)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115fe7d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81169c07)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8116a6e9)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff8116b5a5)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff812d7e9d)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (ffffffff812dccfa)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812fa049)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff81315add)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff8136ab1a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8136bc4f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8137ff17)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff814260f3)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (ffffffff81439cee)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8143c941)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff818c5e7d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104af29)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff81085195)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffffffff810b631b)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (ffffffff8114eaca)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811530ed)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8115ce07)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8115d8e9)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff8115e7a5)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff812c8b1d)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (ffffffff812cd97a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812eac69)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff813066cd)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff8135b5aa)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8135c6df)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813709a7)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81416b73)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (ffffffff8142a75e)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8142d3b1)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff8187fdbd)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b2d9)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810966c5)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffffffff810c704b)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (ffffffff811595aa)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115dc4d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811679d7)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811684b9)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff81169375)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff812d5cad)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (ffffffff812dab0a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812f7e39)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff813138cd)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff813685ea)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8136971f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8137d9e7)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81422293)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (ffffffff81435e8e)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81438ae1)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81916e7d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c799)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff8109e2a5)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
```
```
In kernel/cred.c (ffffffff810cf50b)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/cgroup/cgroup.c (ffffffff8116661a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8116aead)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811750b7)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81175ba9)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:userns_put
```
```
In kernel/pid_namespace.c (ffffffff81176a65)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In fs/super.c (ffffffff812e6ccd)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In fs/exec.c (ffffffff812eba0a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81309609)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff8132511d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc/root.c (ffffffff8137bc3a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8137cf8f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813914e7)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81439113)
Location: include/linux/user_namespace.h:119
Inline: True
```
```
In ipc/mqueue.c (ffffffff8144e95e)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8144fc51)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff8193808d)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
</ul>

## Differences
