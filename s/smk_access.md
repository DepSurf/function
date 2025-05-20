# Function: <code>smk_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813627d0)
Location: security/smack/smack_access.c:125
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff813627d0-ffffffff813628be: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813989a0)
Location: security/smack/smack_access.c:125
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff813989a0-ffffffff81398a90: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813af580)
Location: security/smack/smack_access.c:120
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff813af580-ffffffff813af670: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813c6130)
Location: security/smack/smack_access.c:120
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff813c6130-ffffffff813c621c: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813ec420)
Location: security/smack/smack_access.c:120
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff813ec420-ffffffff813ec50c: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8141d250)
Location: security/smack/smack_access.c:120
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff8141d250-ffffffff8141d336: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81439840)
Location: security/smack/smack_access.c:120
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff81439840-ffffffff81439926: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81467450)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff81467450-ffffffff8146752f: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81481230)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff81481230-ffffffff8148130f: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814d7190)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff814d7190-ffffffff814d727f: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814f4600)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff814f4600-ffffffff814f472c: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814fb570)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff814fb570-ffffffff814fb69c: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815561e0)
Location: security/smack/smack_access.c:115
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff815561e0-ffffffff8155630d: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815f0580)
Location: security/smack/smack_access.c:115
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff815f0580-ffffffff815f06bd: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816a0970)
Location: security/smack/smack_access.c:115
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff816a0970-ffffffff816a0aad: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816d92b0)
Location: security/smack/smack_access.c:115
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff816d92b0-ffffffff816d93ed: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81715d10)
Location: security/smack/smack_access.c:115
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_post_notification
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_access2
```
**Symbols:**

```
ffffffff81715d10-ffffffff81715e4d: smk_access (STB_GLOBAL)
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
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffff800010572ad8)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffff800010572ad8-ffff800010572c18: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0725d00)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
c0725d00-c0725e2c: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0000000006da950)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
c0000000006da950-c0000000006daac4: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffe0003c60e4)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffe0003c60e4-ffffffe0003c61dc: smk_access (STB_GLOBAL)
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
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81479810)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff81479810-ffffffff814798ef: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8146a230)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff8146a230-ffffffff8146a30f: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814758b0)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff814758b0-ffffffff8147598f: smk_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smk_access(struct smack_known *subject, struct smack_known *object, int request, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8148d2b0)
Location: security/smack/smack_access.c:116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff8148d2b0-ffffffff8148d3d4: smk_access (STB_GLOBAL)
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
