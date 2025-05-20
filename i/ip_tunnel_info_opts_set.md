# Function: <code>ip_tunnel_info_opts_set</code>

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
In net/core/filter.c (ffffffff8179bafb)
Location: include/net/ip_tunnels.h:434
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
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
In net/core/filter.c (ffffffff817cbf6a)
Location: include/net/ip_tunnels.h:455
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
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
In net/core/filter.c (ffffffff817eb879)
Location: include/net/ip_tunnels.h:457
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
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
In net/core/filter.c (ffffffff81866539)
Location: include/net/ip_tunnels.h:464
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
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
Location: include/net/ip_tunnels.h:496
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
Location: include/net/ip_tunnels.h:498
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
Location: include/net/ip_tunnels.h:499
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
Location: include/net/ip_tunnels.h:499
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
Location: include/net/ip_tunnels.h:503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8aa9)
Location: include/net/ip_tunnels.h:503
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
In net/core/filter.c (ffffffff81a2eddd)
Location: include/net/ip_tunnels.h:503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05868)
Location: include/net/ip_tunnels.h:503
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
In net/core/filter.c (ffffffff81a16e1e)
Location: include/net/ip_tunnels.h:503
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1122)
Location: include/net/ip_tunnels.h:503
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
In net/core/filter.c (ffffffff81ac82ae)
Location: include/net/ip_tunnels.h:504
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1832)
Location: include/net/ip_tunnels.h:504
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
In net/core/filter.c (ffffffff81c458d3)
Location: include/net/ip_tunnels.h:515
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44eb0)
Location: include/net/ip_tunnels.h:515
Inline: True
Inline callers:
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
In net/core/filter.c (ffffffff81df9a83)
Location: include/net/ip_tunnels.h:527
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e330)
Location: include/net/ip_tunnels.h:527
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_metadata_reply
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
In net/core/filter.c (ffffffff81e6b978)
Location: include/net/ip_tunnels.h:531
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6dfe9)
Location: include/net/ip_tunnels.h:531
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_metadata_reply
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
In net/core/filter.c (ffffffff81f2aac8)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820346f9)
Location: include/net/ip_tunnels.h:514
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_metadata_reply
```
</details>
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
Location: include/net/ip_tunnels.h:499
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
Location: include/net/ip_tunnels.h:499
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
Location: include/net/ip_tunnels.h:499
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
Location: include/net/ip_tunnels.h:499
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
Location: include/net/ip_tunnels.h:499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3b72)
Location: include/net/ip_tunnels.h:499
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
Location: include/net/ip_tunnels.h:499
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
Location: include/net/ip_tunnels.h:499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_opt
```
</details>
</li>
</ul>

## Differences
