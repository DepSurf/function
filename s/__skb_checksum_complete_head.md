# Function: <code>__skb_checksum_complete_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8170d740)
Location: net/core/datagram.c:651
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
**Symbols:**

```
ffffffff8170d740-ffffffff8170d7ce: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81774d90)
Location: net/core/datagram.c:673
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
**Symbols:**

```
ffffffff81774d90-ffffffff81774e22: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a2090)
Location: net/core/datagram.c:693
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
**Symbols:**

```
ffffffff817a2090-ffffffff817a2122: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817bf900)
Location: net/core/datagram.c:719
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
**Symbols:**

```
ffffffff817bf900-ffffffff817bf98b: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818394b0)
Location: net/core/datagram.c:733
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
**Symbols:**

```
ffffffff818394b0-ffffffff8183953b: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81883be0)
Location: net/core/datagram.c:731
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/netfilter.c:nf_ip_checksum_partial
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
**Symbols:**

```
ffffffff81883be0-ffffffff81883c6e: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189bb80)
Location: net/core/skbuff.c:2642
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8189bb80-ffffffff8189bc48: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e6470)
Location: net/core/skbuff.c:2808
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff818e6470-ffffffff818e6538: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819185b0)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819185b0-ffffffff81918678: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb430)
Location: net/core/skbuff.c:2809
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819eb430-ffffffff819eb4f7: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb150)
Location: net/core/skbuff.c:2827
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819eb150-ffffffff819eb217: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1660)
Location: net/core/skbuff.c:2910
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819d1660-ffffffff819d1730: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a81120)
Location: net/core/skbuff.c:2982
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81a81120-ffffffff81a811f0: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf5c10)
Location: net/core/skbuff.c:3031
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81bf5c10-ffffffff81bf5cef: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da3e60)
Location: net/core/skbuff.c:3237
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81da3e60-ffffffff81da3f3f: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e12ad0)
Location: net/core/skbuff.c:3407
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81e12ad0-ffffffff81e12baf: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecfc90)
Location: net/core/skbuff.c:3495
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81ecfc90-ffffffff81ecfd6f: __skb_checksum_complete_head (STB_GLOBAL)
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
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb18f8)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffff800010bb18f8-ffff800010bb19d8: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf47c)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c0ccf47c-c0ccf55c: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c88f10)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c000000000c88f10-c000000000c89010: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000743304)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffe000743304-ffffffe0007433ca: __skb_checksum_complete_head (STB_GLOBAL)
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
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b85b0)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff818b85b0-ffffffff818b8678: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81872500)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81872500-ffffffff818725c8: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819095b0)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819095b0-ffffffff81909678: __skb_checksum_complete_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__sum16 __skb_checksum_complete_head(struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192a6a0)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_checksum_partial
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8192a6a0-ffffffff8192a768: __skb_checksum_complete_head (STB_GLOBAL)
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
