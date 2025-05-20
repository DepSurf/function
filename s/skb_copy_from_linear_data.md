# Function: <code>skb_copy_from_linear_data</code>

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
In net/core/skbuff.c (ffffffff81707eeb)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff8175c85e)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff81778791)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv6/ip6_output.c (ffffffff817c75c6)
Location: include/linux/skbuff.h:2902
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff8176dadb)
Location: include/linux/skbuff.h:3109
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff817c964d)
Location: include/linux/skbuff.h:3109
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/tcp_output.c (ffffffff817e57d4)
Location: include/linux/skbuff.h:3109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv6/ip6_output.c (ffffffff818347c6)
Location: include/linux/skbuff.h:3109
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff8179af3b)
Location: include/linux/skbuff.h:3161
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff817f95d6)
Location: include/linux/skbuff.h:3161
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff8186621f)
Location: include/linux/skbuff.h:3161
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff817b97b7)
Location: include/linux/skbuff.h:3235
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81819a22)
Location: include/linux/skbuff.h:3235
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff8188abe2)
Location: include/linux/skbuff.h:3235
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff81832107)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81898054)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff8190bdd9)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff8187c2ea)
Location: include/linux/skbuff.h:3366
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff818ec4cb)
Location: include/linux/skbuff.h:3366
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81962e80)
Location: include/linux/skbuff.h:3366
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff8189d044)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81919662)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81997e69)
Location: include/linux/skbuff.h:3445
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
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
In net/core/skbuff.c (ffffffff818e7444)
Location: include/linux/skbuff.h:3536
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff8197b332)
Location: include/linux/skbuff.h:3536
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81a013fa)
Location: include/linux/skbuff.h:3536
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff81919b04)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff819b1ca2)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81a37fda)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff819ead94)
Location: include/linux/skbuff.h:3626
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81a9c532)
Location: include/linux/skbuff.h:3626
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dfea)
Location: include/linux/skbuff.h:3626
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff819eaac4)
Location: include/linux/skbuff.h:3655
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81aa6392)
Location: include/linux/skbuff.h:3655
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ca3a)
Location: include/linux/skbuff.h:3655
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff819d1084)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81a91552)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81b29eaa)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff81a80ac4)
Location: include/linux/skbuff.h:3756
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81b4c904)
Location: include/linux/skbuff.h:3756
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81befa7a)
Location: include/linux/skbuff.h:3756
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff81bf55b4)
Location: include/linux/skbuff.h:4129
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81cd9fc4)
Location: include/linux/skbuff.h:4129
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81d885da)
Location: include/linux/skbuff.h:4129
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff81da47a4)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81e9a774)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81f5629a)
Location: include/linux/skbuff.h:4025
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff81e13343)
Location: include/linux/skbuff.h:4057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81ef90f4)
Location: include/linux/skbuff.h:4057
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5c7a)
Location: include/linux/skbuff.h:4057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff81ed0503)
Location: include/linux/skbuff.h:4094
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81fbd014)
Location: include/linux/skbuff.h:4094
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff8208334a)
Location: include/linux/skbuff.h:4094
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffff800010bb2c40)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffff800010c625bc)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffff800010cf8790)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (c0cd0b10)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (c0d71e70)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (c0dffe94)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (c000000000c8a6d0)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (c000000000d65a78)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (c000000000e207e0)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffe000743270)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffe0007ca1f8)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffe0008444ec)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff818b9b04)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81951b12)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff819d766a)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff81873a54)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff8190b602)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff8199442a)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff8190ab04)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff819bc2e2)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81a420ea)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
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
In net/core/skbuff.c (ffffffff8192bc04)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_dev
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff819c5bf2)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
```
```
In net/ipv6/ip6_output.c (ffffffff81a4dd7a)
Location: include/linux/skbuff.h:3603
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
```
</details>
</li>
</ul>

## Differences
