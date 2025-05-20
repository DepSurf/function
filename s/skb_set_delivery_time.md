# Function: <code>skb_set_delivery_time</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cda4c4)
Location: include/linux/skbuff.h:4218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81d019b5)
Location: include/linux/skbuff.h:4218
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a7b1)
Location: include/linux/skbuff.h:4218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca83e)
Location: include/linux/skbuff.h:4218
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81de1474)
Location: include/linux/skbuff.h:4218
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/ipv4/ip_output.c (ffffffff81e9ac84)
Location: include/linux/skbuff.h:4114
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6b25)
Location: include/linux/skbuff.h:4114
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81f58745)
Location: include/linux/skbuff.h:4114
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b877)
Location: include/linux/skbuff.h:4114
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff81fb38d4)
Location: include/linux/skbuff.h:4114
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/ipv4/ip_output.c (ffffffff81ef9617)
Location: include/linux/skbuff.h:4146
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81f252d1)
Location: include/linux/skbuff.h:4146
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv6/ip6_output.c (ffffffff81fb8388)
Location: include/linux/skbuff.h:4146
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffbc3d)
Location: include/linux/skbuff.h:4146
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff82013fef)
Location: include/linux/skbuff.h:4146
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
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
In net/ipv4/ip_output.c (ffffffff81fbd534)
Location: include/linux/skbuff.h:4183
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9b8a)
Location: include/linux/skbuff.h:4183
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv6/ip6_output.c (ffffffff82085977)
Location: include/linux/skbuff.h:4183
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca34d)
Location: include/linux/skbuff.h:4183
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/netfilter.c (ffffffff820e3146)
Location: include/linux/skbuff.h:4183
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
