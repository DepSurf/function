# Function: <code>avc_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int avc_has_perm(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813414e0)
Location: security/selinux/avc.c:1142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:current_has_perm
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_task_wait
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_bprm_secureexec
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/selinuxfs.c:task_has_security
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff813414e0-ffffffff8134167f: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int avc_has_perm(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81376b80)
Location: security/selinux/avc.c:1142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_wait
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_secureexec
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:current_has_perm
  - security/selinux/selinuxfs.c:task_has_security
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff81376b80-ffffffff81376d1a: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int avc_has_perm(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8138d4b0)
Location: security/selinux/avc.c:1142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_wait
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_secureexec
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:current_has_perm
  - security/selinux/selinuxfs.c:task_has_security
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff8138d4b0-ffffffff8138d64a: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int avc_has_perm(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813a31b0)
Location: security/selinux/avc.c:1142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_secureexec
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:superblock_has_perm
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff813a31b0-ffffffff813a333c: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int avc_has_perm(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813c8fb0)
Location: security/selinux/avc.c:1138
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:superblock_has_perm
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff813c8fb0-ffffffff813c913c: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813f8790)
Location: security/selinux/avc.c:1178
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff813f8790-ffffffff813f894c: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81414240)
Location: security/selinux/avc.c:1178
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff81414240-ffffffff814143fc: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff81441f39-ffffffff81441f52: avc_has_perm.cold (STB_LOCAL)
ffffffff81441cb0-ffffffff81441e7c: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8145b590)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff8145b590-ffffffff8145b764: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814ae800)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff814ae800-ffffffff814ae97c: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814cc2c0)
Location: security/selinux/avc.c:1183
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff814cc2c0-ffffffff814cc451: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d28f0)
Location: security/selinux/avc.c:1184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff814d28f0-ffffffff814d2a81: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8152b760)
Location: security/selinux/avc.c:1173
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff8152b760-ffffffff8152b8f1: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff815c1370)
Location: security/selinux/avc.c:1184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:bpf_fd_pass
  - security/selinux/hooks.c:bpf_fd_pass
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff815c1370-ffffffff815c1542: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8166d990)
Location: security/selinux/avc.c:1184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:bpf_fd_pass
  - security/selinux/hooks.c:bpf_fd_pass
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_task_prctl
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff8166d990-ffffffff8166da87: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int avc_has_perm(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816a60b0)
Location: security/selinux/avc.c:1185
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:bpf_fd_pass
  - security/selinux/hooks.c:bpf_fd_pass
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_task_prctl
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff816a60b0-ffffffff816a6199: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int avc_has_perm(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816e2af0)
Location: security/selinux/avc.c:1186
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:bpf_fd_pass
  - security/selinux/hooks.c:bpf_fd_pass
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_getattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff816e2af0-ffffffff816e2bd9: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffff800010547d88)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffff800010547d88-ffff800010547f28: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fd9cc)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:check_nnp_nosuid
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:may_context_mount_sb_relabel
  - security/selinux/hooks.c:may_context_mount_sb_relabel
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
c06fd9cc-c06fdb78: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c00000000069ee40)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:may_context_mount_sb_relabel
  - security/selinux/hooks.c:may_context_mount_sb_relabel
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
c00000000069ee40-c00000000069f088: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a3270)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:may_context_mount_sb_relabel
  - security/selinux/hooks.c:may_context_mount_sb_relabel
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffe0003a3270-ffffffe0003a3390: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81453b70)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff81453b70-ffffffff81453d44: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814445b0)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff814445b0-ffffffff81444784: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8144fc10)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff8144fc10-ffffffff8144fde4: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int avc_has_perm(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81467080)
Location: security/selinux/avc.c:1176
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
  - security/selinux/hooks.c:selinux_ib_pkey_access
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_state_pol_flow_match
  - security/selinux/xfrm.c:selinux_xfrm_policy_lookup
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff81467080-ffffffff81467285: avc_has_perm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>ssid, tsid, tclass, requested, auditdata</code> ➡️ <code>state, ssid, tsid, tclass, requested, auditdata</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, ssid, tsid, tclass, requested, auditdata</code> ➡️ <code>ssid, tsid, tclass, requested, auditdata</code>
</li>
</ul>
</details>
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
