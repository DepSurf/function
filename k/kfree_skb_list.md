# Function: <code>kfree_skb_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817060a0)
Location: net/core/skbuff.c:708
Inline: True
Inline callers:
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_segment
Direct callers:
  - net/core/skbuff.c:skb_release_data
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff817060a0-ffffffff817060c3: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81772e3d)
Location: net/core/skbuff.c:709
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
Direct callers:
  - net/core/skbuff.c:skb_release_data
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff8176e110-ffffffff8176e133: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179ffce)
Location: net/core/skbuff.c:709
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
Direct callers:
  - net/core/skbuff.c:skb_release_data
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff8179b550-ffffffff8179b573: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817befd0)
Location: net/core/skbuff.c:703
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff817bb570-ffffffff817bb594: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81838901)
Location: net/core/skbuff.c:663
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81833610-ffffffff81833634: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81882f45)
Location: net/core/skbuff.c:663
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff8187dab0-ffffffff8187dad3: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a39a2)
Location: net/core/skbuff.c:667
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff8189e680-ffffffff8189e6a3: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ee725)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff818e8ef0-ffffffff818e8f16: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81920821)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff8191b050-ffffffff8191b076: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819efc83)
Location: net/core/skbuff.c:700
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff819edd60-ffffffff819edd89: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ef92c)
Location: net/core/skbuff.c:714
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff819eda00-ffffffff819eda29: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819da03f)
Location: net/core/skbuff.c:762
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff819d3690-ffffffff819d36b9: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a8a0a9)
Location: net/core/skbuff.c:778
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81a833f0-ffffffff81a83419: kfree_skb_list (STB_GLOBAL)
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
In net/core/skbuff.c (ffffffff81bfd489)
Location: include/linux/skbuff.h:1384
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81c19262)
Location: include/linux/skbuff.h:1384
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81cda574)
Location: include/linux/skbuff.h:1384
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7818f)
Location: include/linux/skbuff.h:1384
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a44a)
Location: include/linux/skbuff.h:1384
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a7ec)
Location: include/linux/skbuff.h:1384
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81de14b0)
Location: include/linux/skbuff.h:1384
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee7e3)
Location: include/linux/skbuff.h:1384
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/skbuff.c (ffffffff81dac305)
Location: include/linux/skbuff.h:1227
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff81dca262)
Location: include/linux/skbuff.h:1227
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81e9ad34)
Location: include/linux/skbuff.h:1227
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44a2f)
Location: include/linux/skbuff.h:1227
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81f473a0)
Location: include/linux/skbuff.h:1227
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81f58780)
Location: include/linux/skbuff.h:1227
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff81fb3910)
Location: include/linux/skbuff.h:1227
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc23d6)
Location: include/linux/skbuff.h:1227
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/skbuff.c (ffffffff81e1c186)
Location: include/linux/skbuff.h:1246
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff81e3ade2)
Location: include/linux/skbuff.h:1246
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81ef96c9)
Location: include/linux/skbuff.h:1246
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa420f)
Location: include/linux/skbuff.h:1246
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6df3)
Location: include/linux/skbuff.h:1246
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81fb83c3)
Location: include/linux/skbuff.h:1246
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff8201402c)
Location: include/linux/skbuff.h:1246
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_offload.c (ffffffff82023356)
Location: include/linux/skbuff.h:1246
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/skbuff.c (ffffffff81ed9883)
Location: include/linux/skbuff.h:1253
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
```
```
In net/core/dev.c (ffffffff81ef9176)
Location: include/linux/skbuff.h:1253
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/ipv4/ip_output.c (ffffffff81fbd5e6)
Location: include/linux/skbuff.h:1253
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff8207153f)
Location: include/linux/skbuff.h:1253
Inline: True
```
```
In net/xfrm/xfrm_device.c (ffffffff820740d5)
Location: include/linux/skbuff.h:1253
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff820859b2)
Location: include/linux/skbuff.h:1253
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/netfilter.c (ffffffff820e3183)
Location: include/linux/skbuff.h:1253
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2436)
Location: include/linux/skbuff.h:1253
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bbb190)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffff800010bb5470-ffff800010bb54ac: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd799c)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
c0cd2538-c0cd256c: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c93f30)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
c000000000c8c580-c000000000c8c5d8: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074a186)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffe0007454e8-ffffffe000745518: kfree_skb_list (STB_GLOBAL)
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
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818c0821)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff818bb050-ffffffff818bb076: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a761)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81874f90-ffffffff81874fb6: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81911821)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff8190c050-ffffffff8190c076: kfree_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list(struct sk_buff *segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81932981)
Location: net/core/skbuff.c:701
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff8192d180-ffffffff8192d1a6: kfree_skb_list (STB_GLOBAL)
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
