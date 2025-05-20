# Function: <code>sock_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_has_perm(struct task_struct *task, struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81341fc0)
Location: security/selinux/hooks.c:4051
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_netlink_send
```
**Symbols:**

```
ffffffff81341fc0-ffffffff81342046: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_has_perm(struct task_struct *task, struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813773a0)
Location: security/selinux/hooks.c:4182
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff813773a0-ffffffff81377426: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_has_perm(struct task_struct *task, struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138ddb0)
Location: security/selinux/hooks.c:4257
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff8138ddb0-ffffffff8138de36: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a3b20)
Location: security/selinux/hooks.c:4231
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff813a3b20-ffffffff813a3bb1: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813c9b00)
Location: security/selinux/hooks.c:4246
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff813c9b00-ffffffff813c9b91: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813f9180)
Location: security/selinux/hooks.c:4514
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff813f9180-ffffffff813f920f: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81414cd0)
Location: security/selinux/hooks.c:4234
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81414cd0-ffffffff81414d66: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81442600)
Location: security/selinux/hooks.c:4422
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81442600-ffffffff81442699: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145c0c0)
Location: security/selinux/hooks.c:4480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff8145c0c0-ffffffff8145c161: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b5ccc)
Location: security/selinux/hooks.c:4473
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814af650-ffffffff814af6f1: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d3a5c)
Location: security/selinux/hooks.c:4489
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814cd0f0-ffffffff814cd191: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d9c9c)
Location: security/selinux/hooks.c:4653
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814d36f0-ffffffff814d3791: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81532e5c)
Location: security/selinux/hooks.c:4638
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff8152c3b0-ffffffff8152c451: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815cd83c)
Location: security/selinux/hooks.c:4542
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff815c24c0-ffffffff815c2590: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8167b1cc)
Location: security/selinux/hooks.c:4560
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff8166eca0-ffffffff8166ed70: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816b345c)
Location: security/selinux/hooks.c:4521
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff816a72c0-ffffffff816a738e: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4609
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff816e6980-ffffffff816e6aa1: sock_has_perm (STB_LOCAL)
ffffffff821d0175-ffffffff821d018a: sock_has_perm.cold (STB_LOCAL)
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
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010548be0)
Location: security/selinux/hooks.c:4480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffff800010548be0-ffff800010548cb4: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06fe920)
Location: security/selinux/hooks.c:4480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
c06fe920-c06fe9fc: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a0050)
Location: security/selinux/hooks.c:4480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
c0000000006a0050-c0000000006a0144: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a3d98)
Location: security/selinux/hooks.c:4480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffe0003a3d98-ffffffe0003a3e2c: sock_has_perm (STB_LOCAL)
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
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814546a0)
Location: security/selinux/hooks.c:4480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814546a0-ffffffff81454741: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814450e0)
Location: security/selinux/hooks.c:4480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814450e0-ffffffff81445181: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81450740)
Location: security/selinux/hooks.c:4480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81450740-ffffffff814507e1: sock_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_has_perm(struct sock *sk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81467ca0)
Location: security/selinux/hooks.c:4480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_setsockopt
  - security/selinux/hooks.c:selinux_socket_getpeername
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81467ca0-ffffffff81467d41: sock_has_perm (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param reordered. </b>
<code>task, sk, perms</code> ➡️ <code>sk, perms</code>
</li>
</ul>
</details>
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
