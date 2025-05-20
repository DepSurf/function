# Function: <code>__icmp_send</code>

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
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81952ed0)
Location: net/ipv4/icmp.c:573
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
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
ffffffff81952ed0-ffffffff81953429: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff819b7960)
Location: net/ipv4/icmp.c:568
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
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
ffffffff819b7960-ffffffff819b7ef3: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff819ee660)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
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
ffffffff819ee660-ffffffff819eebf3: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81adc3e0)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
**Symbols:**

```
ffffffff81adc3e0-ffffffff81adc999: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ae9110)
Location: net/ipv4/icmp.c:591
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
**Symbols:**

```
ffffffff81ae9110-ffffffff81ae96b5: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ad4770)
Location: net/ipv4/icmp.c:591
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
**Symbols:**

```
ffffffff81ad4770-ffffffff81ad4d7e: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81b93490)
Location: net/ipv4/icmp.c:591
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
**Symbols:**

```
ffffffff81b93490-ffffffff81b93c2c: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:584
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
**Symbols:**

```
ffffffff81f0892a-ffffffff81f0897f: __icmp_send.cold (STB_LOCAL)
ffffffff81d24270-ffffffff81d24b15: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:584
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
**Symbols:**

```
ffffffff820b03ca-ffffffff820b041f: __icmp_send.cold (STB_LOCAL)
ffffffff81eeba50-ffffffff81eec2f5: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:587
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
**Symbols:**

```
ffffffff8213166e-ffffffff821316ca: __icmp_send.cold (STB_LOCAL)
ffffffff81f4b830-ffffffff81f4c0ea: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:587
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/icmp.c:icmp_ndo_send
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
```
**Symbols:**

```
ffffffff82213023-ffffffff8221307f: __icmp_send.cold (STB_LOCAL)
ffffffff82011940-ffffffff820121fa: __icmp_send (STB_GLOBAL)
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
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffff800010ca4948)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
ffff800010ca4948-ffff800010ca4ddc: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (c0db0a8c)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
c0db0a8c-c0db0ec8: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (c000000000db7bf0)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
c000000000db7bf0-c000000000db81d0: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffe0007ffc80)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
ffffffe0007ffc80-ffffffe000800004: __icmp_send (STB_GLOBAL)
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
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8198e400)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
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
ffffffff8198e400-ffffffff8198e993: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81947ec0)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_options.c:ip_options_rcv_srr
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
**Symbols:**

```
ffffffff81947ec0-ffffffff81948453: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff819f8ca0)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
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
ffffffff819f8ca0-ffffffff819f9233: __icmp_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __icmp_send(struct sk_buff *skb_in, int type, int code, __be32 info, const struct ip_options *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81a02c20)
Location: net/ipv4/icmp.c:569
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
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
ffffffff81a02c20-ffffffff81a031c8: __icmp_send (STB_GLOBAL)
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
