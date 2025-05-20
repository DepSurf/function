# Function: <code>nf_hook_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81751880)
Location: net/netfilter/core.c:295
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81751880-ffffffff81751946: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817bd8d0)
Location: net/netfilter/core.c:295
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff817bd8d0-ffffffff817bd996: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, struct nf_hook_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817ec8a0)
Location: net/netfilter/core.c:303
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff817ec8a0-ffffffff817ec944: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, struct nf_hook_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8180ccd0)
Location: net/netfilter/core.c:232
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff8180ccd0-ffffffff8180cd6f: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188be90)
Location: net/netfilter/core.c:460
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff8188be90-ffffffff8188bf45: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818dfb10)
Location: net/netfilter/core.c:504
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff818dfb10-ffffffff818dfbd5: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190c6a0)
Location: net/netfilter/core.c:504
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff8190c6a0-ffffffff8190c765: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196e290)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff8196e290-ffffffff8196e33c: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a4cd0)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff819a4cd0-ffffffff819a4d7c: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8dbf0)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/netfilter/core.c:nf_hook_slow_list
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81a8dbf0-ffffffff81a8dc9b: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a97bc0)
Location: net/netfilter/core.c:582
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/netfilter/core.c:nf_hook_slow_list
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81a97bc0-ffffffff81a97c6b: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a82f10)
Location: net/netfilter/core.c:582
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow_list
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81a82f10-ffffffff81a82fbb: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3cba0)
Location: net/netfilter/core.c:583
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow_list
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81b3cba0-ffffffff81b3cc4b: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc9030)
Location: net/netfilter/core.c:613
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/netfilter/core.c:nf_hook_slow_list
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/output_core.c:__ip6_local_out
  - net/packet/af_packet.c:nf_hook_direct_egress
```
**Symbols:**

```
ffffffff81cc9030-ffffffff81cc90fc: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e88bb0)
Location: net/netfilter/core.c:607
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/netfilter/core.c:nf_hook_slow_list
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/output_core.c:__ip6_local_out
  - net/packet/af_packet.c:nf_hook_direct_egress
```
**Symbols:**

```
ffffffff81e88bb0-ffffffff81e88c7c: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee6b20)
Location: net/netfilter/core.c:619
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/netfilter/core.c:nf_hook_slow_list
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/output_core.c:__ip6_local_out
  - net/packet/af_packet.c:nf_hook_direct_egress
```
**Symbols:**

```
ffffffff81ee6b20-ffffffff81ee6bf0: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81faa8d0)
Location: net/netfilter/core.c:619
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/netfilter/core.c:nf_hook_slow_list
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/output_core.c:__ip6_local_out
  - net/packet/af_packet.c:nf_hook_direct_egress
```
**Symbols:**

```
ffffffff81faa8d0-ffffffff81faa9f1: nf_hook_slow (STB_GLOBAL)
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
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c54150)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffff800010c54150-ffff800010c54234: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d63eb4)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
c0d63eb4-c0d63f78: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d53d80)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
c000000000d53d80-c000000000d53ec8: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007be8b2)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffe0007be8b2-ffffffe0007be95e: nf_hook_slow (STB_GLOBAL)
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
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81944b40)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81944b40-ffffffff81944bec: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fe630)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff818fe630-ffffffff818fe6dc: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81995cd0)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff81995cd0-ffffffff81995d7c: nf_hook_slow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nf_hook_slow(struct sk_buff *skb, struct nf_hook_state *state, const struct nf_hook_entries *e, unsigned int s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b88b0)
Location: net/netfilter/core.c:505
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/arp.c:arp_xmit
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
  - net/ipv4/xfrm4_output.c:xfrm4_output
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
  - net/ipv6/xfrm6_output.c:xfrm6_output
  - net/ipv6/output_core.c:__ip6_local_out
```
**Symbols:**

```
ffffffff819b88b0-ffffffff819b895c: nf_hook_slow (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nf_hook_entry *entry</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nf_hook_entries *e</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int s</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nf_hook_entry *entry</code>
</li>
</ul>
</details>
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
