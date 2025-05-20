# Function: <code>__skb_ext_del</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d330)
Location: net/core/skbuff.c:5700
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8189d330-ffffffff8189d3bd: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e7bb0)
Location: net/core/skbuff.c:6060
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff818e7bb0-ffffffff818e7c3b: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191a090)
Location: net/core/skbuff.c:6077
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff8191a090-ffffffff8191a11b: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ec0e0)
Location: net/core/skbuff.c:6220
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify_ingress
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff819ec0e0-ffffffff819ec193: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ebe00)
Location: net/core/skbuff.c:6357
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify_ingress
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff819ebe00-ffffffff819ebeb3: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d2510)
Location: net/core/skbuff.c:6445
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify_ingress
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff819d2510-ffffffff819d25c3: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6521
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81d3515d-ffffffff81d35184: __skb_ext_del.cold (STB_LOCAL)
ffffffff81a82110-ffffffff81a82201: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6442
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81f016ba-ffffffff81f016e1: __skb_ext_del.cold (STB_LOCAL)
ffffffff81bf6390-ffffffff81bf649d: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6643
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff820aac57-ffffffff820aac7e: __skb_ext_del.cold (STB_LOCAL)
ffffffff81da4c90-ffffffff81da4d9d: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6688
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff8212c157-ffffffff8212c179: __skb_ext_del.cold (STB_LOCAL)
ffffffff81e13920-ffffffff81e13a21: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6835
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff8220de37-ffffffff8220de59: __skb_ext_del.cold (STB_LOCAL)
ffffffff81ed0ae0-ffffffff81ed0be1: __skb_ext_del (STB_GLOBAL)
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
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb27d8)
Location: net/core/skbuff.c:6077
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffff800010bb27d8-ffff800010bb28bc: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd0a18)
Location: net/core/skbuff.c:6077
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
c0cd0a18-c0cd0acc: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8a3e0)
Location: net/core/skbuff.c:6077
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
c000000000c8a3e0-c000000000c8a514: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007446fe)
Location: net/core/skbuff.c:6077
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffe0007446fe-ffffffe000744792: __skb_ext_del (STB_GLOBAL)
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
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ba090)
Location: net/core/skbuff.c:6077
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff818ba090-ffffffff818ba11b: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81873fe0)
Location: net/core/skbuff.c:6077
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff81873fe0-ffffffff8187406b: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190b090)
Location: net/core/skbuff.c:6077
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff8190b090-ffffffff8190b11b: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __skb_ext_del(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192c190)
Location: net/core/skbuff.c:6077
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff8192c190-ffffffff8192c21b: __skb_ext_del (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
