# Function: <code>SOCK_INODE</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/net/sock.h:1355
Inline: True
```
```
In net/socket.c (ffffffff816fb8e3)
Location: include/net/sock.h:1355
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_file
  - net/socket.c:sock_release
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1355
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:1355
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/net/sock.h:1262
Inline: True
```
```
In net/socket.c (ffffffff81763855)
Location: include/net/sock.h:1262
Inline: True
Inline callers:
  - net/socket.c:sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1262
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:1262
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/net/sock.h:1300
Inline: True
```
```
In net/socket.c (ffffffff81790845)
Location: include/net/sock.h:1300
Inline: True
Inline callers:
  - net/socket.c:sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1300
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1300
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:1300
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/net/sock.h:1303
Inline: True
```
```
In net/socket.c (ffffffff817adeb5)
Location: include/net/sock.h:1303
Inline: True
Inline callers:
  - net/socket.c:sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1303
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1303
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:1303
Inline: True
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
In security/selinux/hooks.c (0)
Location: include/net/sock.h:1307
Inline: True
```
```
In net/socket.c (ffffffff81825dcb)
Location: include/net/sock.h:1307
Inline: True
Inline callers:
  - net/socket.c:sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1307
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1307
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:1307
Inline: True
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
In security/selinux/hooks.c (ffffffff813f8cb5)
Location: include/net/sock.h:1322
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff8186f3ea)
Location: include/net/sock.h:1322
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff81874f23)
Location: include/net/sock.h:1322
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff81929d42)
Location: include/net/sock.h:1322
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81959add)
Location: include/net/sock.h:1322
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (ffffffff814148a5)
Location: include/net/sock.h:1360
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff8188f8ba)
Location: include/net/sock.h:1360
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff818957e5)
Location: include/net/sock.h:1360
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff81959334)
Location: include/net/sock.h:1360
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff8198ea3f)
Location: include/net/sock.h:1360
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (ffffffff81442205)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff818d9916)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff818dfd08)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff819bde08)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff819fa1a9)
Location: include/net/sock.h:1363
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (ffffffff8145bc75)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff8190b8f6)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff81911eb8)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff819f4a18)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81a30e25)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (ffffffff814aeea5)
Location: include/net/sock.h:1421
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff819ddb37)
Location: include/net/sock.h:1421
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_file
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff819e3e5f)
Location: include/net/sock.h:1421
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff81ae273d)
Location: include/net/sock.h:1421
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81b25249)
Location: include/net/sock.h:1421
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
```
```
In net/mptcp/protocol.c (ffffffff81babf7b)
Location: include/net/sock.h:1421
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
```
```
In net/mptcp/subflow.c (ffffffff81bafc19)
Location: include/net/sock.h:1421
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In security/selinux/hooks.c (ffffffff814cc945)
Location: include/net/sock.h:1437
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff819dd527)
Location: include/net/sock.h:1437
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_file
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff819e379f)
Location: include/net/sock.h:1437
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff81aef5dd)
Location: include/net/sock.h:1437
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81b33db9)
Location: include/net/sock.h:1437
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
```
```
In net/mptcp/protocol.c (ffffffff81bbe48b)
Location: include/net/sock.h:1437
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bc36c6)
Location: include/net/sock.h:1437
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
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
In security/selinux/hooks.c (ffffffff814d2f75)
Location: include/net/sock.h:1453
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff819c3777)
Location: include/net/sock.h:1453
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_file
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff819c981f)
Location: include/net/sock.h:1453
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff81adad2d)
Location: include/net/sock.h:1453
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81b21a99)
Location: include/net/sock.h:1453
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
```
```
In net/mptcp/protocol.c (ffffffff81badc25)
Location: include/net/sock.h:1453
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bb3d32)
Location: include/net/sock.h:1453
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
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
In security/selinux/hooks.c (ffffffff8152bc35)
Location: include/net/sock.h:1463
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff81a73007)
Location: include/net/sock.h:1463
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_file
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff81a78bb0)
Location: include/net/sock.h:1463
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff81b99fa8)
Location: include/net/sock.h:1463
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81be6ab9)
Location: include/net/sock.h:1463
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
```
```
In net/mptcp/protocol.c (ffffffff81c7a662)
Location: include/net/sock.h:1463
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81c82473)
Location: include/net/sock.h:1463
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
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
In security/selinux/hooks.c (0)
Location: include/net/sock.h:1536
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:1536
Inline: True
```
```
In net/socket.c (ffffffff81be5976)
Location: include/net/sock.h:1536
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1536
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1536
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:1536
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e23f19)
Location: include/net/sock.h:1536
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_v6_destroy
```
```
In net/mptcp/subflow.c (ffffffff81e286a3)
Location: include/net/sock.h:1536
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
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
In security/selinux/hooks.c (0)
Location: include/net/sock.h:1594
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:1594
Inline: True
```
```
In net/socket.c (ffffffff81d91c26)
Location: include/net/sock.h:1594
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1594
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1594
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:1594
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ffb2a9)
Location: include/net/sock.h:1594
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy
```
```
In net/mptcp/subflow.c (ffffffff8200061e)
Location: include/net/sock.h:1594
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
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
In security/selinux/hooks.c (0)
Location: include/net/sock.h:1585
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:1585
Inline: True
```
```
In net/socket.c (ffffffff81dfff06)
Location: include/net/sock.h:1585
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1585
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1585
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:1585
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82077619)
Location: include/net/sock.h:1585
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy
```
```
In net/mptcp/subflow.c (ffffffff8207c806)
Location: include/net/sock.h:1585
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
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
In security/selinux/hooks.c (0)
Location: include/net/sock.h:1560
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/net/sock.h:1560
Inline: True
```
```
In net/socket.c (ffffffff81ebc3a6)
Location: include/net/sock.h:1560
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (0)
Location: include/net/sock.h:1560
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/sock.h:1560
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:1560
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82146d81)
Location: include/net/sock.h:1560
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff82151cdd)
Location: include/net/sock.h:1560
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
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
In security/selinux/hooks.c (ffff800010548674)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffff800010ba0ea4)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffff800010ba99fc)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffff800010caa930)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffff800010cf15ec)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (c06fe140)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (c0cc3268)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (c0cc7fa8)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (c0db7238)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (c0df7754)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (c00000000069f6c0)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (c000000000c75000)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (c000000000c7eee0)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (c000000000dc0ac8)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (c000000000e14580)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (ffffffe0003a38c0)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffe000738be0)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffe00073cf2a)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffe000805688)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffe00083d74a)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (ffffffff81454255)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff818ab8f6)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff818b1eb8)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff819947b8)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff819d04b5)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (ffffffff81444c95)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff81865846)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff8186be08)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff8194e278)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff8198d275)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (ffffffff814502f5)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff818fc8f6)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff81902eb8)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff819ff058)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81a3af35)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
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
In security/selinux/hooks.c (ffffffff81467795)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In net/socket.c (ffffffff8191d966)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/socket.c:__sock_release
  - net/socket.c:sock_alloc_file
```
```
In net/core/sock.c (ffffffff81923e28)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/ipv4/af_inet.c (ffffffff81a09128)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/unix/af_unix.c (ffffffff81a45d95)
Location: include/net/sock.h:1373
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_bind
```
</details>
</li>
</ul>

## Differences
