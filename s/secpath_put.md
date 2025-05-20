# Function: <code>secpath_put</code>

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
In net/core/skbuff.c (ffffffff81705418)
Location: include/net/xfrm.h:1007
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4b90)
Location: include/net/xfrm.h:1007
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/xfrm/xfrm_input.c (ffffffff817bba53)
Location: include/net/xfrm.h:1007
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/xfrm6_input.c (ffffffff817fcba9)
Location: include/net/xfrm.h:1007
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff8176cc83)
Location: include/net/xfrm.h:1003
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/xfrm/xfrm_input.c (ffffffff81828984)
Location: include/net/xfrm.h:1003
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/xfrm6_input.c (ffffffff8186c4f8)
Location: include/net/xfrm.h:1003
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179a103)
Location: include/net/xfrm.h:1003
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a364)
Location: include/net/xfrm.h:1003
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/xfrm6_input.c (ffffffff8189f308)
Location: include/net/xfrm.h:1003
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b93c3)
Location: include/net/xfrm.h:1061
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff817cc908)
Location: include/net/xfrm.h:1061
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/xfrm/xfrm_input.c (ffffffff8187dfa6)
Location: include/net/xfrm.h:1061
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ef4a)
Location: include/net/xfrm.h:1061
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff8183348c)
Location: include/net/xfrm.h:1067
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81846278)
Location: include/net/xfrm.h:1067
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/xfrm/xfrm_input.c (ffffffff818fee56)
Location: include/net/xfrm.h:1067
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff81900069)
Location: include/net/xfrm.h:1067
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff8187d92c)
Location: include/net/xfrm.h:1099
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8188db58)
Location: include/net/xfrm.h:1099
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/xfrm/xfrm_input.c (ffffffff81955916)
Location: include/net/xfrm.h:1099
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff81956aeb)
Location: include/net/xfrm.h:1099
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
</details>
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
