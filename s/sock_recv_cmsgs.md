# Function: <code>sock_recv_cmsgs</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81d15f1e)
Location: include/net/sock.h:2690
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81d1bdda)
Location: include/net/sock.h:2690
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81db837c)
Location: include/net/sock.h:2690
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81dbd18f)
Location: include/net/sock.h:2690
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81df5656)
Location: include/net/sock.h:2690
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff81e36edb)
Location: include/net/sock.h:2690
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/ipv4/raw.c (ffffffff81edcdae)
Location: include/net/sock.h:2736
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ee2cca)
Location: include/net/sock.h:2736
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81f883ac)
Location: include/net/sock.h:2736
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81f8d1af)
Location: include/net/sock.h:2736
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81fc94fe)
Location: include/net/sock.h:2736
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff820108fb)
Location: include/net/sock.h:2736
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/ipv4/raw.c (ffffffff81f3bffe)
Location: include/net/sock.h:2724
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81f42562)
Location: include/net/sock.h:2724
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81fe8cbc)
Location: include/net/sock.h:2724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fed97f)
Location: include/net/sock.h:2724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff8202bab4)
Location: include/net/sock.h:2724
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff8208d0ab)
Location: include/net/sock.h:2724
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/ipv4/raw.c (ffffffff8200211e)
Location: include/net/sock.h:2714
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8200854e)
Location: include/net/sock.h:2714
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff820b67f5)
Location: include/net/sock.h:2714
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bb58f)
Location: include/net/sock.h:2714
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff820fb564)
Location: include/net/sock.h:2714
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff8216356b)
Location: include/net/sock.h:2714
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
