# Function: <code>ipv6_can_nonlocal_bind</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff8196a78f)
Location: include/net/ipv6.h:785
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819937c7)
Location: include/net/ipv6.h:785
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffff819ce809)
Location: include/net/ipv6.h:785
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff819d1432)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819ff266)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffff81a3d0e9)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81a07f92)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a35e66)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffff81a73d49)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81af692d)
Location: include/net/ipv6.h:848
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b2af44)
Location: include/net/ipv6.h:848
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffff81b6e057)
Location: include/net/ipv6.h:848
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81b037b5)
Location: include/net/ipv6.h:848
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b399e7)
Location: include/net/ipv6.h:848
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffff81b7cada)
Location: include/net/ipv6.h:848
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81aeeff5)
Location: include/net/ipv6.h:849
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b276c0)
Location: include/net/ipv6.h:849
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/raw.c (ffffffff81b5815b)
Location: include/net/ipv6.h:849
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/datagram.c (ffffffff81b6b5ba)
Location: include/net/ipv6.h:849
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81baf3c5)
Location: include/net/ipv6.h:852
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81bed5fa)
Location: include/net/ipv6.h:852
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/raw.c (ffffffff81c20135)
Location: include/net/ipv6.h:852
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/datagram.c (ffffffff81c3341a)
Location: include/net/ipv6.h:852
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81d42748)
Location: include/net/ipv6.h:906
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81d85a54)
Location: include/net/ipv6.h:906
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/raw.c (ffffffff81dbce8f)
Location: include/net/ipv6.h:906
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/datagram.c (ffffffff81dd0c39)
Location: include/net/ipv6.h:906
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81f0b5f8)
Location: include/net/ipv6.h:939
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81f53535)
Location: include/net/ipv6.h:939
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/raw.c (ffffffff81f8ce9f)
Location: include/net/ipv6.h:939
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/datagram.c (ffffffff81fa2019)
Location: include/net/ipv6.h:939
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81f6b1d8)
Location: include/net/ipv6.h:936
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2f41)
Location: include/net/ipv6.h:936
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/raw.c (ffffffff81fed69b)
Location: include/net/ipv6.h:936
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/datagram.c (ffffffff82002ab3)
Location: include/net/ipv6.h:936
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff82031cc8)
Location: include/net/ipv6.h:936
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff82080819)
Location: include/net/ipv6.h:936
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/raw.c (ffffffff820bb29b)
Location: include/net/ipv6.h:936
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/datagram.c (ffffffff820d1a77)
Location: include/net/ipv6.h:936
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffff800010cc11d8)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffff800010cf68fc)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffff800010d3c714)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (c0dccf08)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c0dfd1c8)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (c0e3fb74)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (c000000000ddc47c)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c000000000e1ccc8)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (c000000000e7080c)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffe0008161c6)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffe000841e76)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffe0008791fc)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff819a7d32)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819d54f6)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffff81a133d9)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff819617f2)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819922b6)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffff819d0199)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81a125d2)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a3ff76)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffff81a7de59)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
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
In net/ipv4/ping.c (ffffffff81a1cfdd)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a4bb34)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/datagram.c (ffffffff81a8a6b5)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
```
</details>
</li>
</ul>

## Differences
