# Function: <code>copy_to_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t copy_to_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fbe80)
Location: lib/iov_iter.c:386
Inline: False
Direct callers:
  - fs/dax.c:dax_do_io
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff813fbe80-ffffffff813fc0d6: copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81444920)
Location: lib/iov_iter.c:359
Inline: False
Direct callers:
  - fs/dax.c:dax_do_io
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81444920-ffffffff81444ceb: copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814630c0)
Location: lib/iov_iter.c:538
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff814630c0-ffffffff8146354d: copy_to_iter (STB_GLOBAL)
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
In fs/dax.c (ffffffff812a970e)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In lib/iov_iter.c (ffffffff814675d7)
Location: include/linux/uio.h:103
Inline: True
```
```
In drivers/net/tun.c (ffffffff81695924)
Location: include/linux/uio.h:103
Inline: True
```
```
In net/core/datagram.c (ffffffff817bf6ba)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/ipv4/tcp.c (ffffffff8182432a)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff818473d6)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff818a7f6b)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff818d5490)
Location: include/linux/uio.h:103
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/dax.c (ffffffff812ccccd)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In lib/iov_iter.c (ffffffff8149371e)
Location: include/linux/uio.h:101
Inline: True
```
```
In drivers/net/tun.c (ffffffff8170046e)
Location: include/linux/uio.h:101
Inline: True
```
```
In net/core/datagram.c (ffffffff8183904a)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/ipv4/tcp.c (ffffffff818a59e2)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff818c6e36)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff8192aa1b)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81959f40)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In lib/iov_iter.c (ffffffff814c8b71)
Location: include/linux/uio.h:101
Inline: True
```
```
In drivers/net/tun.c (ffffffff8173fcb2)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff81806d1e)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff818837a3)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/ipv4/tcp.c (ffffffff818f779f)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8191d4f0)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81983112)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff819af1f6)
Location: include/linux/uio.h:101
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap.c (ffffffff81324260)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In lib/iov_iter.c (ffffffff814dd39f)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (ffffffff81763cd2)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff81832d4e)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff818a48b5)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81925e0e)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8194baaa)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819b940c)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff819e5bba)
Location: include/linux/uio.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (ffffffff8134dd10)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (ffffffff81509ad0)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (ffffffff817a1a6e)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff81877936)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff818f0045)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81989962)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819b01a9)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a28103)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81a55612)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (ffffffff81365fc5)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (ffffffff81526ef6)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (ffffffff817c273e)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff818a9836)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff81921785)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819c0dd8)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819e6e2e)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a5eb60)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81a8c6e2)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/pipe.c (ffffffff8131efef)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/eventfd.c (ffffffff81371e10)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/iomap/direct-io.c (ffffffff813ad998)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In lib/iov_iter.c (ffffffff8158ba86)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/net/tun.c (ffffffff8188eb92)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff81979075)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff819f5575)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81aab960)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ad467a)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b580c4)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81b87a66)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/pipe.c (ffffffff8132a51f)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/seq_file.c (ffffffff8134daaa)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/eventfd.c (ffffffff8137fc08)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/iomap/direct-io.c (ffffffff813befd8)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/proc/proc_sysctl.c (ffffffff813d92dc)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/kernfs/file.c (ffffffff813e1ee8)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_file_read_iter
```
```
In lib/iov_iter.c (ffffffff815a6a56)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/tty/tty_io.c (ffffffff81750bd2)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:iterate_tty_read
```
```
In drivers/net/tun.c (ffffffff8189cd02)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff8197e135)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff819f5035)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81ab6658)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/udp.c (ffffffff81ae0bd7)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b66768)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81b97546)
Location: include/linux/uio.h:132
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/pipe.c (ffffffff813304ca)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/seq_file.c (ffffffff81354e44)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/eventfd.c (ffffffff81386888)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/iomap/direct-io.c (ffffffff813c6118)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/proc/proc_sysctl.c (ffffffff813e0780)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/kernfs/file.c (ffffffff813e8b15)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_file_read_iter
```
```
In lib/iov_iter.c (ffffffff815b1816)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/tty/tty_io.c (ffffffff81734ace)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/net/tun.c (ffffffff8187f382)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff81961fd5)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff819db1c5)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81aa1810)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/udp.c (ffffffff81accc98)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b54907)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81b8654e)
Location: include/linux/uio.h:140
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/pipe.c (ffffffff8137dc83)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/seq_file.c (ffffffff813a3254)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/eventfd.c (ffffffff813d3b18)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/iomap/direct-io.c (ffffffff814154e1)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff814321ba)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/kernfs/file.c (ffffffff8143a845)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_file_read_iter
```
```
In fs/configfs/file.c (ffffffff8143e0c6)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
```
```
In lib/iov_iter.c (ffffffff816192c6)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/tty/tty_io.c (ffffffff817b542e)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/net/tun.c (ffffffff81910f56)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff81a09085)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff81a8a845)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81b5d7a7)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/udp.c (ffffffff81b8b6ca)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81c1be30)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81c5290e)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In arch/x86/kernel/crash_dump_64.c (ffffffff81098844)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
```
```
In fs/pipe.c (ffffffff813fd40a)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/seq_file.c (ffffffff81427019)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/eventfd.c (ffffffff8145d0df)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/iomap/direct-io.c (ffffffff8148cba7)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff814acc81)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/proc/vmcore.c (ffffffff814b0a12)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
```
```
In fs/kernfs/file.c (ffffffff814b5a2c)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_file_read_iter
```
```
In fs/configfs/file.c (ffffffff814b9828)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
```
```
In lib/iov_iter.c (ffffffff816e5fb6)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/tty/tty_io.c (ffffffff818f1354)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff819354d8)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/net/tun.c (ffffffff81a64036)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/datagram.c (ffffffff81bffe35)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81cec1a0)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/udp.c (ffffffff81d1c087)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81db85f8)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81df591a)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In arch/x86/kernel/crash_dump_64.c (ffffffff810aef74)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
```
```
In fs/pipe.c (ffffffff81486ffa)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/seq_file.c (ffffffff814b3ad9)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/eventfd.c (ffffffff814ec89f)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/iomap/direct-io.c (ffffffff815200ca)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff815430a1)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/proc/vmcore.c (ffffffff81547312)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
```
```
In fs/kernfs/file.c (ffffffff8154cb8d)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_file_read_iter
```
```
In fs/configfs/file.c (ffffffff81550fd8)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
```
```
In lib/iov_iter.c (ffffffff817d41d6)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/tty/tty_io.c (ffffffff81a4a534)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff81a93dbc)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/net/tun.c (ffffffff81bef276)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/datagram.c (ffffffff81daf215)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81eb00bf)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/udp.c (ffffffff81ee2f6c)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81f88631)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81fc979b)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In arch/x86/kernel/crash_dump_64.c (ffffffff810b1f74)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
```
```
In fs/pipe.c (ffffffff814bbde1)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/seq_file.c (ffffffff814e8b59)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/eventfd.c (ffffffff81522ed2)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/iomap/direct-io.c (ffffffff8155813a)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff8157b4e4)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/proc/kcore.c (ffffffff8157d6c8)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/vmcore.c (ffffffff8157ef32)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
```
```
In fs/kernfs/file.c (ffffffff8158485d)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_file_read_iter
```
```
In fs/configfs/file.c (ffffffff81588cbb)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
```
```
In lib/iov_iter.c (ffffffff81811bc6)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/tty/tty_io.c (ffffffff81a9474f)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff81adef9c)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/net/tun.c (ffffffff81c47356)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/datagram.c (ffffffff81e1f405)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81f0e50f)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/udp.c (ffffffff81f4280d)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81fe8f58)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff8202bd65)
Location: include/linux/uio.h:191
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In arch/x86/kernel/crash_dump_64.c (ffffffff810b93a4)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
```
```
In fs/pipe.c (ffffffff814ee371)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - fs/pipe.c:pipe_read
```
```
In fs/seq_file.c (ffffffff8151c9e9)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
```
```
In fs/eventfd.c (ffffffff815575d2)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/iomap/direct-io.c (ffffffff8158e76a)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff815b3d94)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/proc/kcore.c (ffffffff815b60e9)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/vmcore.c (ffffffff815b7972)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
```
```
In fs/kernfs/file.c (ffffffff815bd1ed)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_file_read_iter
```
```
In fs/configfs/file.c (ffffffff815c188e)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
```
```
In block/bio-integrity.c (ffffffff817f905b)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_free
```
```
In drivers/tty/tty_io.c (ffffffff81ae7306)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff81b323bc)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/net/tun.c (ffffffff81cfcc56)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/datagram.c (ffffffff81edcab5)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
  - net/core/datagram.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81fd2808)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/udp.c (ffffffff82008809)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff820b6a80)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff820fb816)
