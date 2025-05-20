# Function: <code>__begin_current_label_crit_section</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d9e6c)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff813e4485)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff813e7267)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813e984d)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
```
```
In security/apparmor/label.c (ffffffff813ef048)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff81400d2c)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff8140b3e5)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8140e467)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81411831)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
```
```
In security/apparmor/label.c (ffffffff81416df6)
Location: security/apparmor/include/context.h:187
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff81432055)
Location: security/apparmor/include/cred.h:128
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff8143cd20)
Location: security/apparmor/include/cred.h:128
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8143fff7)
Location: security/apparmor/include/cred.h:128
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81443a9a)
Location: security/apparmor/include/cred.h:128
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
```
```
In security/apparmor/label.c (ffffffff81449145)
Location: security/apparmor/include/cred.h:128
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff8144de05)
Location: security/apparmor/include/cred.h:142
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff81459b83)
Location: security/apparmor/include/cred.h:142
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8145cec7)
Location: security/apparmor/include/cred.h:142
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814603a1)
Location: security/apparmor/include/cred.h:142
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff814660b5)
Location: security/apparmor/include/cred.h:142
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff8147b775)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff81487213)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8148a477)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148d2a5)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff81493625)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff81495445)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff814a10c3)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff814a4337)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814a7165)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff814ad555)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff814ed4c5)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff814fb1a7)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff814ff190)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81504c1b)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff8150c1a5)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff8150ab68)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff815181f7)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8151c3d0)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81521abb)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff81529055)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff815112e8)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff8151ea57)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff81522bb0)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81527e9b)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff8152f1c5)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff8156eee8)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff8157cba7)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff81580e20)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8158612b)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff8158d5e5)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff8160d581)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff8161b435)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8161ffc0)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff816234d9)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff8162b3d0)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_get_current_ns
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
In security/apparmor/apparmorfs.c (ffffffff816bf501)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff816ce4e5)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff816d34bd)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff816d7e29)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff816dfc70)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/notify.c (ffffffff816e9f20)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
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
In security/apparmor/apparmorfs.c (ffffffff816f8011)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff81707105)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8170c38d)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81711279)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff81719290)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/notify.c (ffffffff81724170)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
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
In security/apparmor/apparmorfs.c (ffffffff81734d81)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff81744b95)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8174a0d0)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8174e87c)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getlsmblob_subj
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff81757d30)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/notify.c (ffffffff81765470)
Location: security/apparmor/include/cred.h:125
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
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
In security/apparmor/apparmorfs.c (ffff80001058b4fc)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffff800010596dc8)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffff80001059a134)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffff80001059e138)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffff8000105a4a14)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (c073c08c)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (c0747e88)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (c074b238)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c074ed30)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (c0754be8)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (c0000000006fc8d0)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (c00000000070ce94)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (c000000000711668)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c0000000007163e4)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (c000000000720764)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffe0003d9b92)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffe0003e3aea)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffe0003e6726)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffe0003e920c)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffe0003ee9ca)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff8148da25)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff814996a3)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8149c917)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149f745)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff814a5b35)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff8147e445)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff8148a0c3)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8148d337)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81490165)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff81496555)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff81489ac5)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff81495743)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff814989b7)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149b7e5)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff814a1bd5)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff814a1745)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff814ad7a7)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff814b0b09)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814b3b5b)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/label.c (ffffffff814ba375)
Location: security/apparmor/include/cred.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
</ul>

## Differences
