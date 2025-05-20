# Function: <code>security_release_secctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133b6e0)
Location: security/security.c:1168
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_exit
  - fs/xattr.c:xattr_getsecurity
  - fs/kernfs/inode.c:kernfs_iop_setxattr
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff8133b6e0-ffffffff8133b720: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81370c60)
Location: security/security.c:1192
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - fs/xattr.c:xattr_getsecurity
  - fs/kernfs/inode.c:kernfs_iop_setxattr
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81370c60-ffffffff81370ca0: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387590)
Location: security/security.c:1213
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - fs/xattr.c:xattr_getsecurity
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81387590-ffffffff813875d0: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139cba0)
Location: security/security.c:2131
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - fs/xattr.c:xattr_getsecurity
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8139cba0-ffffffff8139cc0c: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c23d0)
Location: security/security.c:1989
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff813c23d0-ffffffff813c2443: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2f60)
Location: security/security.c:1317
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff813f2f60-ffffffff813f2f9e: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140e340)
Location: security/security.c:2068
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - fs/kernfs/inode.c:kernfs_security_xattr_set
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8140e340-ffffffff8140e361: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143aeb0)
Location: security/security.c:2087
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8143aeb0-ffffffff8143aed1: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81454c90)
Location: security/security.c:2126
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81454c90-ffffffff81454cb1: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_release_secctx(struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a88c0)
Location: security/security.c:2397
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_lsm
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff814a88c0-ffffffff814a8913: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_release_secctx(struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5e30)
Location: security/security.c:2414
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_lsm
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff814c5e30-ffffffff814c5e83: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_release_secctx(struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc0f0)
Location: security/security.c:2477
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_lsm
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff814cc0f0-ffffffff814cc143: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_release_secctx(struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815250c0)
Location: security/security.c:2485
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_lsm
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff815250c0-ffffffff81525113: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_release_secctx(struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b94d0)
Location: security/security.c:2515
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fuse/dir.c:get_security_context
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff815b94d0-ffffffff815b9531: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_release_secctx(struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664ca0)
Location: security/security.c:2495
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fuse/dir.c:get_security_context
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81664ca0-ffffffff81664d01: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_release_secctx(struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169d180)
Location: security/security.c:4177
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8169d180-ffffffff8169d1e1: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_release_secctx(struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9930)
Location: security/security.c:4341
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff816d9930-ffffffff816d997d: security_release_secctx (STB_GLOBAL)
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
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff80001053fee8)
Location: security/security.c:2126
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffff80001053fee8-ffff80001053ff2c: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f5fa4)
Location: security/security.c:2126
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
c06f5fa4-c06f5fd8: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006913f0)
Location: security/security.c:2126
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
c0000000006913f0-c000000000691440: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039d1b2)
Location: security/security.c:2126
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffe00039d1b2-ffffffe00039d1ea: security_release_secctx (STB_GLOBAL)
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
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d270)
Location: security/security.c:2126
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8144d270-ffffffff8144d291: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dcc0)
Location: security/security.c:2126
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8143dcc0-ffffffff8143dce1: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449310)
Location: security/security.c:2126
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81449310-ffffffff81449331: security_release_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_release_secctx(char *secdata, u32 seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814606e0)
Location: security/security.c:2126
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff814606e0-ffffffff81460701: security_release_secctx (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmcontext *cp</code>
</li>
<li>
<b>Param removed. </b>
<code>char *secdata</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 seclen</code>
</li>
</ul>
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
