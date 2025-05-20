# Function: <code>dst_confirm_neigh</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81843f44)
Location: include/net/dst.h:443
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818467e9)
Location: include/net/dst.h:443
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff818637c1)
Location: include/net/dst.h:443
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff8189d0b6)
Location: include/net/dst.h:443
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff818a94b9)
Location: include/net/dst.h:443
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff818ac509)
Location: include/net/dst.h:443
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff818c3894)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c6219)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff818e3901)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff8191ca56)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff8192be82)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff8192eed2)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff819199fc)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191c085)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff8193a403)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff819750c9)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff81984382)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81988142)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff81947f35)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194a639)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81969eb1)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff819aad80)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff819ba8b9)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff819bea8a)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff819acbf7)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819aed3f)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff819d0f6e)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81a17ff4)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff81a29929)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a2da54)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff819e37b5)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e5a59)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81a07ac8)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81a4ec54)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff81a60485)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a645bf)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff81ad1089)
Location: include/net/dst.h:415
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ad57fa)
Location: include/net/dst.h:415
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81af72db)
Location: include/net/dst.h:415
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81b46537)
Location: include/net/dst.h:415
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/udp.c (ffffffff81b58fa5)
Location: include/net/dst.h:415
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b5cff6)
Location: include/net/dst.h:415
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff81adcfe5)
Location: include/net/dst.h:413
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ae1d98)
Location: include/net/dst.h:413
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81b0417a)
Location: include/net/dst.h:413
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81b55077)
Location: include/net/dst.h:413
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/udp.c (ffffffff81b675e2)
Location: include/net/dst.h:413
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b6b830)
Location: include/net/dst.h:413
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff81ac806a)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81acba6c)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81aefe0c)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81b42af6)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/udp.c (ffffffff81b557bc)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b59b77)
Location: include/net/dst.h:416
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff81b868d3)
Location: include/net/dst.h:418
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81b8a2fc)
Location: include/net/dst.h:418
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81bafe1c)
Location: include/net/dst.h:418
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81c08253)
Location: include/net/dst.h:418
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/udp.c (ffffffff81c1e295)
Location: include/net/dst.h:418
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81c211b0)
Location: include/net/dst.h:418
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff81d1729e)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81d1dbdb)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81d43458)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81da3009)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/udp.c (ffffffff81dba937)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81dbdeff)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff81eddac9)
Location: include/net/dst.h:412
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ee4c8a)
Location: include/net/dst.h:412
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81f0c444)
Location: include/net/dst.h:412
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81f72419)
Location: include/net/dst.h:412
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/udp.c (ffffffff81f8aa4d)
Location: include/net/dst.h:412
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81f8e49a)
Location: include/net/dst.h:412
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff81f3cd8f)
Location: include/net/dst.h:426
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81f4466c)
Location: include/net/dst.h:426
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81f6c0a7)
Location: include/net/dst.h:426
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81fd2509)
Location: include/net/dst.h:426
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/udp.c (ffffffff81fea34e)
Location: include/net/dst.h:426
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81feec60)
Location: include/net/dst.h:426
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff82003005)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8200a654)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff82032677)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff8209fa99)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/udp.c (ffffffff820b8114)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff820bc827)
Location: include/net/dst.h:419
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffff800010c98200)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9e3b4)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffff800010cc094c)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffff800010d12968)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffff800010d25ab0)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffff800010d2a490)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (c0da6190)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c0da919c)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (c0dccc0c)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (c0e187d8)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (c0e2930c)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (c0e2e4fc)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (c000000000da9528)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000db0330)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (c000000000ddbd88)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (c000000000e3f04c)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (c000000000e55658)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (c000000000e5b5dc)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffe0007f6560)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f8290)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffe0008170e2)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffe000858e20)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffe000866506)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffe00086acc8)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff81983625)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819858c9)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff819a7868)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff819ee2e4)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff819ffb15)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a03c4f)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff8193d0e5)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193f389)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81961328)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff819ab0a4)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff819bc8d5)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff819c0a0f)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff819eddf5)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819f0099)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81a12108)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81a58d64)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff81a6a595)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a6e6cf)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/raw.c (ffffffff819f7d38)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819fa920)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81a1ca6e)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81a64f44)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff81a76bb2)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a7acfa)
Location: include/net/dst.h:408
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
</details>
</li>
</ul>

## Differences
