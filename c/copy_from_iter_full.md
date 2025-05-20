# Function: <code>copy_from_iter_full</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool copy_from_iter_full(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81462ac0)
Location: lib/iov_iter.c:574
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_write
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/udp.c:udplite_getfrag
  - net/ipv6/udp.c:udplite_getfrag
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81462ac0-ffffffff81462d80: copy_from_iter_full (STB_GLOBAL)
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
In kernel/printk/printk.c (ffffffff810e3b6e)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff8139224c)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff81694886)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff8180a149)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff818186ba)
Location: include/linux/uio.h:121
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81826e5d)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/raw.c (ffffffff818440dd)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818486a1)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81863462)
Location: include/linux/uio.h:121
Inline: True
```
```
In net/ipv6/udp.c (ffffffff818a98b1)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff818ac3b4)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff818d4e34)
Location: include/linux/uio.h:121
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In kernel/printk/printk.c (ffffffff810ebe0e)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff813b789c)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff816fe909)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff818890c9)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff8189781a)
Location: include/linux/uio.h:119
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a4d95)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff818c3a25)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c8561)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff818e35a2)
Location: include/linux/uio.h:119
Inline: True
```
```
In net/ipv6/udp.c (ffffffff8192ce51)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff8192f0da)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819598bc)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In kernel/printk/printk.c (ffffffff810f49de)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff813e8485)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff8173e5fa)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff818dca7d)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff818ebb2e)
Location: include/linux/uio.h:119
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818fa8c4)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff819199c2)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191cc47)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81939e3c)
Location: include/linux/uio.h:119
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819849e7)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81988023)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819b05ea)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In kernel/printk/printk.c (ffffffff811001de)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff81402c85)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff817624bb)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81909460)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff819190de)
Location: include/linux/uio.h:157
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8192878f)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff81947f02)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194bf07)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81969c8c)
Location: include/linux/uio.h:157
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bafc7)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff819be959)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e7e28)
Location: include/linux/uio.h:157
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056cc5)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff811089b4)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff8142f8c6)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff817a01f9)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff8196a775)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff8197b41e)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198b700)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff819accf9)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819b06cb)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff819d0953)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a29bbb)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81a2d9ef)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a549fe)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105756f)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff81114d94)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff81449626)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff817c51a9)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff819a11e4)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff819b226e)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c1f1f)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff819e38ad)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e467d)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81a074a3)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a5f64d)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81a6455a)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a8b5ee)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c82f)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff811203f0)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff8149af66)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff8188d8f7)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81a7ab1c)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81a9b8fe)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81aac5cf)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ad1155)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ad316d)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81af6d13)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81b584ed)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81b5cfc0)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b8703c)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b0af)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff8111b390)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/proc/proc_sysctl.c (ffffffff813d9259)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/keyctl.c (ffffffff814b7956)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff8189be37)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81a83972)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81aa575e)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81ab3f1f)
Location: include/linux/uio.h:150
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81add0b1)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81adfd8d)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81b03ba3)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81b66b2d)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81b6b801)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b96ba6)
Location: include/linux/uio.h:150
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105ba5f)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff8111ba70)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/proc/proc_sysctl.c (ffffffff813e06f9)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/keyctl.c (ffffffff814bd7ca)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff8187e3b7)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81a6ca5f)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81a9081e)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81a9f08f)
Location: include/linux/uio.h:158
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ac811f)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81acab6d)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81aef7e3)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81b54cfd)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81b59b48)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b85ba6)
Location: include/linux/uio.h:158
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff8113c165)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/proc/proc_sysctl.c (ffffffff8143212b)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/keyctl.c (ffffffff815161ca)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff8190fba8)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81b260bc)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81b4b9de)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81b5a1ce)
Location: include/linux/uio.h:166
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b86988)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81b88a40)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81baf7e8)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81c1b4a0)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81c2116e)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81c51f46)
Location: include/linux/uio.h:166
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
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff8115eedf)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/proc/proc_sysctl.c (ffffffff814acbfa)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/keyctl.c (ffffffff815a8a6e)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff81a6681b)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81caece5)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81cd90ae)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81ce8520)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81d173e5)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81d19ba0)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81d42cec)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81db7790)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81dbdece)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81df42de)
Location: include/linux/uio.h:175
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff81e37277)
Location: include/linux/uio.h:175
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
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff81191eff)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/proc/proc_sysctl.c (ffffffff8154301a)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/keyctl.c (ffffffff81652bfe)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff81bf1ceb)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81e6c335)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81e997ce)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81eabe70)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81eddc22)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ee05c0)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81f0bccc)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81f87590)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81f8e469)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81fc8d6d)
Location: include/linux/uio.h:192
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff820100b7)
Location: include/linux/uio.h:192
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
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff811a379c)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/proc/proc_sysctl.c (ffffffff8157b45d)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/keyctl.c (ffffffff8168b41e)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff81c4a94d)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81ec8395)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81ef80cd)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81f0a630)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81f3ced1)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81f3e780)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81f6b93c)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff81fe7a20)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81feed42)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820296d6)
Location: include/linux/uio.h:207
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff8208ccea)
Location: include/linux/uio.h:207
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
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
```
```
In kernel/printk/printk.c (ffffffff811b253c)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In fs/proc/proc_sysctl.c (ffffffff815b3d0d)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In security/keys/keyctl.c (ffffffff816c791e)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In block/bio-integrity.c (ffffffff817f925c)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_copy_user
```
```
In drivers/net/tun.c (ffffffff81d002c7)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81f8b75b)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff81fbbe8b)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81fce630)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff82003146)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff82004a20)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff82031efc)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/udp.c (ffffffff820b5a10)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff820bc909)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820f9193)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mptcp/protocol.c (ffffffff8214cc77)
Location: include/linux/uio.h:209
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
```
In net/mctp/af_mctp.c (ffffffff821631b7)
Location: include/linux/uio.h:209
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
In kernel/printk/printk.c (ffff800010175e94)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffff80001053326c)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffff8000109e0488)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffff800010c4f87c)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffff800010c61e8c)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c74c58)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffff800010c98388)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c998e4)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffff800010cc03ec)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d23ecc)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffff800010d2a44c)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffff800010d5a0e4)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In kernel/printk/printk.c (c03c80b8)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (c06eab08)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (c0ac45c8)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (c0d5fa28)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (c0d7188c)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (c0d833e8)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (c0da6250)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0da7404)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (c0dcc714)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (c0e28928)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (c0e2e4b0)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (c0e58b78)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In kernel/printk/printk.c (c0000000001cf8b0)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (c000000000680e80)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (c000000000aa1800)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (c000000000d4e210)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (c000000000d662f0)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7c1fc)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (c000000000da9754)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000dadb30)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (c000000000ddb610)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (c000000000e54b20)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (c000000000e5b578)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (c000000000e943cc)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In kernel/printk/printk.c (ffffffe000111522)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffe0003938d4)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffe00062a064)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffe0007bb49e)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffe0007ca836)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d80cc)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffe0007f6668)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f95be)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffe000816c70)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (ffffffe000866ae6)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffe00086ac7c)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffe00088ff9c)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810570ef)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff8110d374)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff81441c06)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff81789c89)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff81941054)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff819520de)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81961d8f)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff8198371d)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819844ed)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff819a7243)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819fecdd)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81a03bea)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a2ac7e)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810472df)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff810fe0f4)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff81432676)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff817695d9)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff818fab44)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff8190bbce)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191b87f)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff8193d1dd)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193dfad)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81960d03)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bba9d)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff819c09aa)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff819e7e6e)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105751f)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff8110b264)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff8143dda6)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff817ba029)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff819921e4)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff819bc8ae)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819cc55f)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff819edeed)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819eecbd)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81a11ae3)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6975d)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81a6e66a)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a9682e)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810589bf)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
```
In kernel/printk/printk.c (ffffffff81116734)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_write
```
```
In security/keys/keyctl.c (ffffffff81454f26)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
```
In drivers/net/tun.c (ffffffff817d2529)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In net/netlink/af_netlink.c (ffffffff819b4cd4)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/ip_output.c (ffffffff819c61be)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d60ef)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/raw.c (ffffffff819f7e25)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819f8e2d)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv4/udp.c:udplite_getfrag
```
```
In net/ipv4/ping.c (ffffffff81a1c453)
Location: include/linux/uio.h:151
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a75d3d)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/udp.c:udplite_getfrag
```
```
In net/ipv6/raw.c (ffffffff81a7ac9c)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81aa34a8)
Location: include/linux/uio.h:151
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
