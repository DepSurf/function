# Function: <code>sock_rps_record_flow_hash</code>

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
In drivers/net/tun.c (ffffffff815ef3db)
Location: include/net/sock.h:878
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff81766250)
Location: include/net/sock.h:878
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81788a99)
Location: include/net/sock.h:878
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff817938e2)
Location: include/net/sock.h:878
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_sendpage
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
In drivers/net/tun.c (ffffffff8164df12)
Location: include/net/sock.h:880
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff817d27b0)
Location: include/net/sock.h:880
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff817f63f9)
Location: include/net/sock.h:880
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff818026fe)
Location: include/net/sock.h:880
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff8167fc10)
Location: include/net/sock.h:901
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff81802d62)
Location: include/net/sock.h:901
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81826ecb)
Location: include/net/sock.h:901
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff818336d3)
Location: include/net/sock.h:901
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff81694f7d)
Location: include/net/sock.h:918
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff81822b55)
Location: include/net/sock.h:918
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff8184864e)
Location: include/net/sock.h:918
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff81854433)
Location: include/net/sock.h:918
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff816ff6c1)
Location: include/net/sock.h:918
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff818a1c76)
Location: include/net/sock.h:918
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff818c80ae)
Location: include/net/sock.h:918
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff818d42c9)
Location: include/net/sock.h:918
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff8173f2bc)
Location: include/net/sock.h:925
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff818f679a)
Location: include/net/sock.h:925
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8192a9f1)
Location: include/net/sock.h:925
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff8175f326)
Location: include/net/sock.h:953
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81926682)
Location: include/net/sock.h:953
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8195a1f1)
Location: include/net/sock.h:953
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff8179cb5b)
Location: include/net/sock.h:956
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff8198900e)
Location: include/net/sock.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819bedbc)
Location: include/net/sock.h:956
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff819fe5ac)
Location: include/net/sock.h:956
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff817c05ed)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff819c046e)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819f59fc)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81a3519c)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff8188c12f)
Location: include/net/sock.h:1012
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81aa9ab5)
Location: include/net/sock.h:1012
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81ae3f5c)
Location: include/net/sock.h:1012
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a13c)
Location: include/net/sock.h:1012
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff8189a212)
Location: include/net/sock.h:1027
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81ab6e3e)
Location: include/net/sock.h:1027
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81af0e71)
Location: include/net/sock.h:1027
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81b38a81)
Location: include/net/sock.h:1027
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff8187bfe2)
Location: include/net/sock.h:1031
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81aa203e)
Location: include/net/sock.h:1031
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81adc631)
Location: include/net/sock.h:1031
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81b26771)
Location: include/net/sock.h:1031
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff8190d51f)
Location: include/net/sock.h:1043
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81b5de0e)
Location: include/net/sock.h:1043
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81b9ba1e)
Location: include/net/sock.h:1043
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81bec1ce)
Location: include/net/sock.h:1043
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81a60616)
Location: include/net/sock.h:1089
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81cec83c)
Location: include/net/sock.h:1089
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81d2dd16)
Location: include/net/sock.h:1089
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81d84716)
Location: include/net/sock.h:1089
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81bebd06)
Location: include/net/sock.h:1127
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81eb070e)
Location: include/net/sock.h:1127
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81ef5c36)
Location: include/net/sock.h:1127
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81f52036)
Location: include/net/sock.h:1127
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81c441b6)
Location: include/net/sock.h:1129
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81f0ebdd)
Location: include/net/sock.h:1129
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81f54fd6)
Location: include/net/sock.h:1129
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:__inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81fb1a46)
Location: include/net/sock.h:1129
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81cf9a76)
Location: include/net/sock.h:1106
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81fd2d42)
Location: include/net/sock.h:1106
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8201b246)
Location: include/net/sock.h:1106
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:__inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff8207f166)
Location: include/net/sock.h:1106
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffff8000109de00c)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffff800010c72a00)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffff800010cac744)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffff800010cf5864)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (c0ac1a1c)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (c0d7f9a0)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (c0db8320)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (c0dfc2a8)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (c000000000a9cff0)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (c000000000d77910)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (c000000000dc1cf0)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (c000000000e1ba50)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffe000625ae0)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffe0007d6240)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffe0008061be)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffe00084122a)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff817850bd)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff819602de)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8199579c)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff819d482c)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81764a0d)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81919dce)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8194f25c)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff819915ec)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff817b546d)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff819caaae)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81a0003c)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f2ac)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff817cf666)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff819d4622)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81a0a5f4)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81a4ad84)
Location: include/net/sock.h:966
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
```
</details>
</li>
</ul>

## Differences
