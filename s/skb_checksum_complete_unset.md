# Function: <code>skb_checksum_complete_unset</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f6daa)
Location: include/linux/skbuff.h:3159
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81656f1a)
Location: include/linux/skbuff.h:3366
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81684bfa)
Location: include/linux/skbuff.h:3418
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169a02a)
Location: include/linux/skbuff.h:3471
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff817047da)
Location: include/linux/skbuff.h:3655
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81742f7a)
Location: include/linux/skbuff.h:3665
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff817677b7)
Location: include/linux/skbuff.h:3750
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff8194e15f)
Location: include/linux/skbuff.h:3750
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e18c9)
Location: include/linux/skbuff.h:3750
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a4fd7)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff819b295e)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a50684)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff817c90d7)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff819e96fe)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a872a4)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff81893955)
Location: include/linux/skbuff.h:3960
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff81ad3366)
Location: include/linux/skbuff.h:3960
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b824e3)
Location: include/linux/skbuff.h:3960
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff818a1de5)
Location: include/linux/skbuff.h:3989
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff81adf75f)
Location: include/linux/skbuff.h:3989
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b91bd3)
Location: include/linux/skbuff.h:3989
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff818842b5)
Location: include/linux/skbuff.h:4053
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff81aca664)
Location: include/linux/skbuff.h:4053
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80e22)
Location: include/linux/skbuff.h:4053
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff81915c75)
Location: include/linux/skbuff.h:4090
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff81b88f44)
Location: include/linux/skbuff.h:4090
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4ce42)
Location: include/linux/skbuff.h:4090
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff81a6be17)
Location: include/linux/skbuff.h:4509
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff81d1a968)
Location: include/linux/skbuff.h:4509
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded26d)
Location: include/linux/skbuff.h:4509
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff81bfed47)
Location: include/linux/skbuff.h:4405
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff81ee1698)
Location: include/linux/skbuff.h:4405
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc107d)
Location: include/linux/skbuff.h:4405
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff81c643a7)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff81f410db)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv6/ip6_checksum.c (ffffffff82022010)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff81d1adc7)
Location: include/linux/skbuff.h:4477
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff82006d2b)
Location: include/linux/skbuff.h:4477
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_csum_init
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f1130)
Location: include/linux/skbuff.h:4477
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffff800010a0354c)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffff800010c9f004)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffff800010d539b8)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (c0ade404)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (c0dac24c)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (c0e542f8)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (c000000000aa96c0)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (c000000000db18fc)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (c000000000e8c1fc)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffe00062d91a)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffe0007fba54)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b662)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178dbb7)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff8198956e)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a26934)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff81776987)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff8194302e)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e36f4)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bdf57)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff819f3d3e)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a924e4)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
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
In drivers/net/ppp/ppp_generic.c (ffffffff817d8787)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/udp.c (ffffffff819fdefe)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e594)
Location: include/linux/skbuff.h:3926
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
</details>
</li>
</ul>

## Differences
