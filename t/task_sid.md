# Function: <code>task_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81341905)
Location: security/selinux/hooks.c:203
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:current_has_perm
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813797ff)
Location: security/selinux/hooks.c:203
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:current_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8139026e)
Location: security/selinux/hooks.c:203
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:current_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a99a5)
Location: security/selinux/hooks.c:210
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cf941)
Location: security/selinux/hooks.c:211
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fc5d5)
Location: security/selinux/hooks.c:238
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81418d1c)
Location: security/selinux/hooks.c:228
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81446a66)
Location: security/selinux/hooks.c:229
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814605fe)
Location: security/selinux/hooks.c:231
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b2f9b)
Location: security/selinux/hooks.c:234
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d2486)
Location: security/selinux/hooks.c:235
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054dd90)
Location: security/selinux/hooks.c:231
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06ff068)
Location: security/selinux/hooks.c:231
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:ptrace_parent_sid
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006ac834)
Location: security/selinux/hooks.c:231
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a7d58)
Location: security/selinux/hooks.c:231
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81458bde)
Location: security/selinux/hooks.c:231
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144960e)
Location: security/selinux/hooks.c:231
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81454c7e)
Location: security/selinux/hooks.c:231
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814699cc)
Location: security/selinux/hooks.c:231
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:ptrace_parent_sid
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
```
</details>
</li>
</ul>

## Differences
