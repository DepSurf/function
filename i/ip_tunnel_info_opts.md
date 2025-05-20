# Function: <code>ip_tunnel_info_opts</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (0)
Location: include/net/ip_tunnels.h:423
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (0)
Location: include/net/ip_tunnels.h:444
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (0)
Location: include/net/ip_tunnels.h:446
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (0)
Location: include/net/ip_tunnels.h:453
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5071)
Location: include/net/ip_tunnels.h:485
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818dac4b)
Location: include/net/ip_tunnels.h:487
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819276b2)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959d72)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
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
In net/core/filter.c (ffffffff81a2d542)
Location: include/net/ip_tunnels.h:492
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8a02)
Location: include/net/ip_tunnels.h:492
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
In net/core/filter.c (ffffffff81a2ede7)
Location: include/net/ip_tunnels.h:492
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b057d2)
Location: include/net/ip_tunnels.h:492
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
In net/core/filter.c (ffffffff81a16e28)
Location: include/net/ip_tunnels.h:492
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1052)
Location: include/net/ip_tunnels.h:492
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
In net/core/filter.c (ffffffff81ac82b8)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1762)
Location: include/net/ip_tunnels.h:493
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
In net/core/filter.c (ffffffff81c458da)
Location: include/net/ip_tunnels.h:504
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d449ec)
Location: include/net/ip_tunnels.h:504
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:iptunnel_metadata_reply
  - net/ipv4/ip_tunnel_core.c:iptunnel_metadata_reply
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
In net/core/filter.c (ffffffff81df9a8a)
Location: include/net/ip_tunnels.h:516
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0db8c)
Location: include/net/ip_tunnels.h:516
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:ip_tun_cmp_encap
  - net/ipv4/ip_tunnel_core.c:iptunnel_metadata_reply
  - net/ipv4/ip_tunnel_core.c:iptunnel_metadata_reply
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bffa54)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d15c9c)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce3f0c)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077dff4)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f9d42)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
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
In drivers/net/vxlan.c (ffffffff81771ff8)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/filter.c (ffffffff818b3b72)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194ad72)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196c682)
Location: include/net/ip_tunnels.h:488
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
</ul>

## Differences
