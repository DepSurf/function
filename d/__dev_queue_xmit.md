# Function: <code>__dev_queue_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171cd40)
Location: net/core/dev.c:3075
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit
  - net/core/dev.c:dev_queue_xmit_accel
```
**Symbols:**

```
ffffffff8171cd40-ffffffff8171d2cf: __dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817854d0)
Location: net/core/dev.c:3320
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff817854d0-ffffffff81785b99: __dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b2ae0)
Location: net/core/dev.c:3324
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff817b2ae0-ffffffff817b3160: __dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d02e0)
Location: net/core/dev.c:3405
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff817d02e0-ffffffff817d095f: __dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81849c40)
Location: net/core/dev.c:3451
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff81849c40-ffffffff8184a410: __dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, void *accel_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3493
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff81893e40-ffffffff8189472b: __dev_queue_xmit (STB_LOCAL)
ffffffff81899097-ffffffff818990bf: __dev_queue_xmit.cold.163 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3788
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_accel
```
**Symbols:**

```
ffffffff818b4830-ffffffff818b5139: __dev_queue_xmit (STB_LOCAL)
ffffffff818bb539-ffffffff818bb561: __dev_queue_xmit.cold.170 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3798
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff81901160-ffffffff81901b2b: __dev_queue_xmit (STB_LOCAL)
ffffffff81907428-ffffffff81907450: __dev_queue_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3698
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff81933490-ffffffff81933d6d: __dev_queue_xmit (STB_LOCAL)
ffffffff81939a22-ffffffff81939a4a: __dev_queue_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4056
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff81a08300-ffffffff81a08781: __dev_queue_xmit (STB_LOCAL)
ffffffff81a0efea-ffffffff81a0f012: __dev_queue_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4087
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff81a09890-ffffffff81a09d43: __dev_queue_xmit (STB_LOCAL)
ffffffff81c31312-ffffffff81c3133a: __dev_queue_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4170
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff819f0200-ffffffff819f06d9: __dev_queue_xmit (STB_LOCAL)
ffffffff81c235d8-ffffffff81c23600: __dev_queue_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4135
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff81aa1630-ffffffff81aa1b36: __dev_queue_xmit (STB_LOCAL)
ffffffff81d36396-ffffffff81d363be: __dev_queue_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4162
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
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff81f02b68-ffffffff81f02bae: __dev_queue_xmit.cold (STB_LOCAL)
ffffffff81c19670-ffffffff81c19d50: __dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dca6b0)
Location: net/core/dev.c:4149
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
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff81dca6b0-ffffffff81dcadb7: __dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3b230)
Location: net/core/dev.c:4109
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_start_xmit
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
  - net/packet/af_packet.c:packet_xmit
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff81e3b230-ffffffff81e3b93a: __dev_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef95f0)
Location: net/core/dev.c:4259
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_start_xmit
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
  - net/packet/af_packet.c:packet_xmit
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/mctp/route.c:mctp_route_output
```
**Symbols:**

```
ffffffff81ef95f0-ffffffff81ef9e73: __dev_queue_xmit (STB_GLOBAL)
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
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd15a0)
Location: net/core/dev.c:3698
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffff800010bd15a0-ffff800010bd1fe0: __dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cec1c8)
Location: net/core/dev.c:3698
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
c0cec1c8-c0cecbf8: __dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caf910)
Location: net/core/dev.c:3698
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
c000000000caf910-c000000000cb05a0: __dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075ba88)
Location: net/core/dev.c:3698
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffe00075ba88-ffffffe00075c58c: __dev_queue_xmit (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3698
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff818d3490-ffffffff818d3d6d: __dev_queue_xmit (STB_LOCAL)
ffffffff818d99f2-ffffffff818d9a1a: __dev_queue_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3698
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff8188d320-ffffffff8188dbfd: __dev_queue_xmit (STB_LOCAL)
ffffffff81893832-ffffffff8189385a: __dev_queue_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3698
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff81924490-ffffffff81924d6d: __dev_queue_xmit (STB_LOCAL)
ffffffff8192aa22-ffffffff8192aa4a: __dev_queue_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __dev_queue_xmit(struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3698
Inline: False
Direct callers:
  - net/core/dev.c:dev_queue_xmit_accel
  - net/core/dev.c:dev_queue_xmit
```
**Symbols:**

```
ffffffff81945920-ffffffff8194621d: __dev_queue_xmit (STB_LOCAL)
ffffffff8194c0f2-ffffffff8194c11a: __dev_queue_xmit.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *sb_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>void *accel_priv</code>
</li>
</ul>
</details>
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
