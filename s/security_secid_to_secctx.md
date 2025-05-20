# Function: <code>security_secid_to_secctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133b610)
Location: security/security.c:1154
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_exit
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
ffffffff8133b610-ffffffff8133b665: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81370b90)
Location: security/security.c:1178
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
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
ffffffff81370b90-ffffffff81370be5: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813874c0)
Location: security/security.c:1199
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
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
ffffffff813874c0-ffffffff81387515: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139c1a0)
Location: security/security.c:2117
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
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
ffffffff8139c1a0-ffffffff8139c1f5: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c18d0)
Location: security/security.c:1975
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
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
ffffffff813c18d0-ffffffff813c192b: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2ea0)
Location: security/security.c:1303
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
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
ffffffff813f2ea0-ffffffff813f2ef1: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140eff0)
Location: security/security.c:2054
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_exit
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
ffffffff8140eff0-ffffffff8140f03b: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c3d0)
Location: security/security.c:2073
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
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
ffffffff8143c3d0-ffffffff8143c416: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455f50)
Location: security/security.c:2112
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
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
ffffffff81455f50-ffffffff81455f96: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_secid_to_secctx(struct lsmblob *blob, struct lsmcontext *cp, int display);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8970)
Location: security/security.c:2338
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
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
ffffffff814a8970-ffffffff814a8ab3: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_secid_to_secctx(struct lsmblob *blob, struct lsmcontext *cp, int display);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5ee0)
Location: security/security.c:2355
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
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
ffffffff814c5ee0-ffffffff814c6023: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_secid_to_secctx(struct lsmblob *blob, struct lsmcontext *cp, int display);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc1a0)
Location: security/security.c:2418
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
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
ffffffff814cc1a0-ffffffff814cc2df: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_secid_to_secctx(struct lsmblob *blob, struct lsmcontext *cp, int display);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/security.c (0)
Location: security/security.c:2426
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
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
ffffffff81cd345c-ffffffff81cd3486: security_secid_to_secctx.cold (STB_LOCAL)
ffffffff815254c0-ffffffff8152560d: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_secid_to_secctx(struct lsmblob *blob, struct lsmcontext *cp, int ilsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/security.c (0)
Location: security/security.c:2451
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81e86566-ffffffff81e8658f: security_secid_to_secctx.cold (STB_LOCAL)
ffffffff815b95a0-ffffffff815b9766: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_secid_to_secctx(struct lsmblob *blob, struct lsmcontext *cp, int ilsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/security.c (0)
Location: security/security.c:2431
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff82073260-ffffffff82073289: security_secid_to_secctx.cold (STB_LOCAL)
ffffffff81664d90-ffffffff81664f56: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_secid_to_secctx(struct lsmblob *blob, struct lsmcontext *cp, int ilsm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/security.c (0)
Location: security/security.c:4097
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_receive_msg
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff820f2ea8-ffffffff820f2ed2: security_secid_to_secctx.cold (STB_LOCAL)
ffffffff8169d270-ffffffff8169d470: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_secid_to_secctx(u32 secid, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d7ee0)
Location: security/security.c:4265
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff816d7ee0-ffffffff816d7f41: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105416a0)
Location: security/security.c:2112
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
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
ffff8000105416a0-ffff800010541718: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7698)
Location: security/security.c:2112
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
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
c06f7698-c06f7700: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693f00)
Location: security/security.c:2112
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
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
c000000000693f00-c000000000693f88: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e360)
Location: security/security.c:2112
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
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
ffffffe00039e360-ffffffe00039e3b2: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e530)
Location: security/security.c:2112
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
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
ffffffff8144e530-ffffffff8144e576: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ef80)
Location: security/security.c:2112
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
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
ffffffff8143ef80-ffffffff8143efc6: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a5d0)
Location: security/security.c:2112
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build_size
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
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
ffffffff8144a5d0-ffffffff8144a616: security_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int security_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814619a0)
Location: security/security.c:2112
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
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
ffffffff814619a0-ffffffff814619e6: security_secid_to_secctx (STB_GLOBAL)
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
<code>struct lsmblob *blob</code>
</li>
<li>
<b>Param added. </b>
<code>struct lsmcontext *cp</code>
</li>
<li>
<b>Param added. </b>
<code>int display</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 secid</code>
</li>
<li>
<b>Param removed. </b>
<code>char **secdata</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *seclen</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int ilsm</code>
</li>
<li>
<b>Param removed. </b>
<code>int display</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 secid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct lsmblob *blob</code>
</li>
<li>
<b>Param removed. </b>
<code>int ilsm</code>
</li>
</ul>
</details>
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
