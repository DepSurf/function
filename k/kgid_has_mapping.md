# Function: <code>kgid_has_mapping</code>

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
In kernel/capability.c (ffffffff8108a3b0)
Location: include/linux/uidgid.h:145
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
```
In kernel/ptrace.c (ffffffff8108a859)
Location: include/linux/uidgid.h:145
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
```
```
In kernel/user_namespace.c (ffffffff8111ef12)
Location: include/linux/uidgid.h:145
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff81212ae6)
Location: include/linux/uidgid.h:145
Inline: True
```
```
In fs/attr.c (ffffffff8122958e)
Location: include/linux/uidgid.h:145
Inline: True
Inline callers:
  - fs/attr.c:inode_change_ok
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
In kernel/capability.c (ffffffff8108d355)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
```
In kernel/ptrace.c (ffffffff8108d849)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
```
```
In kernel/user_namespace.c (ffffffff81126e72)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff81239923)
Location: include/linux/uidgid.h:135
Inline: True
```
```
In fs/namei.c (ffffffff812418a3)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
```
```
In fs/attr.c (ffffffff81251e9c)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff81299296)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In fs/proc/base.c (ffffffff812a6f0c)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812abd7d)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812b131c)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
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
In kernel/capability.c (ffffffff81092716)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8113099a)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8124c663)
Location: include/linux/uidgid.h:135
Inline: True
```
```
In fs/namei.c (ffffffff8125473a)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
```
```
In fs/attr.c (ffffffff812650a9)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff812add06)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In fs/proc/base.c (ffffffff812bc7f1)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812c1652)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812c6bb1)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
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
In kernel/capability.c (ffffffff8108f856)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff81131fdb)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff81258777)
Location: include/linux/uidgid.h:135
Inline: True
```
```
In fs/namei.c (ffffffff81260270)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
```
```
In fs/attr.c (ffffffff812728f0)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff812bb186)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In fs/proc/base.c (ffffffff812c9b71)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812ce972)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812d3ee1)
Location: include/linux/uidgid.h:135
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
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
In kernel/capability.c (ffffffff81096716)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8113edba)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8127a53e)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff81282950)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
```
```
In fs/attr.c (ffffffff81295213)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff812dea7c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In fs/proc/base.c (ffffffff812ee401)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812f3142)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812f8711)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
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
In kernel/capability.c (ffffffff81099c26)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8114d6fd)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812a105b)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812ab8e2)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff812bb3d7)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff8130abcc)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810a1fb6)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8115a3bd)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812b605b)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812be4f2)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff812d05ce)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813203fc)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810a69e8)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff81166a8c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812d2dd5)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812db106)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff812ed5fd)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff81347ce2)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810acfc8)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8117294c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812e48e5)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812ecc16)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff812ff0bb)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff8135ff82)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810b489e)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff811847ac)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8131c19b)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81326953)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff813381bb)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813a59c2)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810afa9e)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff811817fc)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8132768b)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81331dc7)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff81343b2f)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813b6702)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810b1207)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8118293c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8132f965)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff81336007)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff81349eab)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813bd6e2)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810c32c7)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff811aa90c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8137d115)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff813839e2)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff81397b93)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff8140d4a2)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810da7f6)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff811dbf68)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff813f9e65)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81402ed0)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff81419d90)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff814828ec)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/user_namespace.c (ffffffff812217c8)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/namei.c (ffffffff8148d2c0)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkobj
```
```
In fs/posix_acl.c (ffffffff815156bc)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/user_namespace.c (ffffffff81237c78)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In mm/shmem.c (ffffffff813bb3df)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/namei.c (ffffffff814c3ece)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/posix_acl.c (ffffffff8154d086)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/user_namespace.c (ffffffff81251778)
Location: include/linux/uidgid.h:128
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/bpf/inode.c (ffffffff8133f556)
Location: include/linux/uidgid.h:128
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff813e5d04)
Location: include/linux/uidgid.h:128
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/namei.c (ffffffff814f65a8)
Location: include/linux/uidgid.h:128
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/posix_acl.c (ffffffff81582eb6)
Location: include/linux/uidgid.h:128
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffff800010106800)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffff8000101e68d4)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffff80001038c188)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffff800010396348)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffff8000103b0528)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffff800010426148)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (c0361504)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (c0426fc8)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (c057414c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (c057b79c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (c058fe34)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (c05eedc0)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (c00000000014dbc0)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (c000000000257054)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (c000000000483d84)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (c00000000048e73c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (c0000000004abe58)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (c000000000535398)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffe0000cb570)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffe00015c180)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffe00025d710)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffe000264980)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffe000274910)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffe0002c4c58)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810a7338)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8116af6c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812dcec5)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812e51f6)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff812f769b)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff81358562)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff81095d18)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8115e16c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812cdb45)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812d5e36)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff812e82bb)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff81349212)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810a6898)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff81168d3c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812dacd5)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812e3006)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff812f54ab)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff81356032)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
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
In kernel/capability.c (ffffffff810ae9c8)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8117642c)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812ebbd5)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812f2f44)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff8130663b)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff81369702)
Location: include/linux/uidgid.h:136
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
</details>
</li>
</ul>

## Differences
