# Function: <code>ip_tunnel_info_af</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81731b32)
Location: include/net/ip_tunnels.h:238
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179cb7c)
Location: include/net/ip_tunnels.h:247
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/filter.c (ffffffff817ca51c)
Location: include/net/ip_tunnels.h:247
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/filter.c (ffffffff817e9504)
Location: include/net/ip_tunnels.h:249
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8183e6a5)
Location: include/net/ip_tunnels.h:255
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff81864a04)
Location: include/net/ip_tunnels.h:255
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818885d9)
Location: include/net/ip_tunnels.h:260
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818b1bc4)
Location: include/net/ip_tunnels.h:260
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff818a9131)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818d6604)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff818f489a)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81923e88)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff8192684a)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81956198)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff819fac5f)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a2b896)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff819fa86f)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a2cab6)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff819e0a73)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a13e79)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff81a90df3)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81ac5849)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff81c06e8a)
Location: include/net/ip_tunnels.h:245
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81c413c7)
Location: include/net/ip_tunnels.h:245
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff81db6908)
Location: include/net/ip_tunnels.h:245
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81df6b39)
Location: include/net/ip_tunnels.h:245
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff81e26cde)
Location: include/net/ip_tunnels.h:252
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81e687ef)
Location: include/net/ip_tunnels.h:252
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff81ee4c70)
Location: include/net/ip_tunnels.h:225
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81f27dcf)
Location: include/net/ip_tunnels.h:225
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffff800010bc2bb0)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffff800010bf6fc0)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (c0cddef8)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (c0d11804)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (c000000000c9cba4)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (c000000000cde11c)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffe00074f8c2)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffe000778dea)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff818c684a)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818f6168)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In drivers/net/vxlan.c (ffffffff81770432)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit_one
```
```
In net/core/flow_dissector.c (ffffffff8188078a)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818aff98)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967394)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
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
In net/core/flow_dissector.c (ffffffff8191784a)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81947198)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
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
In net/core/flow_dissector.c (ffffffff81938a5a)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81968aa8)
Location: include/net/ip_tunnels.h:241
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_key
  - net/core/filter.c:bpf_skb_get_tunnel_key
```
</details>
</li>
</ul>

## Differences
