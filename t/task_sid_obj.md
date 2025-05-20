# Function: <code>task_sid_obj</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d8586)
Location: security/selinux/hooks.c:248
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid_obj
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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81530db0)
Location: security/selinux/hooks.c:248
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c6034)
Location: security/selinux/hooks.c:234
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81672c1f)
Location: security/selinux/hooks.c:236
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ab109)
Location: security/selinux/hooks.c:232
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e8117)
Location: security/selinux/hooks.c:260
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getlsmblob_obj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
