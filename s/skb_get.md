# Function: <code>skb_get</code>

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
In kernel/audit.c (ffffffff81120dab)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_skb
```
```
In drivers/connector/connector.c (ffffffff81541bd2)
Location: include/linux/skbuff.h:1201
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff815fa332)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff8170836a)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/netlink/af_netlink.c (ffffffff8174bc15)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff817bf5cb)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81807233)
Location: include/linux/skbuff.h:1201
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In kernel/audit.c (ffffffff81128cfb)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_skb
```
```
In drivers/connector/connector.c (ffffffff81593512)
Location: include/linux/skbuff.h:1292
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8165a1f2)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff8176f060)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff817b8be6)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff8182c618)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81877de9)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8188c48e)
Location: include/linux/skbuff.h:1292
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff8113266c)
Location: include/linux/skbuff.h:1307
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_unicast_skb
```
```
In drivers/connector/connector.c (ffffffff815c0dd2)
Location: include/linux/skbuff.h:1307
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81687f42)
Location: include/linux/skbuff.h:1307
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff8179c550)
Location: include/linux/skbuff.h:1307
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff817e8696)
Location: include/linux/skbuff.h:1307
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff8185e0cf)
Location: include/linux/skbuff.h:1307
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff818ab658)
Location: include/linux/skbuff.h:1307
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818c063d)
Location: include/linux/skbuff.h:1307
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff81133ccf)
Location: include/linux/skbuff.h:1300
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff815d6908)
Location: include/linux/skbuff.h:1300
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8169d2e2)
Location: include/linux/skbuff.h:1300
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff817bd47f)
Location: include/linux/skbuff.h:1300
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff81808666)
Location: include/linux/skbuff.h:1300
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff818835ba)
Location: include/linux/skbuff.h:1300
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff818d48f3)
Location: include/linux/skbuff.h:1300
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818e6fab)
Location: include/linux/skbuff.h:1300
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff81140a81)
Location: include/linux/skbuff.h:1402
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff8163d6d8)
Location: include/linux/skbuff.h:1402
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81708345)
Location: include/linux/skbuff.h:1402
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff81835855)
Location: include/linux/skbuff.h:1402
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff818874d8)
Location: include/linux/skbuff.h:1402
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff81903caf)
Location: include/linux/skbuff.h:1402
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff8195937d)
Location: include/linux/skbuff.h:1402
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8196c464)
Location: include/linux/skbuff.h:1402
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff81975ac9)
Location: include/linux/skbuff.h:1402
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8114f3c1)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff81678cd6)
Location: include/linux/skbuff.h:1413
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81747012)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff8187fbc8)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff818dabc6)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8d49)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/unix/af_unix.c (ffffffff8195bdd4)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ipv6/reassembly.c (ffffffff819905a7)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
```
In net/packet/af_packet.c (ffffffff819b3105)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819c5f1e)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff819d219b)
Location: include/linux/skbuff.h:1413
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8115c0a1)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff81697dc3)
Location: include/linux/skbuff.h:1482
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8176b122)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff818a0839)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff819074a5)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff819905ee)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/ipv6/reassembly.c (ffffffff819c7cde)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/packet/af_packet.c (ffffffff819ea059)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819fd680)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff81a0b53d)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff81168755)
Location: include/linux/skbuff.h:1572
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff816d094f)
Location: include/linux/skbuff.h:1572
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817a8f22)
Location: include/linux/skbuff.h:1572
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff818eb27d)
Location: include/linux/skbuff.h:1572
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff8196875d)
Location: include/linux/skbuff.h:1572
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff819fbcdd)
Location: include/linux/skbuff.h:1572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81a5868b)
Location: include/linux/skbuff.h:1572
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a6c8e6)
Location: include/linux/skbuff.h:1572
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff81a7af2a)
Location: include/linux/skbuff.h:1572
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff811745f5)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff816f476f)
Location: include/linux/skbuff.h:1582
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817cc992)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff8191d3dd)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff8199f1fd)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff81a3296d)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81a90cf3)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aa32a6)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff81ab228a)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff81186785)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In lib/kobject_uevent.c (ffffffff815ec2a8)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
```
```
In drivers/connector/connector.c (ffffffff817ad295)
Location: include/linux/skbuff.h:1593
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81898505)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff819f18eb)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
```
```
In net/netlink/af_netlink.c (ffffffff81a78f13)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/unix/af_unix.c (ffffffff81b2742a)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81b8c165)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9ed3a)
Location: include/linux/skbuff.h:1593
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff81183945)
Location: include/linux/skbuff.h:1614
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In lib/kobject_uevent.c (ffffffff81610a88)
Location: include/linux/skbuff.h:1614
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
```
```
In drivers/connector/connector.c (ffffffff817c1e25)
Location: include/linux/skbuff.h:1614
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff818a68c5)
Location: include/linux/skbuff.h:1614
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff819f1ec5)
Location: include/linux/skbuff.h:1614
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
```
```
In net/netlink/af_netlink.c (ffffffff81a81743)
Location: include/linux/skbuff.h:1614
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/unix/af_unix.c (ffffffff81b35d0b)
Location: include/linux/skbuff.h:1614
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81b9b5b3)
Location: include/linux/skbuff.h:1614
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81bae73a)
Location: include/linux/skbuff.h:1614
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff811849b5)
Location: include/linux/skbuff.h:1630
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In lib/kobject_uevent.c (ffffffff815f4176)
Location: include/linux/skbuff.h:1630
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/connector/connector.c (ffffffff817a522f)
Location: include/linux/skbuff.h:1630
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81889ff0)
Location: include/linux/skbuff.h:1630
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff819d7d66)
Location: include/linux/skbuff.h:1630
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
```
```
In net/netlink/af_netlink.c (ffffffff81a6a850)
Location: include/linux/skbuff.h:1630
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/unix/af_unix.c (ffffffff81b238e1)
Location: include/linux/skbuff.h:1630
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81b8af5d)
Location: include/linux/skbuff.h:1630
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9d858)
Location: include/linux/skbuff.h:1630
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff811acc11)
Location: include/linux/skbuff.h:1643
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In lib/kobject_uevent.c (ffffffff816614e6)
Location: include/linux/skbuff.h:1643
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/connector/connector.c (ffffffff81830baf)
Location: include/linux/skbuff.h:1643
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8191cbb0)
Location: include/linux/skbuff.h:1643
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff81a87bb6)
Location: include/linux/skbuff.h:1643
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
```
```
In net/netlink/af_netlink.c (ffffffff81b23e50)
Location: include/linux/skbuff.h:1643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/unix/af_unix.c (ffffffff81be7db4)
Location: include/linux/skbuff.h:1643
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81c57207)
Location: include/linux/skbuff.h:1643
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81c6adea)
Location: include/linux/skbuff.h:1643
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff811de7d1)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In lib/kobject_uevent.c (ffffffff8177b294)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/connector/connector.c (ffffffff81971fc9)
Location: include/linux/skbuff.h:1992
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81a7215f)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff81bfcfe7)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
```
```
In net/netlink/af_netlink.c (ffffffff81cad64a)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/unix/af_unix.c (ffffffff81d7f6f2)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81df6629)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81e0e54a)
Location: include/linux/skbuff.h:1992
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In kernel/audit.c (ffffffff81224381)
Location: include/linux/skbuff.h:1850
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff81add269)
Location: include/linux/skbuff.h:1850
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c04a0f)
Location: include/linux/skbuff.h:1850
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff81dac925)
Location: include/linux/skbuff.h:1850
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/skmsg.c (ffffffff81e4829c)
Location: include/linux/skbuff.h:1850
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
```
```
In net/netlink/af_netlink.c (ffffffff81e6abfa)
Location: include/linux/skbuff.h:1850
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/unix/af_unix.c (ffffffff81f4d3e2)
Location: include/linux/skbuff.h:1850
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:queue_oob
```
```
In net/packet/af_packet.c (ffffffff81fcabb6)
Location: include/linux/skbuff.h:1850
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81fe495e)
Location: include/linux/skbuff.h:1850
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff820244a4)
Location: include/linux/skbuff.h:1850
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In kernel/audit.c (ffffffff8123a961)
Location: include/linux/skbuff.h:1886
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff81b2b4d9)
Location: include/linux/skbuff.h:1886
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a11f)
Location: include/linux/skbuff.h:1886
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff81e1c715)
Location: include/linux/skbuff.h:1886
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
```
```
In net/netlink/af_netlink.c (ffffffff81ec706a)
Location: include/linux/skbuff.h:1886
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/unix/af_unix.c (ffffffff81face1b)
Location: include/linux/skbuff.h:1886
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:queue_oob
```
```
In net/packet/af_packet.c (ffffffff8202b8f9)
Location: include/linux/skbuff.h:1886
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82060c6e)
Location: include/linux/skbuff.h:1886
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff820a45b4)
Location: include/linux/skbuff.h:1886
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In kernel/audit.c (ffffffff81254651)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff81b82879)
Location: include/linux/skbuff.h:1893
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81d1eaff)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff81ed9e15)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
```
```
In net/core/skmsg.c (ffffffff81f655de)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/netlink/af_netlink.c (ffffffff81f8a314)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_one_broadcast
```
```
In net/unix/af_unix.c (ffffffff8207b273)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:queue_oob
```
```
In net/packet/af_packet.c (ffffffff820fb3ad)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82133b8b)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff8217c684)
Location: include/linux/skbuff.h:1893
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In kernel/audit.c (ffff8000101e9014)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffff8000108dda70)
Location: include/linux/skbuff.h:1582
Inline: True
```
```
In drivers/net/xen-netfront.c (ffff800010a06968)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffff800010bb7dc8)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffff800010c4c4cc)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffff800010cf20dc)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffff800010d5e50c)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffff800010d74d48)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffff800010d8c484)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (c0428ffc)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (c09ccb90)
Location: include/linux/skbuff.h:1582
Inline: True
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0d08)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_find_ts
```
```
In net/core/skbuff.c (c0cd49bc)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (c0d5d22c)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (c0dfa01c)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (c0e5d0a8)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (c0e7181c)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (c0e86860)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (c000000000259c04)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (c000000000971254)
Location: include/linux/skbuff.h:1582
Inline: True
```
```
In net/core/skbuff.c (c000000000c8fbf0)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (c000000000d4ae10)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (c000000000e184d0)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (c000000000e97258)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (c000000000eb46a4)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (c000000000ece4b4)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffe00015ded0)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffe000574122)
Location: include/linux/skbuff.h:1582
Inline: True
```
```
In net/core/skbuff.c (ffffffe000747738)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffe0007b986c)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffe00083f26c)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffe000894190)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffe0008a4d86)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffe0008b565a)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8116cc15)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff816b9f5f)
Location: include/linux/skbuff.h:1582
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81791472)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff818bd3dd)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff8193f06d)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff819d1ffd)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81a30383)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a42636)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff81a510da)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8115fdb5)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff81697b9f)
Location: include/linux/skbuff.h:1582
Inline: True
```
```
In net/core/skbuff.c (ffffffff8187731d)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff818f8b6d)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff8198edbd)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff819ed573)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819ff226)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff81a0e1da)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff8116a9e5)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff816e842f)
Location: include/linux/skbuff.h:1582
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817c1812)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff8190e3dd)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff819901fd)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff81a3ca7d)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81a9bf33)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aae4e6)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff81abd4ca)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In kernel/audit.c (ffffffff811781a5)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_send_queue
```
```
In drivers/connector/connector.c (ffffffff81702b2f)
Location: include/linux/skbuff.h:1582
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817dbad2)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In net/core/skbuff.c (ffffffff8192f50d)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/netlink/af_netlink.c (ffffffff819b2acc)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/unix/af_unix.c (ffffffff81a4803b)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
```
In net/packet/af_packet.c (ffffffff81aa66e7)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aba896)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In lib/kobject_uevent.c (ffffffff81ac994a)
Location: include/linux/skbuff.h:1582
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
</ul>

## Differences