Location: include/linux/uio.h:193
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (ffff80001042ce64)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (ffff80001063166c)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (ffff8000109dd250)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffff800010afdbb8)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffff800010bbca8c)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffff800010c711bc)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffff800010c9d340)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffff800010d2604c)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffff800010d57e94)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (c05f5c64)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (c07d79c4)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (c0ac5980)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In net/core/datagram.c (c0cd8224)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (c0d802a8)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (c0daa9e4)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (c0e2a508)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (c0e59e04)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (c00000000053e570)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (c0000000007d56b8)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (c000000000aa3898)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (c000000000beee60)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (c000000000c95ac0)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (c000000000d78460)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (c000000000dac274)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (c000000000e53bc4)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (c000000000e92fd8)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (ffffffe0002ca1bc)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (ffffffe00045ffa2)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (ffffffe0006284b4)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffe0006efbe0)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffe00074b324)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffe0007d69ba)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffe0007f9194)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffe0008651e0)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffe00088fb36)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (ffffffff8135e5a5)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (ffffffff8151f4d6)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (ffffffff8178720e)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff8184f6b6)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff818c1785)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81960c48)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81986c9e)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819fe1f0)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81a2bd72)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (ffffffff8134f245)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (ffffffff8150f7c6)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (ffffffff81766b5e)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff81816cc6)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff8187b6c5)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff8191a738)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8194075e)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819bafb0)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff819e8f62)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (ffffffff8135c075)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (ffffffff8151b566)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (ffffffff817b75be)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff8189ece6)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff81912785)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819cb418)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819f146e)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a68c70)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81a97922)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In fs/iomap/direct-io.c (ffffffff8136f7c5)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In lib/iov_iter.c (ffffffff81534da6)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/net/tun.c (ffffffff817d1c21)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/md/dm.c (ffffffff818bb5e6)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_to_iter
```
```
In net/core/datagram.c (ffffffff81933905)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/core/datagram.c:simple_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff819d4fa8)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819fb149)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a7525b)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81aa4242)
Location: include/linux/uio.h:133
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *addr</code> ➡️ <code>const void *addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
