# Function: <code>__sk_del_node_init</code>

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
In net/ipv4/raw.c (ffffffff817843b6)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/unix/af_unix.c (ffffffff817bfd44)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_bind
```
```
In net/packet/af_packet.c (ffffffff81805869)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/ipv4/inet_hashtables.c (ffffffff817ce56b)
Location: include/net/sock.h:563
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff817f1976)
Location: include/net/sock.h:563
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff817f3dcb)
Location: include/net/sock.h:563
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/unix/af_unix.c (ffffffff8182da03)
Location: include/net/sock.h:563
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81876429)
Location: include/net/sock.h:563
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/ipv4/inet_hashtables.c (ffffffff817fe37b)
Location: include/net/sock.h:584
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff818226f6)
Location: include/net/sock.h:584
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81824fdb)
Location: include/net/sock.h:584
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/unix/af_unix.c (ffffffff8185f4c7)
Location: include/net/sock.h:584
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818aa929)
Location: include/net/sock.h:584
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/ipv4/inet_hashtables.c (ffffffff8181e74f)
Location: include/net/sock.h:598
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff81843346)
Location: include/net/sock.h:598
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818475da)
Location: include/net/sock.h:598
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81882d79)
Location: include/net/sock.h:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818d143a)
Location: include/net/sock.h:598
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/ipv4/inet_hashtables.c (ffffffff8189d66b)
Location: include/net/sock.h:602
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff818c2d12)
Location: include/net/sock.h:602
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818c7036)
Location: include/net/sock.h:602
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81905125)
Location: include/net/sock.h:602
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81956356)
Location: include/net/sock.h:602
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/ipv4/inet_hashtables.c (ffffffff818f237d)
Location: include/net/sock.h:609
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff81918802)
Location: include/net/sock.h:609
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8191db26)
Location: include/net/sock.h:609
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8195a76c)
Location: include/net/sock.h:609
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819b177c)
Location: include/net/sock.h:609
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/ipv4/inet_hashtables.c (ffffffff8191fd7d)
Location: include/net/sock.h:629
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff81946fd2)
Location: include/net/sock.h:629
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8194c0a6)
Location: include/net/sock.h:629
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198f45c)
Location: include/net/sock.h:629
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819e8b5c)
Location: include/net/sock.h:629
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/ipv4/inet_hashtables.c (ffffffff8198268d)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff819ab652)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819b0893)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819fac70)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a58ecc)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a747b4)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffff819e2322)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819e7526)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a31900)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a8efdc)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aab16a)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffff81acf922)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad497f)
Location: include/net/sock.h:673
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b25e06)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b8b3c1)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba760e)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffff81adc202)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae0ebf)
Location: include/net/sock.h:680
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b347ab)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b9a391)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb646b)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffff81ac7172)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81acc1e0)
Location: include/net/sock.h:680
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b225ba)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b892f6)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba542b)
Location: include/net/sock.h:680
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffff81b85992)
Location: include/net/sock.h:692
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8aa70)
Location: include/net/sock.h:692
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81be930d)
Location: include/net/sock.h:692
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81c55406)
Location: include/net/sock.h:692
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c72fab)
Location: include/net/sock.h:692
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/udp.c (ffffffff81d19857)
Location: include/net/sock.h:731
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81d8048d)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81df51a8)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16d3b)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff81e37bf7)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In net/ipv4/udp.c (ffffffff81ee01b2)
Location: include/net/sock.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/unix/af_unix.c (ffffffff81f4b73e)
Location: include/net/sock.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/packet/af_packet.c (ffffffff81fc7b28)
Location: include/net/sock.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee70b)
Location: include/net/sock.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff82010e78)
Location: include/net/sock.h:757
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In net/ipv4/raw.c (ffffffff81f3bb14)
Location: include/net/sock.h:759
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3f672)
Location: include/net/sock.h:759
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/ping.c (ffffffff81f6b560)
Location: include/net/sock.h:759
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81fab4de)
Location: include/net/sock.h:759
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/packet/af_packet.c (ffffffff82028ab8)
Location: include/net/sock.h:759
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206a80b)
Location: include/net/sock.h:759
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff8208dc38)
Location: include/net/sock.h:759
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In net/ipv4/raw.c (ffffffff82001c34)
Location: include/net/sock.h:742
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff820055a2)
Location: include/net/sock.h:742
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/ping.c (ffffffff82031940)
Location: include/net/sock.h:742
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff820788ce)
Location: include/net/sock.h:742
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/packet/af_packet.c (ffffffff820f84f8)
Location: include/net/sock.h:742
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e43c)
Location: include/net/sock.h:742
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff821640f8)
Location: include/net/sock.h:742
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In net/ipv4/raw.c (ffff800010c96d94)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffff800010c9b5fc)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (ffff800010cf2b5c)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffff800010d5c204)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f06c)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (c0da4ab0)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c0da83c0)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (c0df8900)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c0e5c214)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e79220)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (c000000000da78cc)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c000000000dac894)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (c000000000e17fb0)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c000000000e97c44)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf2c0)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffe0007f53be)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f99d6)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (ffffffe00083e1da)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffe0008923c4)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac208)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffff81982192)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81987396)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819d0f90)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a2e66c)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a4fa)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffff8193bc52)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81940e56)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198dd50)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819eb85c)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a070ea)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffff819ec962)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f1b66)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a3ba10)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a9a21c)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab63aa)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/ipv4/raw.c (ffffffff819f6852)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819fb456)
Location: include/net/sock.h:631
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a46d60)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81aa6f4c)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac24ca)
Location: include/net/sock.h:631
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
