# Function: <code>skb_gso_network_seglen</code>

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
In net/ipv4/ip_forward.c (ffffffff8175a9b1)
Location: include/linux/skbuff.h:3578
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175e081)
Location: include/linux/skbuff.h:3578
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c6cb0)
Location: include/linux/skbuff.h:3578
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/core/skbuff.c (ffffffff8176bfc2)
Location: include/linux/skbuff.h:3798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mtu
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
In net/core/skbuff.c (ffffffff817991a2)
Location: include/linux/skbuff.h:3857
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mtu
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
In net/core/skbuff.c (ffffffff817b7772)
Location: include/linux/skbuff.h:3921
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mtu
```
```
In net/ipv4/xfrm4_output.c (ffffffff81872538)
Location: include/linux/skbuff.h:3921
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5f65)
Location: include/linux/skbuff.h:3921
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/skbuff.c (ffffffff8182fe22)
Location: include/linux/skbuff.h:4112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_mtu
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f2f2e)
Location: include/linux/skbuff.h:4112
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819492ff)
Location: include/linux/skbuff.h:4112
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/skbuff.c (ffffffff8187a4a5)
Location: net/core/skbuff.c:4962
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (ffffffff8189b0b5)
Location: net/core/skbuff.c:4988
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (ffffffff818e5795)
Location: net/core/skbuff.c:5173
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (ffffffff819178e5)
Location: net/core/skbuff.c:5185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea9a5)
Location: net/core/skbuff.c:5287
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea6f2)
Location: net/core/skbuff.c:5354
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d0cb2)
Location: net/core/skbuff.c:5442
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a804f2)
Location: net/core/skbuff.c:5517
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf4b92)
Location: net/core/skbuff.c:5438
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2a72)
Location: net/core/skbuff.c:5640
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81e7d852)
Location: net/core/gso.c:178
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_network_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81f3e7c2)
Location: net/core/gso.c:178
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (ffff800010bb0ca4)
Location: net/core/skbuff.c:5185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (c0cce018)
Location: net/core/skbuff.c:5185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (c000000000c86ed8)
Location: net/core/skbuff.c:5185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (ffffffe000741e48)
Location: net/core/skbuff.c:5185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (ffffffff818b78e5)
Location: net/core/skbuff.c:5185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (ffffffff81871835)
Location: net/core/skbuff.c:5185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (ffffffff819088e5)
Location: net/core/skbuff.c:5185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
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
In net/core/skbuff.c (ffffffff81929995)
Location: net/core/skbuff.c:5185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_validate_network_len
```
</details>
</li>
</ul>

## Differences
