# Function: <code>skb_pull_rcsum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned char *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81706ab0)
Location: net/core/skbuff.c:3032
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
**Symbols:**

```
ffffffff81706ab0-ffffffff81706b4b: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned char *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176cdc0)
Location: net/core/skbuff.c:3030
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff8176cdc0-ffffffff8176ce5c: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned char *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179a240)
Location: net/core/skbuff.c:3027
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff8179a240-ffffffff8179a2dc: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b98e0)
Location: net/core/skbuff.c:3068
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff817b98e0-ffffffff817b9984: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81832810)
Location: net/core/skbuff.c:3450
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff81832810-ffffffff818328b6: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187ccd0)
Location: net/core/skbuff.c:3466
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff8187ccd0-ffffffff8187cd76: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d960)
Location: net/core/skbuff.c:3445
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff8189d960-ffffffff8189d9f9: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e8940)
Location: net/core/skbuff.c:3611
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff818e8940-ffffffff818e89d2: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191a120)
Location: net/core/skbuff.c:3617
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff8191a120-ffffffff8191a1b2: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb5f0)
Location: net/core/skbuff.c:3616
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819eb5f0-ffffffff819eb68a: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb310)
Location: net/core/skbuff.c:3666
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819eb310-ffffffff819eb3aa: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1820)
Location: net/core/skbuff.c:3751
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819d1820-ffffffff819d18b8: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a812e0)
Location: net/core/skbuff.c:3811
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81a812e0-ffffffff81a81378: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf4fa0)
Location: net/core/skbuff.c:3861
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81bf4fa0-ffffffff81bf5053: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2e00)
Location: net/core/skbuff.c:4063
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81da2e00-ffffffff81da2eb3: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e119c0)
Location: net/core/skbuff.c:4233
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
**Symbols:**

```
ffffffff81e119c0-ffffffff81e11a73: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81eceb80)
Location: net/core/skbuff.c:4355
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_eth_pop
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
**Symbols:**

```
ffffffff81eceb80-ffffffff81ecec33: skb_pull_rcsum (STB_GLOBAL)
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
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb3070)
Location: net/core/skbuff.c:3617
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffff800010bb3070-ffff800010bb3138: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd1130)
Location: net/core/skbuff.c:3617
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
c0cd1130-c0cd11e0: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8bc70)
Location: net/core/skbuff.c:3617
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
c000000000c8bc70-c000000000c8bd74: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744eb2)
Location: net/core/skbuff.c:3617
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffe000744eb2-ffffffe000744f64: skb_pull_rcsum (STB_GLOBAL)
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
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ba120)
Location: net/core/skbuff.c:3617
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff818ba120-ffffffff818ba1b2: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81874070)
Location: net/core/skbuff.c:3617
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81874070-ffffffff81874102: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190b120)
Location: net/core/skbuff.c:3617
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff8190b120-ffffffff8190b1b2: skb_pull_rcsum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *skb_pull_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192c220)
Location: net/core/skbuff.c:3617
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff8192c220-ffffffff8192c2b2: skb_pull_rcsum (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned char *</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
