# Function: <code>smack_cred</code>

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
In security/smack/smack_lsm.c (ffffffff820e384c)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_msg_queue_alloc_security
  - security/smack/smack_lsm.c:smack_sem_alloc_security
  - security/smack/smack_lsm.c:smack_shm_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_secureexec
  - security/smack/smack_lsm.c:smack_bprm_committing_creds
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff813c6688)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff813c83a3)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff826ec4df)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_msg_queue_alloc_security
  - security/smack/smack_lsm.c:smack_sem_alloc_security
  - security/smack/smack_lsm.c:smack_shm_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff813ec978)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff813ee833)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff828ce337)
Location: security/smack/smack.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff81439d95)
Location: security/smack/smack.h:361
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff8143a6e3)
Location: security/smack/smack.h:361
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff828e7dd8)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff81467955)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff8146835e)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:load_self2_seq_next
  - security/smack/smackfs.c:load_self2_seq_start
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff828f08c4)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff81481735)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff8148213e)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:load_self2_seq_next
  - security/smack/smackfs.c:load_self2_seq_start
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff82d05bdc)
Location: security/smack/smack.h:342
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff814d7735)
Location: security/smack/smack.h:342
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff814da264)
Location: security/smack/smack.h:342
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:smk_netlabel_audit_set
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
In security/smack/smack_lsm.c (ffffffff82ff2fb9)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff814f4c95)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff814f7824)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:smk_netlabel_audit_set
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
In security/smack/smack_lsm.c (ffffffff831fd85e)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smack_task_getsecid_subj
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff814fbc05)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff814fec73)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:smk_netlabel_audit_set
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
In security/smack/smack_lsm.c (ffffffff832e4b4b)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smack_task_getsecid_subj
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff81556875)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff81559cc3)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:smk_netlabel_audit_set
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
In security/smack/smack_lsm.c (ffffffff8349b7c7)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smack_current_getsecid_subj
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff815f0c85)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff815f49a4)
Location: security/smack/smack.h:335
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff83ed2765)
Location: security/smack/smack.h:326
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smack_current_getsecid_subj
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff816a10e5)
Location: security/smack/smack.h:326
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff816a5424)
Location: security/smack/smack.h:326
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff836f77e5)
Location: security/smack/smack.h:327
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smack_current_getsecid_subj
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff816d9a25)
Location: security/smack/smack.h:327
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff816dde04)
Location: security/smack/smack.h:327
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff8392ab85)
Location: security/smack/smack.h:326
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:do_setattr
  - security/smack/smack_lsm.c:do_setattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_getselfattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getlsmblob_obj
  - security/smack/smack_lsm.c:smack_current_getlsmblob_subj
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getlsmblob
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff817164c5)
Location: security/smack/smack.h:326
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff8171a924)
Location: security/smack/smack.h:326
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffff80001146a950)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffff80001057313c)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffff800010573ffc)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (c1543604)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (c07262b0)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (c0727044)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (c000000001399088)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (c0000000006db3d0)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (c0000000006df230)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:load_self2_seq_next
  - security/smack/smackfs.c:load_self2_seq_start
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffe0000259aa)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffe0003c663a)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffe0003c71f6)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff828d9778)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff81479d15)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff8147a71e)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:load_self2_seq_next
  - security/smack/smackfs.c:load_self2_seq_start
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff828d1e94)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff8146a735)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff8146b13e)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:load_self2_seq_next
  - security/smack/smackfs.c:load_self2_seq_start
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff828ec4ec)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff81475db5)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff814767be)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:load_self2_seq_next
  - security/smack/smackfs.c:load_self2_seq_start
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff828f190e)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_key_alloc
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_cred_getsecid
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_transfer
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_free
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
```
In security/smack/smack_access.c (ffffffff8148d825)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged_cred
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (ffffffff8148e26e)
Location: security/smack/smack.h:349
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:load_self2_seq_next
  - security/smack/smackfs.c:load_self2_seq_start
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
</details>
</li>
</ul>

## Differences
