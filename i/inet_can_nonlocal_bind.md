# Function: <code>inet_can_nonlocal_bind</code>

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
In net/ipv4/af_inet.c (ffffffff8195a732)
Location: include/net/inet_sock.h:378
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff8196a942)
Location: include/net/inet_sock.h:378
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81993750)
Location: include/net/inet_sock.h:378
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff819bf2f2)
Location: include/net/inet_sock.h:374
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff819d1635)
Location: include/net/inet_sock.h:374
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819ff1ed)
Location: include/net/inet_sock.h:374
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff819f5f32)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81a08195)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a35ded)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff81ae441f)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81af6a36)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b2aec8)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff81af134f)
Location: include/net/inet_sock.h:369
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81b038ae)
Location: include/net/inet_sock.h:369
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b39884)
Location: include/net/inet_sock.h:369
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff81adcb0e)
Location: include/net/inet_sock.h:369
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81aef0f5)
Location: include/net/inet_sock.h:369
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b27560)
Location: include/net/inet_sock.h:369
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff81b9befe)
Location: include/net/inet_sock.h:368
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81baf4c2)
Location: include/net/inet_sock.h:368
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81bed49a)
Location: include/net/inet_sock.h:368
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/raw.c (ffffffff81d15d54)
Location: include/net/inet_sock.h:386
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/af_inet.c (ffffffff81d2de23)
Location: include/net/inet_sock.h:386
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81d42863)
Location: include/net/inet_sock.h:386
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81d8598b)
Location: include/net/inet_sock.h:386
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/raw.c (ffffffff81edc194)
Location: include/net/inet_sock.h:386
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/af_inet.c (ffffffff81ef5d53)
Location: include/net/inet_sock.h:386
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81f0b713)
Location: include/net/inet_sock.h:386
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81f5346c)
Location: include/net/inet_sock.h:386
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/raw.c (ffffffff81f3b224)
Location: include/net/inet_sock.h:388
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/af_inet.c (ffffffff81f555b3)
Location: include/net/inet_sock.h:388
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81f6b2f3)
Location: include/net/inet_sock.h:388
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2e90)
Location: include/net/inet_sock.h:388
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/raw.c (ffffffff82001334)
Location: include/net/inet_sock.h:420
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/af_inet.c (ffffffff8201ba0c)
Location: include/net/inet_sock.h:420
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff82031de8)
Location: include/net/inet_sock.h:420
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff82080676)
Location: include/net/inet_sock.h:420
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffff800010cac818)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffff800010cc1390)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffff800010cf68ac)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (c0db8de4)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (c0dcd144)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c0dfd280)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (c000000000dc26b4)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (c000000000ddc708)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c000000000e1ce94)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffe000806780)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffe0008163a2)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffe000841f50)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff81995cd2)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff819a7f35)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819d547d)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff8194f792)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff819619f5)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8199223d)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff81a00572)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81a127d5)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a3fefd)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/af_inet.c (ffffffff81a0aa32)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffffffff81a1d199)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a4ba63)
Location: include/net/inet_sock.h:375
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
</details>
</li>
</ul>

## Differences
