# Function: <code>dev_queue_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171d2d0)
Location: net/core/dev.c:3184
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_xmit
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:skb_do_redirect
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
**Symbols:**

```
ffffffff8171d2d0-ffffffff8171d2e2: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81785ba0)
Location: net/core/dev.c:3436
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81785ba0-ffffffff81785bb2: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b3160)
Location: net/core/dev.c:3430
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff817b3160-ffffffff817b3172: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d0960)
Location: net/core/dev.c:3511
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff817d0960-ffffffff817d0972: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184a410)
Location: net/core/dev.c:3557
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff8184a410-ffffffff8184a422: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81894730)
Location: net/core/dev.c:3600
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81894730-ffffffff81894742: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b696c)
Location: net/core/dev.c:3895
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff818b5140-ffffffff818b5152: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81901b30)
Location: net/core/dev.c:3904
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81901b30-ffffffff81901b42: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81933d70)
Location: net/core/dev.c:3804
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81933d70-ffffffff81933d82: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a08790)
Location: net/core/dev.c:4162
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81a08790-ffffffff81a087a2: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a09d50)
Location: net/core/dev.c:4194
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:neigh_hh_output
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81a09d50-ffffffff81a09d62: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f06e0)
Location: net/core/dev.c:4277
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:neigh_hh_output
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:neigh_hh_output
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:neigh_hh_output
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff819f06e0-ffffffff819f06f2: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa1b40)
Location: net/core/dev.c:4245
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/netlink/af_netlink.c:__netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81aa1b40-ffffffff81aa1b52: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81c29bed)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81c4929e)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:neigh_hh_output
```
```
In net/netlink/af_netlink.c (ffffffff81caad7a)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/ip_output.c (ffffffff81cd8dde)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/arp.c (ffffffff81d21a97)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv6/ip6_output.c (ffffffff81d8708e)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/seg6_local.c (ffffffff81de8fc2)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81df79e5)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81e0e56a)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/mctp/route.c (ffffffff81e38e19)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff81df0870-ffffffff81df0885: dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81ddc92d)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81dfdc8d)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:neigh_hh_output
```
```
In net/netlink/af_netlink.c (ffffffff81e67ec7)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/ip_output.c (ffffffff81e9971e)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/arp.c (ffffffff81ee8e42)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv6/ip6_output.c (ffffffff81f5502e)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc6f2)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff81fcc000)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81fe4986)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/mctp/route.c (ffffffff820120a9)
Location: include/linux/netdevice.h:3031
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff81fc4a50-ffffffff81fc4a65: dev_queue_xmit (STB_LOCAL)
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
In drivers/net/net_failover.c (ffffffff81c6f2b5)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_start_xmit
```
```
In net/core/neighbour.c (ffffffff81e4d67b)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81e6f20a)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:neigh_hh_output
```
```
In net/netlink/af_netlink.c (ffffffff81ec3d1f)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/ip_output.c (ffffffff81ef801e)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/arp.c (ffffffff81f48802)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4a3e)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/seg6_local.c (ffffffff8201cfe2)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff8202d335)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_xmit
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82060c96)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/mctp/route.c (ffffffff8208ee90)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_output
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
In drivers/net/net_failover.c (ffffffff81d23b85)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_start_xmit
```
```
In net/core/neighbour.c (ffffffff81f0c3d8)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81f2e84a)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:neigh_hh_output
```
```
In net/netlink/af_netlink.c (ffffffff81f870df)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ipv4/ip_output.c (ffffffff81fbc06e)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/arp.c (ffffffff8200e962)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv6/ip6_output.c (ffffffff820820de)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/seg6_local.c (ffffffff820ebfc2)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff820fcdb9)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_xmit
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82133bb3)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/mctp/route.c (ffffffff82165336)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_output
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
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd1fe0)
Location: net/core/dev.c:3804
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffff800010bd1fe0-ffff800010bd2010: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cecbf8)
Location: net/core/dev.c:3804
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
c0cecbf8-c0cecc18: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb05a0)
Location: net/core/dev.c:3804
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
c000000000cb05a0-c000000000cb05b8: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075c58c)
Location: net/core/dev.c:3804
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffe00075c58c-ffffffe00075c5b8: dev_queue_xmit (STB_GLOBAL)
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
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d3d70)
Location: net/core/dev.c:3804
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff818d3d70-ffffffff818d3d82: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188dc00)
Location: net/core/dev.c:3804
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff8188dc00-ffffffff8188dc12: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81924d70)
Location: net/core/dev.c:3804
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81924d70-ffffffff81924d82: dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81946220)
Location: net/core/dev.c:3804
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_direct_output
  - net/core/neighbour.c:neigh_connected_output
  - net/core/filter.c:__bpf_redirect
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/arp.c:arp_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81946220-ffffffff81946232: dev_queue_xmit (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
