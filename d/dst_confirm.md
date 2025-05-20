# Function: <code>dst_confirm</code>

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
In net/ipv4/tcp_input.c (ffffffff817725df)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781f76)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/raw.c (ffffffff81784fda)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81787823)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff817a3ca4)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff817d6c96)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff817e25ef)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff817e6026)
Location: include/net/dst.h:432
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/tcp_input.c (ffffffff817e0d3b)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef5f5)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/raw.c (ffffffff817f25d2)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f4f7c)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81810a02)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff818461c1)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff81850936)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff8185442f)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/tcp_input.c (ffffffff8181113d)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181fe45)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv4/raw.c (ffffffff818233b4)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81826049)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81841f0f)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/route.c (ffffffff81877f21)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/udp.c (ffffffff81882785)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81886151)
Location: include/net/dst.h:441
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
