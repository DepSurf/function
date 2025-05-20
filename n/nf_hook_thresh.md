# Function: <code>nf_hook_thresh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81758dcd)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_forward.c (ffffffff8175aab7)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175e17c)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_output
```
```
In net/ipv4/raw.c (ffffffff81785581)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8178c260)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff817a9280)
Location: include/linux/netfilter.h:171
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff817afed8)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b02fb)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc3c7)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff817c4e4e)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_output
```
```
In net/ipv6/ip6_input.c (ffffffff817c8d53)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_input
```
```
In net/ipv6/ndisc.c (ffffffff817de8f5)
Location: include/linux/netfilter.h:171
Inline: True
```
```
In net/ipv6/raw.c (ffffffff817e66b3)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff817ea2f5)
Location: include/linux/netfilter.h:171
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f9e40)
Location: include/linux/netfilter.h:171
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff817fce61)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd3cb)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff8180063b)
Location: include/linux/netfilter.h:171
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff817c5460)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_local_deliver
```
```
In net/ipv4/ip_forward.c (ffffffff817c6e5f)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817cacfe)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffffffff817f2b3f)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/arp.c (ffffffff817f988b)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81816ab0)
Location: include/linux/netfilter.h:155
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181ce13)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv4/xfrm4_output.c (ffffffff8181d23b)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_output
```
```
In net/xfrm/xfrm_output.c (ffffffff818292f1)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81833e32)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81835c2d)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/ndisc.c (ffffffff8184c815)
Location: include/linux/netfilter.h:155
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81854a83)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81858bb5)
Location: include/linux/netfilter.h:155
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818696a0)
Location: include/linux/netfilter.h:155
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff8186c781)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186ccfb)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_output
```
```
In net/ipv6/output_core.c (ffffffff81871d55)
Location: include/linux/netfilter.h:155
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ip6_local_out
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
