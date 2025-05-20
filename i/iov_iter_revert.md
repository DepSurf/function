# Function: <code>iov_iter_revert</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814652e0)
Location: lib/iov_iter.c:851
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff814652e0-ffffffff814654ca: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81491260)
Location: lib/iov_iter.c:853
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap.c:iomap_dio_actor
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81491260-ffffffff8149146c: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c6220)
Location: lib/iov_iter.c:983
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap.c:iomap_dio_actor
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff814c6220-ffffffff814c6440: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da980)
Location: lib/iov_iter.c:1033
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap.c:iomap_dio_bio_actor
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff814da980-ffffffff814dab89: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff8150620f)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8150ad28-ffffffff8150ad3b: iov_iter_revert.cold (STB_LOCAL)
ffffffff815061f0-ffffffff815063f9: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81524320)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81524320-ffffffff81524512: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815886a0)
Location: lib/iov_iter.c:1079
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff815886a0-ffffffff81588877: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a75e0)
Location: lib/iov_iter.c:1086
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - drivers/tty/tty_io.c:do_tty_write
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff815a75e0-ffffffff815a77b7: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ab6d0)
Location: lib/iov_iter.c:1183
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - drivers/tty/tty_io.c:do_tty_write
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff815ab6d0-ffffffff815ab8c9: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614740)
Location: lib/iov_iter.c:1039
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81614740-ffffffff81614939: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e13d0)
Location: lib/iov_iter.c:1091
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_read_iter
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff816e13d0-ffffffff816e1619: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff817d5cd8)
Location: lib/iov_iter.c:915
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_mc_to_iter
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/splice.c:iter_to_pipe
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_read_iter
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - lib/iov_iter.c:_copy_mc_to_iter
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff817d1940-ffffffff817d1ade: iov_iter_revert.part.0 (STB_LOCAL)
ffffffff817d1af0-ffffffff817d1b25: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81810750)
Location: lib/iov_iter.c:647
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/splice.c:iter_to_pipe
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_read_iter
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv4/ping.c:ping_getfrag
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff81810750-ffffffff81810885: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff818561b0)
Location: lib/iov_iter.c:548
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - kernel/printk/printk.c:devkmsg_write
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/splice.c:iter_to_pipe
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
  - block/fops.c:blkdev_write_iter
  - block/fops.c:blkdev_write_iter
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - block/bio-integrity.c:bio_integrity_copy_user
  - drivers/tty/tty_io.c:iterate_tty_write
  - drivers/net/tun.c:tun_get_user
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff818561b0-ffffffff818562c6: iov_iter_revert (STB_GLOBAL)
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
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062e198)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffff80001062e198-ffff80001062e3dc: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d4f6c)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c07d4f6c-c07d51c8: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d18d0)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c0000000007d18d0-c0000000007d1bc4: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045ddb2)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffe00045ddb2-ffffffe00045df66: iov_iter_revert (STB_GLOBAL)
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
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c900)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8151c900-ffffffff8151caf2: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150cbf0)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8150cbf0-ffffffff8150cde2: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518990)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81518990-ffffffff81518b82: iov_iter_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_revert(struct iov_iter *i, size_t unroll);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81532180)
Location: lib/iov_iter.c:1047
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81532180-ffffffff81532372: iov_iter_revert (STB_GLOBAL)
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
