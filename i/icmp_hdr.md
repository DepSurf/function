# Function: <code>icmp_hdr</code>

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
In net/ipv4/route.c (ffffffff817549ec)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761965)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177daf9)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff817858a3)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff817894a3)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff8178dcca)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_err
```
```
In net/ipv4/ping.c (ffffffff817a2fca)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_rcv
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
In net/ipv4/route.c (ffffffff817c0b6c)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cdc95)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eaf49)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff817f2eaa)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff817f6be3)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff817fcaa4)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81811da9)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff817f004c)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fd9f5)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b899)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81823c8a)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff81827b43)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff8182da04)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff818432b9)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff818100fc)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181de35)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183bfe9)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff8184496a)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff818492f6)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff8184eea9)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81864b09)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff8188f7af)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189cd3e)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb6f9)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff818c43a0)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff818c8db6)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff818cec29)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff818e4c69)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff818e356c)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f1221)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819111dd)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff8191a07d)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff8191ef43)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81925042)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff8193b54f)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff8191041c)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191ed81)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193fa0b)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819488e5)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff8194d974)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81953e52)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff8196b23f)
Location: include/linux/icmp.h:23
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff81972e6c)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff8198168d)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a3ef0)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819acf69)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff819b2163)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff819b876d)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff819d1f0e)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff819a97dc)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b7ecd)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dab10)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819e3c39)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff819e8f03)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff819ef46d)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81a08a7e)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff81a92c0e)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa27e6)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7c4f)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81acf9a5)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_err
```
```
In net/ipv4/udp.c (ffffffff81ad71e3)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81add3bd)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81af82bb)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff81a9caae)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacab6)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3aaf)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81adb925)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_err
```
```
In net/ipv4/udp.c (ffffffff81ae3843)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81aea10d)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81b0511b)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06d02)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (ffffffff81a87b6a)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97d08)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abeb6f)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81ac8443)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff81ace854)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81ad5876)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81af097c)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af243b)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (ffffffff81b4209a)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b53198)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c6af)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81b86cb3)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff81b8d224)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81b94736)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81bb07ec)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb294b)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (0)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdf88a)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c5cc)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81d178ee)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff81d1e3b1)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81d25ff6)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81d43d9b)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46127)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (0)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9e2da)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed200e)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81ede1ae)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff81ee5451)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81eed826)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81f0cdfb)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f507)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (0)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81efc190)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efcada)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f30ccc)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81f3d4b4)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff81f44c30)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81f4d1e6)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81f6ca6b)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f1f7)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (0)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81fc00f0)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc0aea)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6c0c)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff82003612)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff8200ac80)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff820132f6)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff820331bb)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035927)
Location: include/linux/icmp.h:20
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (ffff800010c593e8)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffff800010c692e0)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8de90)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffff800010c98608)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffff800010c9e860)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffff800010ca51f4)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffff800010cc1c9c)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (c0d68f3c)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (c0d784d4)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (c0d9cf30)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (c0da6464)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (c0daba84)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (c0db1b18)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (c0dcd434)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (c000000000d5b0b8)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (c000000000d6de64)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9c798)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (c000000000da9c90)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (c000000000db0f64)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (c000000000db9000)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (c000000000ddd230)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffe0007c30c2)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf204)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee32c)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffe0007f67f2)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffe0007fb422)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffe000800b24)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffe0008172ee)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff8194964c)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957d3d)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a980)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff81983aa9)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff81988d73)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff8198f20d)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff819a881e)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff8190313c)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191182d)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934440)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff8193d569)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff81942833)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81948ccd)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff819622de)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff819b3e1c)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c250d)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5150)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819ee279)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff819f3543)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff819f9aad)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81a130be)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
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
In net/ipv4/route.c (ffffffff819bd50c)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cbf0d)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eee00)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/raw.c (ffffffff819f82d9)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
```
In net/ipv4/udp.c (ffffffff819fd703)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/icmp.c (ffffffff81a03d9d)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_err
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv4/ping.c (ffffffff81a1da8e)
Location: include/linux/icmp.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_err
```
</details>
</li>
</ul>

## Differences
