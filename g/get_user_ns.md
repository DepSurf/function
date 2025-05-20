# Function: <code>get_user_ns</code>

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
In kernel/cred.c (ffffffff810a20da)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup.c (ffffffff81f81d2a)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8111dd95)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8111e3b7)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_get
  - kernel/user_namespace.c:userns_install
```
```
In kernel/pid_namespace.c (ffffffff8111fa35)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff8120f600)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/namespace.c (ffffffff8122b741)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/proc/base.c (ffffffff8127c33a)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_setgroups_open
```
```
In fs/fuse/inode.c (ffffffff8131ac5c)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff8132e2c1)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In ipc/namespace.c (ffffffff8132ea4b)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff813344ff)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff81710eff)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
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
In kernel/cred.c (ffffffff810a588a)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup.c (ffffffff81121924)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/cgroup.c:cgroup_init
```
```
In kernel/utsname.c (ffffffff81125c63)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81126ce3)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81127a33)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff81236047)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/namespace.c (ffffffff81253eb1)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/proc/base.c (ffffffff812a9325)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff8134f72c)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff81362f4c)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In ipc/namespace.c (ffffffff813636a1)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff8136948f)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff8177883f)
Location: include/linux/user_namespace.h:48
Inline: True
Inline callers:
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
In kernel/fork.c (ffffffff81083e9c)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810ab4ea)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup.c (ffffffff81129eee)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/cgroup.c:cgroup_init
```
```
In kernel/utsname.c (ffffffff8112f6aa)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8112fd9c)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff811316e8)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff81248d1d)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/exec.c (ffffffff8124bf59)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812671c0)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/proc/base.c (ffffffff812bec25)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff81365046)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff81379728)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In ipc/namespace.c (ffffffff81379ea8)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff8137fc9f)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff817a5898)
Location: include/linux/user_namespace.h:81
Inline: True
Inline callers:
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
In kernel/fork.c (ffffffff81080ddb)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810a80aa)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff820c79cb)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/cgroup/namespace.c (ffffffff81128f0e)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81130c37)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811313ac)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81132cea)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff81254651)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/exec.c (ffffffff81258079)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81274a10)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/proc/base.c (ffffffff812cb7c5)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff81379747)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff8138c33d)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In ipc/namespace.c (ffffffff8138dab3)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff81393b1f)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff817c3b02)
Location: include/linux/user_namespace.h:88
Inline: True
Inline callers:
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
In kernel/fork.c (ffffffff810877a6)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810ae77a)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/cred.c:clone_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff826d0031)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/cgroup/namespace.c (ffffffff81135b97)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8113db88)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8113df22)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff8113fab5)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff812767ca)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/exec.c (ffffffff8127a2d9)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81297340)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/proc/base.c (ffffffff812f0065)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff8139e5ed)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff813b16ed)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In ipc/namespace.c (ffffffff813b2ed2)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff813b91af)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff8183d5c2)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
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
In kernel/fork.c (ffffffff8108accc)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810b5aa5)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff826fa76e)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/cgroup/namespace.c (ffffffff8114449c)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8114c524)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8114c8c2)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff8114e2f9)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff8129d15f)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/exec.c (ffffffff812a0e60)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812bd538)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/proc/base.c (ffffffff8131cf15)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff813cd9a2)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff813e1943)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In ipc/namespace.c (ffffffff813e3613)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff813e9f3f)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff81887e63)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
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
In kernel/fork.c (ffffffff81092cc9)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810becab)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff828b166a)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/cgroup/namespace.c (ffffffff8114ffac)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81159144)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811594e2)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff8115afd9)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff812b210f)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/exec.c (ffffffff812b5e60)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812d2848)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/proc/base.c (ffffffff81334295)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/fuse/inode.c (ffffffff813e6d82)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff813fc513)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In ipc/namespace.c (ffffffff813fdf87)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff81404985)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff818a8973)
Location: include/linux/user_namespace.h:98
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a467)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff81096cc5)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810c4d1c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff828ca315)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115beab)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8116587c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81165c28)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81167689)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff812ce014)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812d2bf7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812efa10)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff8130a683)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff8135a31c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8135c489)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8136f5e9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81412db2)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff8142918b)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8142a5ba)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff81431836)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff818f3fd2)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b337)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff8109d4f9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810cde2c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff828d2873)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81167acb)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8117173c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81171ae8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81173549)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff812dfa64)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812e4707)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff813014e0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff8131d643)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff8137254c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813748e9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff81387949)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8142ca97)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff81442ec9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814442ea)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff8144b596)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff81925f92)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fcd7)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810a4359)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/nsproxy.c (ffffffff810d601a)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff810d7bc3)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/time/namespace.c (ffffffff81159c53)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff82cf323f)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81179429)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81183369)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8118390b)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff8118504c)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/super.c (ffffffff813169c4)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff8131b8f7)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff8133abad)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff81357711)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff813ba86f)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813bca89)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813d2609)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8147d500)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff81494d29)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81494f1b)
Location: include/linux/user_namespace.h:109
Inline: True
```
```
In security/keys/process_keys.c (ffffffff8149d2b9)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff819f9f41)
Location: include/linux/user_namespace.h:109
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ebef)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff8109ff75)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/nsproxy.c (ffffffff810d0b4f)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff810d29f3)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/time/namespace.c (ffffffff81155c68)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff82fdfd14)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8117613c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8118023b)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811813fc)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff811821c4)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/super.c (ffffffff81321e84)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff81326f07)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81346dbe)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff813640f7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff813cc39e)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813ce840)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813e433e)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff814988c4)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff814b26b8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814b28af)
Location: include/linux/user_namespace.h:108
Inline: True
```
```
In security/keys/process_keys.c (ffffffff814bad69)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff819f9ac1)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f40f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810a0c88)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/nsproxy.c (ffffffff810d272f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff810d460f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/time/namespace.c (ffffffff81157247)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff831ea926)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81176cb6)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8118141b)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8118249f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81183314)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/super.c (ffffffff81327f54)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff8132cfb9)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff8134d2be)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:clone_mnt
```
```
In fs/fs_context.c (ffffffff8136ab6f)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff813d335a)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813d54c0)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813eaf3e)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8149d950)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff814b8524)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814b8b0c)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff814c0c3b)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff819dfc82)
Location: include/linux/user_namespace.h:119
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068d5f)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810b20fb)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/nsproxy.c (ffffffff810e586f)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff810e77ef)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/ucount.c (ffffffff810ea0f1)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/time/namespace.c (ffffffff8117c097)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff832cf105)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8119e536)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811a938b)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811aa46f)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff811ab3ce)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/super.c (ffffffff81375524)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff8137a6b9)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff8139b28e)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:clone_mnt
```
```
In fs/fs_context.c (ffffffff813b982f)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff814248aa)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff81426e00)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8143ccbe)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff814f5400)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff81510d54)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8151133c)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff8151967d)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff81a90082)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075ecf)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810c8a4c)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/nsproxy.c (ffffffff810ff7dd)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff81101a78)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/ucount.c (ffffffff81104d54)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/time/namespace.c (ffffffff811b17e2)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff83482e4a)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811ce964)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811da4d9)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811dba59)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff811dcb2f)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/super.c (ffffffff813f48d0)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff813fa435)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff8141eaea)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:vfs_create_mount
```
```
In fs/fs_context.c (ffffffff8143f298)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff8149d4ba)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff814a0689)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff814b84de)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff815854b0)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff815a2f59)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff815a316c)
Location: include/linux/user_namespace.h:142
Inline: True
```
```
In security/keys/process_keys.c (ffffffff815ac24d)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff81c05e9d)
Location: include/linux/user_namespace.h:142
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810860ff)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810e5de5)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/nsproxy.c (ffffffff8112450d)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff81126c48)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/ucount.c (ffffffff8112a664)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/time/namespace.c (ffffffff811f2532)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb0664)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff812121e4)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8121fa99)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81221269)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff8122248f)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/super.c (ffffffff8147d9e0)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff81483f39)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff814ab55a)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff814ce1a7)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff81531fba)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff815355f9)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8154faee)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8162b6b0)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff8164cab9)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8164cd1c)
Location: include/linux/user_namespace.h:151
Inline: True
```
```
In security/keys/process_keys.c (ffffffff816566dd)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/apparmor/notify.c (ffffffff816ea1ad)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_unotif
```
```
In net/core/net_namespace.c (ffffffff81db579d)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088bdf)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810f15fe)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/nsproxy.c (ffffffff8113180d)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff811340e8)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/ucount.c (ffffffff811376b3)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/time/namespace.c (ffffffff81206cb2)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff836d5654)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81227b28)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81235c89)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237719)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81238ac6)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/super.c (ffffffff814b2780)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff814b877b)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff814e035a)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff8150439c)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/mnt_idmapping.c (ffffffff81506d3c)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:alloc_mnt_idmap
```
```
In fs/proc/root.c (ffffffff8156a18a)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8156d7c9)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8158774e)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff816638e0)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff81685219)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81685526)
Location: include/linux/user_namespace.h:151
Inline: True
```
```
In security/keys/process_keys.c (ffffffff8168ef1d)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/apparmor/notify.c (ffffffff817236c0)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
```
```
In net/core/net_namespace.c (ffffffff81e25d6d)
Location: include/linux/user_namespace.h:151
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108ec24)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff810fa9c2)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/nsproxy.c (ffffffff8113c454)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cred.c (ffffffff8113f089)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/ucount.c (ffffffff811428c2)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/time/namespace.c (ffffffff8121dec2)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/cgroup.c (ffffffff839079c4)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8123f938)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8124f909)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81250f49)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81252796)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/super.c (ffffffff814e5151)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff814eac8b)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff8151361b)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff8153905e)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff815a280b)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff815a6149)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff815c030d)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff8169d9d0)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff816c1639)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff816c1946)
Location: include/linux/user_namespace.h:159
Inline: True
```
```
In security/keys/process_keys.c (ffffffff816cb46f)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/apparmor/notify.c (ffffffff817649bf)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
```
```
In net/core/net_namespace.c (ffffffff81ee3cfc)
Location: include/linux/user_namespace.h:159
Inline: True
Inline callers:
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
In kernel/fork.c (ffff8000100f1c80)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffff80001012d078)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffff80001144add4)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffff8000101da3c0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffff8000101e5320)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffff8000101e65c8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffff8000101e7874)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffff80001038650c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffff80001038ce34)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffff8000103b4cc0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffff8000103d5a68)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffff80001043c96c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffff80001043ed54)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffff800010457a8c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffff800010512444)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffff80001052c240)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffff80001052cd08)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffff8000105351d4)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffff800010bc1fd0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In kernel/fork.c (c0350ba0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (c037d540)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (c1525140)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (c041cc2c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (c0425bc8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c042607c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (c0427c70)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (c056ff68)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (c0573f18)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (c05929e8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (c05af428)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (c060299c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c06056ac)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (c0619818)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (c06cc134)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (c06e43f8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c06e560c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (c06ec8c0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (c0cdd4e0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In kernel/fork.c (c00000000013740c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (c000000000176364)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (c000000001370570)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (c000000000247654)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (c00000000025573c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c000000000255cf0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (c000000000258184)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (c00000000047dd94)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (c000000000483b18)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (c0000000004b0bd0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (c0000000004d832c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (c0000000005506d4)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c000000000553ae0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (c000000000571fdc)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (c00000000065848c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (c000000000677d20)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c000000000678d14)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (c0000000006837a4)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (c000000000c9bdd8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In kernel/fork.c (ffffffe0000becc6)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffe0000e17fe)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffe00000c1aa)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffe000152ab6)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffe00015b000)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffe00015b38e)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffe00015cd30)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffe000258fd2)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffe00025d57e)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffe00027740a)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffe00028f54e)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffe0002d4ace)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffe0002d52b8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffe0002e8db2)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffe00037b192)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffe00038e6f8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffe00038ec12)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffe000395196)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffe00074f01e)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105aeb7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff81096e19)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810c81ac)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff828bb724)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811600eb)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81169d5c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8116a108)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff8116bb69)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff812d8044)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812dcce7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812f9ac0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff81315c23)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff8136ab2c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8136cec9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8137ff29)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81425077)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff8143b4a9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8143c8ca)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff81443b76)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff818c5f92)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104af37)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff81085899)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810b69cc)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff828b3db7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81153355)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8115cf5c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115d308)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff8115ed69)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff812c8cc4)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812cd967)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812ea6e0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff81306813)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff8135b5bc)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8135d959)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813709b9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81415af7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff8142bf19)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8142d33a)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff814345c6)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff8187fed2)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b2e7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff81096dc9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810c76fc)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff828ce4a7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115debb)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81167b2c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81167ed8)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81169939)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff812d5e54)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812daaf7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff812f78b0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff81313a13)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff813685fc)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8136a999)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff8137d9f9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81421217)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff81437649)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81438a6a)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff8143fd16)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff81916f92)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c7a7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In kernel/fork.c (ffffffff8109ec69)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cred.c (ffffffff810cfbcc)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff828d38a1)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8116b129)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8117520c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81175578)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81177059)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/super.c (ffffffff812e77b4)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812eb9f7)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namespace.c (ffffffff81308bc0)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff81325263)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/root.c (ffffffff8137bc4c)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8137e39b)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/sysfs/mount.c (ffffffff813914f9)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/fuse/inode.c (ffffffff81438097)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/mqueue.c (ffffffff8144ed53)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8144fbda)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/process_keys.c (ffffffff81456ec6)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In net/core/net_namespace.c (ffffffff819381a2)
Location: include/linux/user_namespace.h:108
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
</details>
</li>
</ul>

## Differences
