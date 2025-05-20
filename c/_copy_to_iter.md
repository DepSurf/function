# Function: <code>_copy_to_iter</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814670c0)
Location: lib/iov_iter.c:558
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff814670c0-ffffffff81467499: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814931c0)
Location: lib/iov_iter.c:558
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff814931c0-ffffffff81493599: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c85f0)
Location: lib/iov_iter.c:558
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff814c85f0-ffffffff814c89bf: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dcc50)
Location: lib/iov_iter.c:602
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff814dcc50-ffffffff814dd052: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81509330)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81509330-ffffffff8150978f: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81526750)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81526750-ffffffff81526baf: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158b540)
Location: lib/iov_iter.c:621
Inline: False
Direct callers:
  - fs/pipe.c:pipe_read
  - fs/eventfd.c:eventfd_read
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff8158b540-ffffffff8158b92e: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a6730)
Location: lib/iov_iter.c:630
Inline: False
Direct callers:
  - fs/pipe.c:pipe_read
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/eventfd.c:eventfd_read
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/kernfs/file.c:kernfs_file_read_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - drivers/tty/tty_io.c:iterate_tty_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff815a6730-ffffffff815a6a2e: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b0c00)
Location: lib/iov_iter.c:651
Inline: False
Direct callers:
  - fs/pipe.c:pipe_read
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/eventfd.c:eventfd_read
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/kernfs/file.c:kernfs_file_read_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - drivers/tty/tty_io.c:tty_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff815b0c00-ffffffff815b13a1: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81618790)
Location: lib/iov_iter.c:616
Inline: False
Direct callers:
  - fs/pipe.c:pipe_read
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/eventfd.c:eventfd_read
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - drivers/tty/tty_io.c:tty_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81618790-ffffffff81618e98: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:661
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - fs/pipe.c:pipe_read
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/eventfd.c:eventfd_read
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - drivers/tty/tty_io.c:tty_read
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
  - drivers/dax/super.c:dax_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff81e93164-ffffffff81e931b0: _copy_to_iter.cold (STB_LOCAL)
ffffffff816e54f0-ffffffff816e5b89: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:521
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - fs/pipe.c:pipe_read
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/eventfd.c:eventfd_read
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - drivers/tty/tty_io.c:tty_read
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
  - drivers/dax/super.c:dax_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff820781a6-ffffffff820781fd: _copy_to_iter.cold (STB_LOCAL)
ffffffff817d3b80-ffffffff817d417c: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - fs/pipe.c:pipe_read
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/eventfd.c:eventfd_read
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/tty/tty_io.c:tty_read
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
  - drivers/dax/super.c:dax_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff820f84e0-ffffffff820f8542: _copy_to_iter.cold (STB_LOCAL)
ffffffff81811650-ffffffff81811b61: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page
  - fs/pipe.c:pipe_read
  - fs/seq_file.c:seq_read_iter
  - fs/seq_file.c:seq_read_iter
  - fs/eventfd.c:eventfd_read
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:__read_vmcore
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/configfs/file.c:configfs_bin_read_iter
  - fs/configfs/file.c:configfs_read_iter
  - block/bio-integrity.c:bio_integrity_free
  - drivers/tty/tty_io.c:tty_read
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
  - drivers/dax/super.c:dax_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - net/core/datagram.c:simple_copy_to_iter
  - net/core/datagram.c:hash_and_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff821d626d-ffffffff821d6282: _copy_to_iter.cold (STB_LOCAL)
ffffffff81857760-ffffffff81857ce2: _copy_to_iter (STB_GLOBAL)
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
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff800010630e80)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffff800010630e80-ffff8000106312d0: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d729c)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
c07d729c-c07d7704: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d4bb0)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
c0000000007d4bb0-c0000000007d51c8: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045f97a)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffe00045f97a-ffffffe00045fcca: _copy_to_iter (STB_GLOBAL)
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
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151ed30)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff8151ed30-ffffffff8151f18f: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150f020)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff8150f020-ffffffff8150f47f: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151adc0)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff8151adc0-ffffffff8151b21f: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t _copy_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815345f0)
Location: lib/iov_iter.c:603
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:hash_and_copy_to_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - net/core/datagram.c:simple_copy_to_iter
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff815345f0-ffffffff81534a4f: _copy_to_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
