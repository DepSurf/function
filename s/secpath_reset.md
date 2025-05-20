# Function: <code>secpath_reset</code>

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
In net/core/skbuff.c (ffffffff8170631f)
Location: include/net/xfrm.h:1016
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4b84)
Location: include/net/xfrm.h:1016
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
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
In net/core/skbuff.c (ffffffff8176cc7f)
Location: include/net/xfrm.h:1012
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
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
In net/core/skbuff.c (ffffffff8179a0ff)
Location: include/net/xfrm.h:1012
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
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
In net/core/skbuff.c (ffffffff817b93bf)
Location: include/net/xfrm.h:1071
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff817cc904)
Location: include/net/xfrm.h:1071
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ee39)
Location: include/net/xfrm.h:1071
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81833488)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81846274)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/xfrm/xfrm_output.c (ffffffff818fff59)
Location: include/net/xfrm.h:1077
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff8187d928)
Location: include/net/xfrm.h:1109
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8188db54)
Location: include/net/xfrm.h:1109
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/xfrm/xfrm_output.c (ffffffff81956a5f)
Location: include/net/xfrm.h:1109
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff8189d3fe)
Location: include/net/xfrm.h:1115
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff818ae9e4)
Location: include/net/xfrm.h:1115
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a8c8)
Location: include/net/xfrm.h:1115
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b6cb)
Location: include/net/xfrm.h:1115
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff818e7c7e)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff818fa2d6)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/xfrm/xfrm_input.c (ffffffff819f550f)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6beb)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81a2c1bf)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d85b)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81b1e752)
Location: include/net/xfrm.h:1039
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2028b)
Location: include/net/xfrm.h:1039
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81b2d022)
Location: include/net/xfrm.h:1042
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2ebcb)
Location: include/net/xfrm.h:1042
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81b1ac65)
Location: include/net/xfrm.h:1042
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c980)
Location: include/net/xfrm.h:1042
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81bdf188)
Location: include/net/xfrm.h:1039
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be12f2)
Location: include/net/xfrm.h:1039
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81d75f02)
Location: include/net/xfrm.h:1042
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d78224)
Location: include/net/xfrm.h:1042
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_policy.c (ffffffff81f37b69)
Location: include/net/xfrm.h:1060
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42642)
Location: include/net/xfrm.h:1060
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44ae8)
Location: include/net/xfrm.h:1060
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81fa1ef2)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa42af)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff8206f2cf)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8207160d)
Location: include/net/xfrm.h:1066
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffff800010ceafe0)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec5ec)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (c0df2c9c)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4518)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (c000000000e0ec40)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e107c8)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffe0008387ae)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839cd8)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff819cb84f)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cceeb)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff8198863f)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989cdb)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81a362cf)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a3796b)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_input.c (ffffffff81a41c3b)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4332b)
Location: include/net/xfrm.h:1040
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
</details>
</li>
</ul>

## Differences
