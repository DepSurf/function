# Function: <code>smk_ad_init</code>

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
In security/smack/smack_lsm.c (ffffffff8135e29e)
Location: security/smack/smack.h:416
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/smack/smack_lsm.c (ffffffff81394312)
Location: security/smack/smack.h:416
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff813aaf02)
Location: security/smack/smack.h:425
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff813c4b0b)
Location: security/smack/smack.h:508
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff813eaddb)
Location: security/smack/smack.h:508
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff8141c176)
Location: security/smack/smack.h:429
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff81438de9)
Location: security/smack/smack.h:468
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff81466a29)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff81480809)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff814d5d31)
Location: security/smack/smack.h:449
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff814f3411)
Location: security/smack/smack.h:442
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814fa1c2)
Location: security/smack/smack.h:464
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff81554da2)
Location: security/smack/smack.h:464
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff815eda99)
Location: security/smack/smack.h:448
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff8169dc59)
Location: security/smack/smack.h:439
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff816d68ad)
Location: security/smack/smack.h:440
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff81713230)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
</details>
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
In security/smack/smack_lsm.c (ffff800010571fc4)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (c0725284)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (c0000000006d8fe0)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffe0003c23b8)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff81478de9)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff81469809)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff81474e89)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
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
In security/smack/smack_lsm.c (ffffffff8148c829)
Location: security/smack/smack.h:456
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
```
</details>
</li>
</ul>

## Differences
