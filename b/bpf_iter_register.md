# Function: <code>bpf_iter_register</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff82d2d911)
Location: net/netlink/af_netlink.c:2819
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv6/route.c (ffffffff82d2fb3b)
Location: net/ipv6/route.c:6439
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8301c459)
Location: net/netlink/af_netlink.c:2851
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8301cdec)
Location: net/ipv4/tcp_ipv4.c:3016
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/udp.c (ffffffff8301d134)
Location: net/ipv4/udp.c:3231
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv6/route.c (ffffffff8301e72a)
Location: net/ipv6/route.c:6430
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8322759a)
Location: net/netlink/af_netlink.c:2861
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff83227edb)
Location: net/ipv4/tcp_ipv4.c:3038
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/udp.c (ffffffff83228219)
Location: net/ipv4/udp.c:3302
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/ipv6/route.c (ffffffff8322981d)
Location: net/ipv6/route.c:6501
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8331193a)
Location: net/netlink/af_netlink.c:2874
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff833122f6)
Location: net/ipv4/tcp_ipv4.c:3308
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/udp.c (ffffffff8331267e)
Location: net/ipv4/udp.c:3317
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/unix/af_unix.c (ffffffff8331345c)
Location: net/unix/af_unix.c:3378
Inline: True
Inline callers:
  - net/unix/af_unix.c:af_unix_init
```
```
In net/ipv6/route.c (ffffffff83313e34)
Location: net/ipv6/route.c:6661
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff834cb783)
Location: net/netlink/af_netlink.c:2860
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff834cc32f)
Location: net/ipv4/tcp_ipv4.c:3252
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/udp.c (ffffffff834cc757)
Location: net/ipv4/udp.c:3332
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/unix/af_unix.c (ffffffff834cd7c2)
Location: net/unix/af_unix.c:3660
Inline: True
Inline callers:
  - net/unix/af_unix.c:af_unix_init
```
```
In net/ipv6/route.c (ffffffff834ce1c4)
Location: net/ipv6/route.c:6654
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff83f0dc99)
Location: net/netlink/af_netlink.c:2933
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff83f0ec06)
Location: net/ipv4/tcp_ipv4.c:3363
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/udp.c (ffffffff83f0f140)
Location: net/ipv4/udp.c:3460
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/unix/af_unix.c (ffffffff83f1063e)
Location: net/unix/af_unix.c:3720
Inline: True
Inline callers:
  - net/unix/af_unix.c:af_unix_init
```
```
In net/ipv6/route.c (ffffffff83f1133f)
Location: net/ipv6/route.c:6661
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff837342a9)
Location: net/netlink/af_netlink.c:2907
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff83735216)
Location: net/ipv4/tcp_ipv4.c:3373
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/udp.c (ffffffff83735767)
Location: net/ipv4/udp.c:3623
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/unix/af_unix.c (ffffffff83736c6e)
Location: net/unix/af_unix.c:3640
Inline: True
Inline callers:
  - net/unix/af_unix.c:af_unix_init
```
```
In net/ipv6/route.c (ffffffff8373798f)
Location: net/ipv6/route.c:6659
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff839687e9)
Location: net/netlink/af_netlink.c:2901
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff839697d6)
Location: net/ipv4/tcp_ipv4.c:3580
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/udp.c (ffffffff83969dd7)
Location: net/ipv4/udp.c:3612
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_init
```
```
In net/unix/af_unix.c (ffffffff8396b31e)
Location: net/unix/af_unix.c:3657
Inline: True
Inline callers:
  - net/unix/af_unix.c:af_unix_init
```
```
In net/ipv6/route.c (ffffffff8396c049)
Location: net/ipv6/route.c:6661
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
```
</details>
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
