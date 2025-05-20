# Function: <code>kuid_has_mapping</code>

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
In kernel/capability.c (ffffffff8108a39e)
Location: include/linux/uidgid.h:140
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
```
In kernel/ptrace.c (ffffffff8108a829)
Location: include/linux/uidgid.h:140
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
```
```
In kernel/user_namespace.c (ffffffff8111eea7)
Location: include/linux/uidgid.h:140
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff81212ac7)
Location: include/linux/uidgid.h:140
Inline: True
```
```
In fs/inode.c (ffffffff81227a2d)
Location: include/linux/uidgid.h:140
Inline: True
```
```
In fs/attr.c (ffffffff812294e3)
Location: include/linux/uidgid.h:140
Inline: True
Inline callers:
  - fs/attr.c:inode_change_ok
```
```
In security/keys/keyring.c (ffffffff813318b6)
Location: include/linux/uidgid.h:140
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff81335c2c)
Location: include/linux/uidgid.h:140
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff8108d343)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
```
In kernel/ptrace.c (ffffffff8108d819)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
```
```
In kernel/user_namespace.c (ffffffff81126e07)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff81239904)
Location: include/linux/uidgid.h:130
Inline: True
```
```
In fs/namei.c (ffffffff81241887)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
```
```
In fs/inode.c (ffffffff81250050)
Location: include/linux/uidgid.h:130
Inline: True
```
```
In fs/attr.c (ffffffff81251e76)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff812992c1)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In fs/proc/base.c (ffffffff812a6efc)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812abd6d)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812b130c)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In security/keys/keyring.c (ffffffff8136665d)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8136ab7c)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff81092705)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8113092d)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8124c644)
Location: include/linux/uidgid.h:130
Inline: True
```
```
In fs/namei.c (ffffffff81254716)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
```
```
In fs/inode.c (ffffffff812630f0)
Location: include/linux/uidgid.h:130
Inline: True
```
```
In fs/attr.c (ffffffff81265083)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff812add31)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In fs/proc/base.c (ffffffff812bc7e1)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812c1642)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812c6ba1)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In security/keys/keyring.c (ffffffff8137ce7d)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8138138c)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff8108f845)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff81131f6d)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff81258758)
Location: include/linux/uidgid.h:130
Inline: True
```
```
In fs/namei.c (ffffffff81260251)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
```
```
In fs/inode.c (ffffffff8127093e)
Location: include/linux/uidgid.h:130
Inline: True
```
```
In fs/attr.c (ffffffff812728ca)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff812bb1b1)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In fs/proc/base.c (ffffffff812c9b61)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812ce962)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812d3ed1)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In security/keys/keyring.c (ffffffff81390bff)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff813952ec)
Location: include/linux/uidgid.h:130
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff81096705)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8113edaa)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8127a51f)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff81282931)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
```
```
In fs/inode.c (ffffffff8129327e)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff812951ed)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff812deaa7)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In fs/proc/base.c (ffffffff812ee3f1)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setattr
```
```
In fs/proc/generic.c (ffffffff812f3132)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_notify_change
```
```
In fs/proc/proc_sysctl.c (ffffffff812f8701)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_setattr
```
```
In security/keys/keyring.c (ffffffff813b619d)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff813baa3c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff81099c12)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8114d6ed)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812a1040)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812ab8c3)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff812b8eee)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff812bb3b1)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff8130abf7)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff813e69d1)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff813eb83c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff810a1fa2)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8115a3ad)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812b6040)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812be4d3)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff812ce02e)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff812d05a6)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813203b6)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff814011d1)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8140643c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff810a69d5)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff81166a7c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812d2dbd)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812db0e9)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff812eae8f)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff812ed5d4)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff81347cba)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff8142d9e6)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8143358e)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff810acfb5)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8117293c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812e48cd)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812ecbf9)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff812fc9cf)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff812ff093)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff8135ff5a)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff81447736)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8144d2fe)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff810b488e)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8118479c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8131c183)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81326934)
Location: include/linux/uidgid.h:131
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
In fs/inode.c (ffffffff813351ff)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff81338193)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813a599a)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff81498eb2)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8149f84c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
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
In kernel/capability.c (ffffffff810afa8e)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff811817ec)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff81327673)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81331da8)
Location: include/linux/uidgid.h:131
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
In fs/inode.c (ffffffff81340b6f)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff81343b07)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813b66da)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff814b6932)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff814bd27c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
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
In kernel/capability.c (ffffffff810b11e7)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8118292c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8132f94a)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff81335e78)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff81346e76)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
```
```
In fs/attr.c (ffffffff81349e81)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813bd6ba)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff814bc782)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff814c30ec)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff810c32a7)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff811aa8fc)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff8137d0fa)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff8138395d)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff813948d6)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
```
```
In fs/attr.c (ffffffff81397bcd)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff8140d47a)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff815151a2)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8151badc)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff810da79b)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff811dbf58)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff813f9e4d)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81402e80)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff81416f39)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
```
```
In fs/attr.c (ffffffff81419b8a)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff814828cc)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff815a792f)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff815aed1a)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/user_namespace.c (ffffffff812217b8)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/namei.c (ffffffff8148d270)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkobj
```
```
In fs/posix_acl.c (ffffffff8151569c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff8165198f)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff816594ca)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/user_namespace.c (ffffffff81237c68)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In mm/shmem.c (ffffffff813bb379)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/namei.c (ffffffff814c3eb7)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/posix_acl.c (ffffffff8154d0a3)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff8168a23f)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff81691d57)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/user_namespace.c (ffffffff81251768)
Location: include/linux/uidgid.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/bpf/inode.c (ffffffff8133f4dd)
Location: include/linux/uidgid.h:123
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff813e5f44)
Location: include/linux/uidgid.h:123
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/namei.c (ffffffff814f6591)
Location: include/linux/uidgid.h:123
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/posix_acl.c (ffffffff81582ed3)
Location: include/linux/uidgid.h:123
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff816c673f)
Location: include/linux/uidgid.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff816ce327)
Location: include/linux/uidgid.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffff8000101067dc)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffff8000101e68c0)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffff80001038c170)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffff80001039632c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffff8000103ac3c4)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffff8000103b0508)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffff800010426110)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffff800010530fb8)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffff800010537398)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (c03614e4)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (c0426fb4)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (c0574134)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (c057b778)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (c058d3f0)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
```
```
In fs/attr.c (c058fe14)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (c05eed48)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (c06e8da0)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (c06ee1f4)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (c00000000014db84)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (c000000000257040)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (c000000000483d68)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (c00000000048e724)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (c0000000004a7b3c)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (c0000000004abe30)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (c0000000005353d8)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (c00000000067e2c0)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (c000000000686120)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffe0000cb54c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffe00015c16c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffe00025d6fa)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffe00026496e)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffe0002719ea)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffe0002748ea)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffe0002c4c00)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffe00039205a)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffe0003966c8)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff810a7325)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8116af5c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812dcead)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812e51d9)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff812f4faf)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff812f7673)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff8135853a)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff8143fd16)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff814458de)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff81095d05)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8115e15c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812cdb2d)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812d5e19)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff812e5bcf)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff812e8293)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813491ea)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff81430786)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8143632e)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff810a6885)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff81168d2c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812dacbd)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812e2fe9)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff812f2dbf)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff812f5483)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff8135600a)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff8143beb6)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8144197e)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
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
In kernel/capability.c (ffffffff810ae9b5)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In kernel/user_namespace.c (ffffffff8117641c)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In fs/exec.c (ffffffff812ebbbd)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812f2f27)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff813044cf)
Location: include/linux/uidgid.h:131
Inline: True
```
```
In fs/attr.c (ffffffff81306613)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (ffffffff813696da)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_valid
```
```
In security/keys/keyring.c (ffffffff81453036)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff81458cae)
Location: include/linux/uidgid.h:131
Inline: True
Inline callers:
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
</details>
</li>
</ul>

## Differences
