# Function: <code>prandom_u32_max</code>

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
In lib/random32.c (ffffffff813f8a2d)
Location: include/linux/random.h:67
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff8174d068)
Location: include/linux/random.h:67
Inline: True
```
```
In net/ipv4/route.c (ffffffff81753176)
Location: include/linux/random.h:67
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/packet/af_packet.c (ffffffff81804a55)
Location: include/linux/random.h:67
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff813e185c)
Location: include/linux/random.h:67
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff8143fa0d)
Location: include/linux/random.h:67
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff817b943b)
Location: include/linux/random.h:67
Inline: True
```
```
In net/ipv4/route.c (ffffffff817bf300)
Location: include/linux/random.h:67
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff817d835f)
Location: include/linux/random.h:67
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81878a80)
Location: include/linux/random.h:67
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff813f9f5c)
Location: include/linux/random.h:78
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff8145cb0d)
Location: include/linux/random.h:78
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff817e8df2)
Location: include/linux/random.h:78
Inline: True
```
```
In net/ipv4/route.c (ffffffff817eec50)
Location: include/linux/random.h:78
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff8180877f)
Location: include/linux/random.h:78
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818acb80)
Location: include/linux/random.h:78
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff814065f2)
Location: include/linux/random.h:137
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff81461d1d)
Location: include/linux/random.h:137
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff81808ae9)
Location: include/linux/random.h:137
Inline: True
```
```
In net/ipv4/route.c (ffffffff8180ed12)
Location: include/linux/random.h:137
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff81828db3)
Location: include/linux/random.h:137
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d0816)
Location: include/linux/random.h:137
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff8142ef32)
Location: include/linux/random.h:138
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff8148dbfd)
Location: include/linux/random.h:138
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff81887999)
Location: include/linux/random.h:138
Inline: True
```
```
In net/ipv4/route.c (ffffffff8188e2d2)
Location: include/linux/random.h:138
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff818a82c7)
Location: include/linux/random.h:138
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81955742)
Location: include/linux/random.h:138
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff81461b92)
Location: include/linux/random.h:136
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff814c297d)
Location: include/linux/random.h:136
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff818db39b)
Location: include/linux/random.h:136
Inline: True
```
```
In net/ipv4/route.c (ffffffff818e1ff0)
Location: include/linux/random.h:136
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff818fd60a)
Location: include/linux/random.h:136
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ae38c)
Location: include/linux/random.h:136
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff8147fba2)
Location: include/linux/random.h:137
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff814d702d)
Location: include/linux/random.h:137
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff81907c9b)
Location: include/linux/random.h:137
Inline: True
```
```
In net/ipv4/route.c (ffffffff8190ee90)
Location: include/linux/random.h:137
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff8192b70a)
Location: include/linux/random.h:137
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e4d7e)
Location: include/linux/random.h:137
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff814adb92)
Location: include/linux/random.h:138
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff81502e8d)
Location: include/linux/random.h:138
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff81968fbb)
Location: include/linux/random.h:138
Inline: True
```
```
In net/ipv4/route.c (ffffffff8197099d)
Location: include/linux/random.h:138
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff8198e999)
Location: include/linux/random.h:138
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a53ec5)
Location: include/linux/random.h:138
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff814c8842)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff81520e2d)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff8199fa5b)
Location: include/linux/random.h:139
Inline: True
```
```
In net/ipv4/route.c (ffffffff819a739d)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff819c56d9)
Location: include/linux/random.h:139
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8aad5)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In mm/swapfile.c (ffffffff812bf756)
Location: include/linux/prandom.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81527e2c)
Location: include/linux/prandom.h:44
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff81583e9d)
Location: include/linux/prandom.h:44
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff81a78b4b)
Location: include/linux/prandom.h:44
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a906e4)
Location: include/linux/prandom.h:44
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0a29)
Location: include/linux/prandom.h:44
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8666f)
Location: include/linux/prandom.h:44
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In mm/swapfile.c (ffffffff812cb2f4)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81544d9c)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff815a10bd)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - lib/random32.c:prandom_reseed
```
```
In net/core/neighbour.c (ffffffff81a13202)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/netlink/af_netlink.c (ffffffff81a81e5d)
Location: include/linux/prandom.h:94
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9a554)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff81abb9f9)
Location: include/linux/prandom.h:94
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae90e1)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/packet/af_packet.c (ffffffff81b95fa5)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In mm/swapfile.c (ffffffff812d1e8a)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154d439)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff815a7f6d)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - lib/random32.c:prandom_reseed
```
```
In net/core/neighbour.c (ffffffff819fa7a2)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/netlink/af_netlink.c (ffffffff81a6af46)
Location: include/linux/prandom.h:94
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a85845)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff81aa69b9)
Location: include/linux/prandom.h:94
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad437e)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/packet/af_packet.c (ffffffff81b84e85)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In mm/swapfile.c (ffffffff81317607)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/kfence/core.c (ffffffff8133bfbe)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815adc19)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff81610f05)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - lib/random32.c:prandom_reseed
```
```
In net/core/neighbour.c (ffffffff81aad6e2)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/netlink/af_netlink.c (ffffffff81b24546)
Location: include/linux/prandom.h:94
Inline: True
```
```
In net/ipv4/route.c (ffffffff81b41e90)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff81b62da9)
Location: include/linux/prandom.h:94
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b9341e)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv6/route.c (ffffffff81c05f56)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/packet/af_packet.c (ffffffff81c51336)
Location: include/linux/prandom.h:94
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In mm/swapfile.c (ffffffff81382d13)
Location: include/linux/prandom.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/kfence/core.c (ffffffff813aeac5)
Location: include/linux/prandom.h:48
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81656107)
Location: include/linux/prandom.h:48
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In net/core/neighbour.c (ffffffff81c22b51)
Location: include/linux/prandom.h:48
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/netlink/af_netlink.c (ffffffff81cac851)
Location: include/linux/prandom.h:48
Inline: True
```
```
In net/ipv4/route.c (ffffffff81cce883)
Location: include/linux/prandom.h:48
Inline: True
Inline callers:
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1445)
Location: include/linux/prandom.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
```
```
In net/ipv4/icmp.c (ffffffff81d23aea)
Location: include/linux/prandom.h:48
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv6/route.c (ffffffff81da0612)
Location: include/linux/prandom.h:48
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/packet/af_packet.c (ffffffff81df2802)
Location: include/linux/prandom.h:48
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa-pkcs1pad.c (ffff8000105c45f8)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffff80001062a378)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffff800010c4d20c)
Location: include/linux/random.h:139
Inline: True
```
```
In net/ipv4/route.c (ffff800010c58580)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffff800010c7a324)
Location: include/linux/random.h:139
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5ac84)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (c0771444)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (c07d16a4)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (c0d5e104)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
```
```
In net/ipv4/route.c (c0d67a5c)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (c0d86bb0)
Location: include/linux/random.h:139
Inline: True
```
```
In net/packet/af_packet.c (c0e5a2a4)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (c00000000074d3f0)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (c0000000007cc3f8)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (c000000000d4c160)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
```
```
In net/ipv4/route.c (c000000000d57ef0)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (c000000000d80c9c)
Location: include/linux/random.h:139
Inline: True
```
```
In net/packet/af_packet.c (c000000000e935f0)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffe000408b1a)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffe00045aebc)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffe0007ba080)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
```
```
In net/ipv4/route.c (ffffffe0007c1014)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffe0007db3c6)
Location: include/linux/random.h:139
Inline: True
```
```
In net/packet/af_packet.c (ffffffe00088f61e)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff814c0e22)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff8151940d)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff8193f8cb)
Location: include/linux/random.h:139
Inline: True
```
```
In net/ipv4/route.c (ffffffff8194720d)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff81965549)
Location: include/linux/random.h:139
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2a165)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff814b1842)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff815096fd)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff818f93cb)
Location: include/linux/random.h:139
Inline: True
```
```
In net/ipv4/route.c (ffffffff81900cfd)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff8191f039)
Location: include/linux/random.h:139
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e7355)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff814bceb2)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff8151549d)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff81990a5b)
Location: include/linux/random.h:139
Inline: True
```
```
In net/ipv4/route.c (ffffffff819b19dd)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff819cfd19)
Location: include/linux/random.h:139
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a95d15)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In crypto/rsa-pkcs1pad.c (ffffffff814d5982)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In lib/random32.c (ffffffff8152ec3d)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In net/netlink/af_netlink.c (ffffffff819b34d7)
Location: include/linux/random.h:139
Inline: True
```
```
In net/ipv4/route.c (ffffffff819bb07d)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/tcp_input.c (ffffffff819d98aa)
Location: include/linux/random.h:139
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa297d)
Location: include/linux/random.h:139
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
</details>
</li>
</ul>

## Differences
