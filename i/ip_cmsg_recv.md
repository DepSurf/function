# Function: <code>ip_cmsg_recv</code>

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
In net/ipv4/ip_sockglue.c (ffffffff81761dd7)
Location: include/net/ip.h:576
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff8178469a)
Location: include/net/ip.h:576
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff817a3629)
Location: include/net/ip.h:576
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff817e317e)
Location: include/net/ip.h:576
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff817f5a5a)
Location: include/net/ip.h:576
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff817cdfe0)
Location: include/net/ip.h:572
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff817f1c5a)
Location: include/net/ip.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81810668)
Location: include/net/ip.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/udp.c (ffffffff8185178a)
Location: include/net/ip.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81864a8e)
Location: include/net/ip.h:572
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff817fdd40)
Location: include/net/ip.h:602
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81822a4a)
Location: include/net/ip.h:602
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81841b68)
Location: include/net/ip.h:602
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff8189717d)
Location: include/net/ip.h:602
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff8181e238)
Location: include/net/ip.h:614
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff818436b2)
Location: include/net/ip.h:614
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff8186331f)
Location: include/net/ip.h:614
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff818bd525)
Location: include/net/ip.h:614
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff8189d148)
Location: include/net/ip.h:626
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff818c3092)
Location: include/net/ip.h:626
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff818e345b)
Location: include/net/ip.h:626
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81940645)
Location: include/net/ip.h:626
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff818f1634)
Location: include/net/ip.h:654
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81918b85)
Location: include/net/ip.h:654
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81939d8a)
Location: include/net/ip.h:654
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819995e3)
Location: include/net/ip.h:654
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff8191f191)
Location: include/net/ip.h:708
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff8194734f)
Location: include/net/ip.h:708
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81969a1b)
Location: include/net/ip.h:708
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819cff24)
Location: include/net/ip.h:708
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81981ae8)
Location: include/net/ip.h:746
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff819ab9cf)
Location: include/net/ip.h:746
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff819d06c0)
Location: include/net/ip.h:746
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3ec35)
Location: include/net/ip.h:746
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff819b8328)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff819e269f)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81a07210)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a758a5)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81aa2c48)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81ad04be)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81af7810)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6fac5)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81aacf58)
Location: include/net/ip.h:744
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81adc4ce)
Location: include/net/ip.h:744
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81b046f0)
Location: include/net/ip.h:744
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7e5f5)
Location: include/net/ip.h:744
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81a981a8)
Location: include/net/ip.h:748
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81ac743d)
Location: include/net/ip.h:748
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81aef700)
Location: include/net/ip.h:748
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6d20c)
Location: include/net/ip.h:748
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81b53638)
Location: include/net/ip.h:761
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81b85c5d)
Location: include/net/ip.h:761
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81bb0c9a)
Location: include/net/ip.h:761
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81c35127)
Location: include/net/ip.h:761
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81cdfc63)
Location: include/net/ip.h:759
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81d15fd1)
Location: include/net/ip.h:759
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81d441d4)
Location: include/net/ip.h:759
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd2aa8)
Location: include/net/ip.h:759
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81ea0103)
Location: include/net/ip.h:763
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81edce42)
Location: include/net/ip.h:763
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81f0d6a3)
Location: include/net/ip.h:763
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa3f94)
Location: include/net/ip.h:763
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81efe953)
Location: include/net/ip.h:783
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff81f3c092)
Location: include/net/ip.h:783
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81f6d307)
Location: include/net/ip.h:783
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff8200485d)
Location: include/net/ip.h:783
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81fc2b7b)
Location: include/net/ip.h:793
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff820021b6)
Location: include/net/ip.h:793
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff82033a5e)
Location: include/net/ip.h:793
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff820d3623)
Location: include/net/ip.h:793
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffff800010c696d4)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffff800010c964d4)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffff800010cc0108)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffff800010d3e1d4)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (c0d788f4)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (c0da57b4)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (c0dcc60c)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (c0e41534)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (c000000000d6e3a8)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (c000000000da7e30)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (c000000000ddb4e4)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (c000000000e72950)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffe0007cf54c)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffe0007f570a)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffe000816b9e)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffe00087a7e8)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81958198)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff8198250f)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff819a6fb0)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a14f35)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff81911c88)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff8193bfcf)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81960a70)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819d1cf5)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff819c2968)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff819eccdf)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81a11850)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7f9b5)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ip_sockglue.c (ffffffff819cc368)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (ffffffff819f6bcf)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/ping.c (ffffffff81a1c1c0)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8c275)
Location: include/net/ip.h:747
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_error
```
</details>
</li>
</ul>

## Differences
