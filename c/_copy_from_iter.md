# Function: <code>_copy_from_iter</code>

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
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81467740)
Location: lib/iov_iter.c:576
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81467740-ffffffff81467a2b: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814939c0)
Location: lib/iov_iter.c:576
Inline: False
Direct callers:
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff814939c0-ffffffff81493ca9: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c8cd0)
Location: lib/iov_iter.c:692
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff814c8cd0-ffffffff814c8faf: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dd430)
Location: lib/iov_iter.c:736
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_actor
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff814dd430-ffffffff814dd72f: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff8150adc7-ffffffff8150addd: _copy_from_iter.cold (STB_LOCAL)
ffffffff81508630-ffffffff815089b3: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81526fb0)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff81526fb0-ffffffff8152733a: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158bb40)
Location: lib/iov_iter.c:758
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff8158bb40-ffffffff8158beff: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a6b10)
Location: lib/iov_iter.c:765
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff815a6b10-ffffffff815a6ddf: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815af3b0)
Location: lib/iov_iter.c:800
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff815af3b0-ffffffff815afaa1: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81616750)
Location: lib/iov_iter.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff81616750-ffffffff81616d17: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:766
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/char/random.c:write_pool_user
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff81e93118-ffffffff81e93164: _copy_from_iter.cold (STB_LOCAL)
ffffffff816e4c40-ffffffff816e52d1: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:627
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/char/random.c:write_pool_user
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff8207814f-ffffffff820781a6: _copy_from_iter.cold (STB_LOCAL)
ffffffff817d34d0-ffffffff817d3aa0: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - kernel/printk/printk.c:devkmsg_write
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/char/random.c:write_pool_user
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff820f8578-ffffffff820f85da: _copy_from_iter.cold (STB_LOCAL)
ffffffff81811e30-ffffffff818122d0: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:253
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - kernel/printk/printk.c:devkmsg_write
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/configfs/file.c:configfs_bin_write_iter
  - fs/configfs/file.c:configfs_write_iter
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - block/bio-integrity.c:bio_integrity_copy_user
  - drivers/tty/tty_io.c:iterate_tty_write
  - drivers/char/random.c:write_pool_user
  - drivers/dax/super.c:dax_copy_from_iter
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_output.c:ip_generic_getfrag
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv4/ping.c:ping_common_sendmsg
  - net/ipv6/udp.c:udplite_getfrag
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff821d6282-ffffffff821d6297: _copy_from_iter.cold (STB_LOCAL)
ffffffff81857d00-ffffffff81858287: _copy_from_iter (STB_GLOBAL)
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
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff800010631720)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffff800010631720-ffff800010631a7c: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d7aa0)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:copy_page_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
c07d7aa0-c07d7e48: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d6680)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
c0000000007d6680-c0000000007d6b88: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe000460330)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - lib/iov_iter.c:copy_page_from_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffe000460330-ffffffe0004605f6: _copy_from_iter (STB_GLOBAL)
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
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151f590)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff8151f590-ffffffff8151f91a: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150f880)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff8150f880-ffffffff8150fc0a: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151b620)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff8151b620-ffffffff8151b9aa: _copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t _copy_from_iter(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81534e60)
Location: lib/iov_iter.c:737
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff81534e60-ffffffff815351ea: _copy_from_iter (STB_GLOBAL)
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
