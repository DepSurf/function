# Function: <code>SOCKET_I</code>

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
In security/smack/smack_lsm.c (0)
Location: include/net/sock.h:1350
Inline: True
```
```
In security/tomoyo/realpath.c (0)
Location: include/net/sock.h:1350
Inline: True
```
```
In net/socket.c (ffffffff816fcb86)
Location: include/net/sock.h:1350
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/sock.h:1350
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/net/sock.h:1350
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
In security/smack/smack_lsm.c (0)
Location: include/net/sock.h:1257
Inline: True
```
```
In security/tomoyo/realpath.c (0)
Location: include/net/sock.h:1257
Inline: True
```
```
In net/socket.c (ffffffff81763886)
Location: include/net/sock.h:1257
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/sock.h:1257
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/net/sock.h:1257
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
In security/smack/smack_lsm.c (0)
Location: include/net/sock.h:1295
Inline: True
```
```
In security/tomoyo/realpath.c (0)
Location: include/net/sock.h:1295
Inline: True
```
```
In net/socket.c (ffffffff81790876)
Location: include/net/sock.h:1295
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/sock.h:1295
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/net/sock.h:1295
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
In security/smack/smack_lsm.c (0)
Location: include/net/sock.h:1298
Inline: True
```
```
In security/tomoyo/realpath.c (0)
Location: include/net/sock.h:1298
Inline: True
```
```
In net/socket.c (ffffffff817adee6)
Location: include/net/sock.h:1298
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/sock.h:1298
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/net/sock.h:1298
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
In security/smack/smack_lsm.c (0)
Location: include/net/sock.h:1302
Inline: True
```
```
In security/tomoyo/realpath.c (0)
Location: include/net/sock.h:1302
Inline: True
```
```
In net/socket.c (ffffffff81825f46)
Location: include/net/sock.h:1302
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/sock.h:1302
Inline: True
```
```
In net/unix/garbage.c (0)
Location: include/net/sock.h:1302
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
In security/smack/smack_lsm.c (ffffffff81419027)
Location: include/net/sock.h:1317
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/tomoyo/realpath.c (ffffffff8142d880)
Location: include/net/sock.h:1317
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
```
In net/socket.c (ffffffff8186f405)
Location: include/net/sock.h:1317
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff818dc45f)
Location: include/net/sock.h:1317
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/garbage.c (ffffffff8195d423)
Location: include/net/sock.h:1317
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_notinflight
  - net/unix/garbage.c:unix_inflight
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
In security/smack/smack_lsm.c (ffffffff81435710)
Location: include/net/sock.h:1355
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/tomoyo/realpath.c (ffffffff8144a1d0)
Location: include/net/sock.h:1355
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
```
In net/socket.c (ffffffff8188f8d5)
Location: include/net/sock.h:1355
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81908e3f)
Location: include/net/sock.h:1355
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/garbage.c (ffffffff81991f63)
Location: include/net/sock.h:1355
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_notinflight
  - net/unix/garbage.c:unix_inflight
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
In security/smack/smack_lsm.c (ffffffff8146318d)
Location: include/net/sock.h:1358
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/tomoyo/realpath.c (ffffffff81477e73)
Location: include/net/sock.h:1358
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
```
In net/socket.c (ffffffff818d9935)
Location: include/net/sock.h:1358
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8196a191)
Location: include/net/sock.h:1358
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff819fde5c)
Location: include/net/sock.h:1358
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff8147cf5d)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff8190b915)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff819a0c01)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff81a34a4c)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff814d29fd)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff819ddb05)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a7a393)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff81b2988c)
Location: include/net/sock.h:1416
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff814f119d)
Location: include/net/sock.h:1432
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff819dd4f5)
Location: include/net/sock.h:1432
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a831f3)
Location: include/net/sock.h:1432
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff81b381bc)
Location: include/net/sock.h:1432
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff814f8b08)
Location: include/net/sock.h:1448
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff819c3745)
Location: include/net/sock.h:1448
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81a6c2c3)
Location: include/net/sock.h:1448
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff81b25e5c)
Location: include/net/sock.h:1448
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff815536f8)
Location: include/net/sock.h:1458
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff81a72fd5)
Location: include/net/sock.h:1458
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81b25923)
Location: include/net/sock.h:1458
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff81bebaac)
Location: include/net/sock.h:1458
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff815eb25e)
Location: include/net/sock.h:1531
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff81be5935)
Location: include/net/sock.h:1531
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/sock.h:1531
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/net/sock.h:1531
Inline: True
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
In security/smack/smack_lsm.c (ffffffff8169b06e)
Location: include/net/sock.h:1589
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff81d91bd5)
Location: include/net/sock.h:1589
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/sock.h:1589
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/net/sock.h:1589
Inline: True
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
In security/smack/smack_lsm.c (ffffffff816d387e)
Location: include/net/sock.h:1580
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff81dffeb5)
Location: include/net/sock.h:1580
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/sock.h:1580
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/net/sock.h:1580
Inline: True
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
In security/smack/smack_lsm.c (ffffffff8171187e)
Location: include/net/sock.h:1555
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff81ebc355)
Location: include/net/sock.h:1555
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/sock.h:1555
Inline: True
```
```
In net/unix/scm.c (0)
Location: include/net/sock.h:1555
Inline: True
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
In security/smack/smack_lsm.c (ffff80001056f63c)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffff800010ba0ee8)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffff800010c4f320)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffff800010cf51dc)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (c07215ac)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (c0cc32a0)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (c0d5f460)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (c0dfbd28)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (c0000000006d36e4)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (c000000000c7506c)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (c000000000d4dab4)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (c000000000e1b2b8)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffe0003c26fa)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffe000738c1e)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffe0007baf6c)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffe000840d60)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff8147553d)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff818ab915)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81940a71)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff819d40dc)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff81465f5d)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff81865865)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff818fa561)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff81990e9c)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff814715dd)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff818fc915)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81991c01)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff81a3eb5c)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
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
In security/smack/smack_lsm.c (ffffffff81488ecd)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In net/socket.c (ffffffff8191d985)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/socket.c:sock_close
  - net/socket.c:sock_alloc
```
```
In net/netlink/af_netlink.c (ffffffff819b46f1)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
```
```
In net/unix/scm.c (ffffffff81a4a61c)
Location: include/net/sock.h:1368
Inline: True
Inline callers:
  - net/unix/scm.c:unix_get_socket
```
</details>
</li>
</ul>

## Differences
