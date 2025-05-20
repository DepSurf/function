# Function: <code>copy_from_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb920)
Location: lib/iov_iter.c:407
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff813fb920-ffffffff813fbb76: copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81444d80)
Location: lib/iov_iter.c:374
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81444d80-ffffffff814450bd: copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81463700)
Location: lib/iov_iter.c:555
Inline: False
Direct callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81463700-ffffffff81463a7b: copy_from_iter (STB_GLOBAL)
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
In drivers/md/dm.c (ffffffff8174c686)
Location: include/linux/uio.h:112
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff817c0310)
Location: include/linux/uio.h:112
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff818359bf)
Location: include/linux/uio.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In drivers/md/dm.c (ffffffff817be852)
Location: include/linux/uio.h:110
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff81839d30)
Location: include/linux/uio.h:110
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff818b4f35)
Location: include/linux/uio.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In kernel/bpf/sockmap.c (ffffffff811cfca7)
Location: include/linux/uio.h:110
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
```
```
In drivers/md/dm.c (ffffffff81806dfe)
Location: include/linux/uio.h:110
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff81884475)
Location: include/linux/uio.h:110
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff8190a5a0)
Location: include/linux/uio.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In fs/iomap.c (ffffffff81324195)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In drivers/md/dm.c (ffffffff81832e2e)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff818a41cf)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff818e7128)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff8193881b)
Location: include/linux/uio.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In fs/iomap/direct-io.c (ffffffff8134dc6c)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In drivers/md/dm.c (ffffffff81877856)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff818ef81f)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81936ac0)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff8199b2a1)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (ffffffff81365f07)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In drivers/md/dm.c (ffffffff818a9746)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff81921812)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81968f79)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff819d1ce1)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (ffffffff813ad935)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In drivers/md/dm.c (ffffffff81978f85)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff819f4c52)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81a3c96b)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff81abebce)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (ffffffff813bef75)
Location: include/linux/uio.h:141
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/kernfs/file.c (ffffffff813e2555)
Location: include/linux/uio.h:141
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write_iter
```
```
In drivers/tty/tty_io.c (ffffffff81750f34)
Location: include/linux/uio.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/md/dm.c (ffffffff8197e235)
Location: include/linux/uio.h:141
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff819f4582)
Location: include/linux/uio.h:141
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81a3f03b)
Location: include/linux/uio.h:141
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff81aca52e)
Location: include/linux/uio.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (ffffffff813c60b5)
Location: include/linux/uio.h:149
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/kernfs/file.c (ffffffff813e8dd5)
Location: include/linux/uio.h:149
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write_iter
```
```
In drivers/tty/tty_io.c (ffffffff81734f54)
Location: include/linux/uio.h:149
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/md/dm.c (ffffffff81961ee5)
Location: include/linux/uio.h:149
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff819da732)
Location: include/linux/uio.h:149
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81a4d44b)
Location: include/linux/uio.h:149
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff81ab53ac)
Location: include/linux/uio.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8106508b)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff8113c165)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/iomap/direct-io.c (ffffffff81415481)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff8143212b)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/kernfs/file.c (ffffffff8143ab05)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write_iter
```
```
In fs/configfs/file.c (ffffffff8143deef)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
```
```
In security/keys/keyctl.c (ffffffff815161ca)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/tty/tty_io.c (ffffffff817b5954)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/net/tun.c (ffffffff8190fba8)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/dm.c (ffffffff81a08f95)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff81a8ac62)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81b056df)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/netlink/af_netlink.c (ffffffff81b260bc)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81b4b9de)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81b5a1ce)
Location: include/linux/uio.h:157
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b723a4)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv4/raw.c (ffffffff81b86988)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81b88a40)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81baf7e8)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81c1b4a0)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81c2116e)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81c51f46)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071ae9)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff8115eedf)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/iomap/direct-io.c (ffffffff8148cb69)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff814acbfa)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/kernfs/file.c (ffffffff814b630d)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write_iter
```
```
In fs/configfs/file.c (ffffffff814b9a3e)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
```
```
In security/keys/keyctl.c (ffffffff815a8a6e)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/tty/tty_io.c (ffffffff818f1adb)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/char/random.c (ffffffff819342b2)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
```
```
In drivers/net/tun.c (ffffffff81a6681b)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/datagram.c (ffffffff81c002b6)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81c8ac88)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/netlink/af_netlink.c (ffffffff81caece5)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81cd90ae)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81ce8520)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/tcp_output.c (ffffffff81d01aca)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv4/raw.c (ffffffff81d173e5)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81d19ba0)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81d42cec)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81db7790)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81dbdece)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81df42de)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff81e37277)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081779)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff81191eff)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/iomap/direct-io.c (ffffffff8152008c)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff8154301a)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/kernfs/file.c (ffffffff8154d11d)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write_iter
```
```
In fs/configfs/file.c (ffffffff815511fe)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
```
```
In security/keys/keyctl.c (ffffffff81652bfe)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/tty/tty_io.c (ffffffff81a49b52)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/char/random.c (ffffffff81a93ee2)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
```
```
In drivers/net/tun.c (ffffffff81bf1ceb)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/datagram.c (ffffffff81daf6d6)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81e45d68)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/netlink/af_netlink.c (ffffffff81e6c335)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81e997ce)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81eabe70)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6c3a)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv4/raw.c (ffffffff81eddc22)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ee05c0)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81f0bccc)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81f87590)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81f8e469)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81fc8d6d)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff820100b7)
Location: include/linux/uio.h:184
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81083c2c)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff811a379c)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In kernel/trace/trace_events_user.c (ffffffff812c4e8b)
Location: include/linux/uio.h:199
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff815580fc)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff8157b45d)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/kernfs/file.c (ffffffff81584cfd)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write_iter
```
```
In fs/configfs/file.c (ffffffff81588eee)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
```
```
In security/keys/keyctl.c (ffffffff8168b41e)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/tty/tty_io.c (ffffffff81a941e2)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/char/random.c (ffffffff81adea12)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
```
```
In drivers/net/tun.c (ffffffff81c4a94d)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/datagram.c (ffffffff81e1f916)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81ea1378)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/netlink/af_netlink.c (ffffffff81ec8395)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81ef80cd)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81f0a630)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81f3ced1)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81f3e780)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81f6b93c)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81fe7a20)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81feed42)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820296d6)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff8208ccea)
Location: include/linux/uio.h:199
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108b347)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
```
```
In kernel/printk/printk.c (ffffffff811b253c)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In kernel/trace/trace_events_user.c (ffffffff812e175b)
Location: include/linux/uio.h:201
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8158e72c)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/proc_sysctl.c (ffffffff815b3d0d)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/kernfs/file.c (ffffffff815bd74d)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write_iter
```
```
In fs/configfs/file.c (ffffffff815c1abe)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
```
```
In security/keys/keyctl.c (ffffffff816c791e)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In block/bio-integrity.c (ffffffff817f925c)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_copy_user
```
```
In drivers/tty/tty_io.c (ffffffff81ae6c4e)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:iterate_tty_write
```
```
In drivers/char/random.c (ffffffff81b31e32)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
```
```
In drivers/net/tun.c (ffffffff81d002c7)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/datagram.c (ffffffff81edcfc6)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81f63b78)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/netlink/af_netlink.c (ffffffff81f8b75b)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81fbbe8b)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81fce630)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff82003146)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff82004a20)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff82031efc)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff820b5a10)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff820bc909)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820f9193)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mptcp/protocol.c (ffffffff8214cc77)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
```
In net/mctp/af_mctp.c (ffffffff821631b7)
Location: include/linux/uio.h:201
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In fs/iomap/direct-io.c (ffff80001042cda8)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In drivers/md/dm.c (ffff800010afda98)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffff800010bbbeb4)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffff800010c0f654)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffff800010c848a4)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (c05f5b80)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In net/core/datagram.c (c0cd82e8)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (c0d26e34)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (c0d93b94)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (c00000000053e6a0)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In drivers/md/dm.c (c000000000beecd0)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (c000000000c94f24)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (c000000000cfafa0)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (c000000000d90684)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (ffffffe0002ca136)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In drivers/md/dm.c (ffffffe0006efb1a)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffe00074aca2)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffe00078c138)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffe0007e62dc)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (ffffffff8135e4e7)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In drivers/md/dm.c (ffffffff8184f5c6)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff818c1812)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81908f49)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff81971b51)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (ffffffff8134f187)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In drivers/md/dm.c (ffffffff81816bd6)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff8187b752)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff818c2d59)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff8192b621)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (ffffffff8135bfb7)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In drivers/md/dm.c (ffffffff8189ebf6)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff81912812)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff81959f79)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff819dc321)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
In fs/iomap/direct-io.c (ffffffff8136f707)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In drivers/md/dm.c (ffffffff818bb4f6)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
```
```
In net/core/datagram.c (ffffffff81933992)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
```
In net/core/skmsg.c (ffffffff8197c199)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp_output.c (ffffffff819e5fa1)
Location: include/linux/uio.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
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
</ul>
