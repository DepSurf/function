# Function: <code>icmp_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8178e4b0)
Location: net/ipv4/icmp.c:568
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
ffffffff8178e4b0-ffffffff8178e91b: icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff817fbaa0)
Location: net/ipv4/icmp.c:568
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
ffffffff817fbaa0-ffffffff817fbf65: icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8182c9f0)
Location: net/ipv4/icmp.c:570
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
ffffffff8182c9f0-ffffffff8182ceb8: icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8184de50)
Location: net/ipv4/icmp.c:576
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
ffffffff8184de50-ffffffff8184e34a: icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff818cdb70)
Location: net/ipv4/icmp.c:576
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
ffffffff818cdb70-ffffffff818ce076: icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81924310)
Location: net/ipv4/icmp.c:576
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
ffffffff81924310-ffffffff81924810: icmp_send (STB_GLOBAL)
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
In net/ipv4/route.c (ffffffff8190efc5)
Location: include/net/icmp.h:45
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff8191584a)
Location: include/net/icmp.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81917086)
Location: include/net/icmp.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81917454)
Location: include/net/icmp.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81917921)
Location: include/net/icmp.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81919b4c)
Location: include/net/icmp.h:45
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194e6ba)
Location: include/net/icmp.h:45
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b5db)
Location: include/net/icmp.h:45
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff8197bc1e)
Location: include/net/icmp.h:45
Inline: True
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
In net/ipv4/route.c (ffffffff81970f41)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81977db5)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81979034)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff8197939b)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff8197a017)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8197bbb3)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2e54)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4b12)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff819e511e)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff819a7941)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819ae725)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff819af9a4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819afd36)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819b0977)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff819b2393)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e9beb)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bb4e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81a1c14e)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff81a90c33)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a985c5)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9986e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a99bdb)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81a9a824)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a9cb45)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad7958)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/icmp.c (ffffffff81adca7d)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b0cd5e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fa82)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff81a9aa8a)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81aa2515)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa37e3)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3b2b)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81aa477d)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81aa69d5)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae3fa8)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b1b09e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e35e)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff81a85e1d)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81a8d232)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e933)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ec25)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81a8f872)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a91ac5)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acf18a)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81b08d4e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1bdb3)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff81b4061d)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81b483d4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49b32)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81b49e61)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81b4aade)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81b4ceb5)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8db2e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81bcbc3e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be05a9)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff81ccd099)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81cd56c4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd66aa)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7391)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81cd7922)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81cda62e)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1ec70)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81d617ae)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7760c)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff81e8d149)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81e95b7f)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81e96c02)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81e979b2)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81e97f9e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81e9adfe)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee5e1e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81f2c12e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43e98)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff81eeb87a)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81ef43bf)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5439)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81ef61f5)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81ef67f9)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81ef97fe)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f455a1)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81f8bdce)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa367c)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff81faf88a)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81fb833f)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb93e9)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81fba18e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff81fba789)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81fbd71e)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8200b5b4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff820536ce)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff82070740)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffff800010c59cc4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffff800010c5ec48)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f6e4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffff800010c603d0)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffff800010c60eb4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffff800010c64034)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f4e4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7dd8)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (ffff800010cd8354)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (c0d66d28)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (c0d6e3ac)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c0d6f198)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c0d6fbe0)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (c0d70954)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (c0d727bc)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (c0dac744)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (c0de1884)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (c0de1db0)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (c000000000d585cc)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (c000000000d616dc)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c000000000d6268c)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c000000000d63478)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (c000000000d642c4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (c000000000d664e4)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1e38)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (c000000000df7ea0)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (c000000000df8694)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffe0007c14a2)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffe0007c720c)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c82d2)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffe0007c865a)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffe0007c9068)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffe0007ca95c)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fbfaa)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffe00082839c)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffe000828828)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff819477b1)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff8194e595)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f814)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff8194fba6)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819507e7)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff81952203)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81989a5b)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb1de)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff819bb7de)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff819012a1)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff81908085)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81909304)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff81909696)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff8190a2d7)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff8190bcf3)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194351b)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/ip_tunnel.c (ffffffff81966bcd)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977fce)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff819785ce)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff819b1f81)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819b8d65)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9fe4)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819ba376)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819bafb7)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff819bc9d3)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f422b)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25c5e)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81a2625e)
Location: include/net/icmp.h:41
Inline: True
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
In net/ipv4/route.c (ffffffff819bb638)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_input.c (ffffffff819c25e5)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff819c32ca)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffffffff819c3c66)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_options.c (ffffffff819c48d1)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
```
```
In net/ipv4/ip_output.c (ffffffff819c62e3)
Location: include/net/icmp.h:41
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fe3eb)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a310fe)
Location: include/net/icmp.h:41
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv4/xfrm4_protocol.c (ffffffff81a3170e)
Location: include/net/icmp.h:41
Inline: True
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
</ul>
