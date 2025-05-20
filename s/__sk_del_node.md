# Function: <code>__sk_del_node</code>

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
In net/ipv4/raw.c (ffffffff817843bb)
Location: include/net/sock.h:564
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/unix/af_unix.c (ffffffff817bfd49)
Location: include/net/sock.h:564
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_bind
```
```
In net/packet/af_packet.c (ffffffff8180586e)
Location: include/net/sock.h:564
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
In net/ipv4/inet_hashtables.c (ffffffff817ce570)
Location: include/net/sock.h:557
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff817f197b)
Location: include/net/sock.h:557
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff817f3dd4)
Location: include/net/sock.h:557
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/unix/af_unix.c (ffffffff8182da08)
Location: include/net/sock.h:557
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff8187642e)
Location: include/net/sock.h:557
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
In net/ipv4/inet_hashtables.c (ffffffff817fe380)
Location: include/net/sock.h:578
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff818226fb)
Location: include/net/sock.h:578
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81824fe4)
Location: include/net/sock.h:578
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/unix/af_unix.c (ffffffff8185f4cc)
Location: include/net/sock.h:578
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818aa92e)
Location: include/net/sock.h:578
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
In net/ipv4/inet_hashtables.c (ffffffff8181e754)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff8184334b)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818475e3)
Location: include/net/sock.h:592
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81882d7e)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818d143f)
Location: include/net/sock.h:592
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
In net/ipv4/inet_hashtables.c (ffffffff8189d674)
Location: include/net/sock.h:596
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff818c2d1b)
Location: include/net/sock.h:596
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818c7043)
Location: include/net/sock.h:596
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8190512e)
Location: include/net/sock.h:596
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff8195635f)
Location: include/net/sock.h:596
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
In net/ipv4/inet_hashtables.c (ffffffff818f240a)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff8191880b)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8191db33)
Location: include/net/sock.h:603
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8195a776)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819b1785)
Location: include/net/sock.h:603
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
In net/ipv4/inet_hashtables.c (ffffffff8191fe0a)
Location: include/net/sock.h:623
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff81946fdb)
Location: include/net/sock.h:623
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8194c0b3)
Location: include/net/sock.h:623
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198f466)
Location: include/net/sock.h:623
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819e8b65)
Location: include/net/sock.h:623
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
In net/ipv4/inet_hashtables.c (ffffffff81982713)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/raw.c (ffffffff819ab65b)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819b08a0)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819fac79)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a58ed6)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a747be)
Location: include/net/sock.h:625
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
In net/ipv4/raw.c (ffffffff819e232b)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819e7533)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a31909)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a8efe6)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aab174)
Location: include/net/sock.h:625
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
In net/ipv4/raw.c (ffffffff81acf92b)
Location: include/net/sock.h:667
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad498c)
Location: include/net/sock.h:667
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b25e16)
Location: include/net/sock.h:667
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b8b3cb)
Location: include/net/sock.h:667
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba7618)
Location: include/net/sock.h:667
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
In net/ipv4/raw.c (ffffffff81adc20b)
Location: include/net/sock.h:674
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae0ecc)
Location: include/net/sock.h:674
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b347b4)
Location: include/net/sock.h:674
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b9a39b)
Location: include/net/sock.h:674
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb6481)
Location: include/net/sock.h:674
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
In net/ipv4/raw.c (ffffffff81ac717b)
Location: include/net/sock.h:674
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81acc1ed)
Location: include/net/sock.h:674
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b225c3)
Location: include/net/sock.h:674
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b89300)
Location: include/net/sock.h:674
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba5441)
Location: include/net/sock.h:674
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
In net/ipv4/raw.c (ffffffff81b8599b)
Location: include/net/sock.h:686
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8aa7d)
Location: include/net/sock.h:686
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81be9319)
Location: include/net/sock.h:686
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81c55410)
Location: include/net/sock.h:686
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c72fc1)
Location: include/net/sock.h:686
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
In net/ipv4/udp.c (ffffffff81d19864)
Location: include/net/sock.h:725
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81d80496)
Location: include/net/sock.h:725
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81df51b1)
Location: include/net/sock.h:725
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16d4f)
Location: include/net/sock.h:725
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff81e37c00)
Location: include/net/sock.h:725
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
In net/ipv4/udp.c (ffffffff81ee01bf)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/unix/af_unix.c (ffffffff81f4b747)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/packet/af_packet.c (ffffffff81fc7b31)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee71f)
Location: include/net/sock.h:751
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff82010e82)
Location: include/net/sock.h:751
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
In net/ipv4/raw.c (ffffffff81f3bb1d)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3f67f)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/ping.c (ffffffff81f6b569)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81fab4e7)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/packet/af_packet.c (ffffffff82028ac1)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206a818)
Location: include/net/sock.h:753
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff8208dc42)
Location: include/net/sock.h:753
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
In net/ipv4/raw.c (ffffffff82001c3d)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff820055af)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/ping.c (ffffffff82031949)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff820788d7)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/packet/af_packet.c (ffffffff820f8501)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e449)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff82164102)
Location: include/net/sock.h:736
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
In net/ipv4/raw.c (ffff800010c96d9c)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffff800010c9b604)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (ffff800010cf2b64)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffff800010d5c20c)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f074)
Location: include/net/sock.h:625
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
In net/ipv4/raw.c (c0da4abc)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c0da83cc)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (c0df890c)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c0e5c220)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e7922c)
Location: include/net/sock.h:625
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
In net/ipv4/raw.c (c000000000da78d8)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c000000000dac8a0)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (c000000000e17fbc)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c000000000e97c54)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf2d0)
Location: include/net/sock.h:625
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
In net/ipv4/raw.c (ffffffe0007f53c2)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f99da)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (ffffffe00083e1e0)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffe0008923c8)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac20c)
Location: include/net/sock.h:625
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
In net/ipv4/raw.c (ffffffff8198219b)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819873a3)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819d0f99)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a2e676)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a504)
Location: include/net/sock.h:625
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
In net/ipv4/raw.c (ffffffff8193bc5b)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81940e63)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198dd59)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819eb866)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a070f4)
Location: include/net/sock.h:625
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
In net/ipv4/raw.c (ffffffff819ec96b)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f1b73)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a3ba19)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a9a226)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab63b4)
Location: include/net/sock.h:625
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
In net/ipv4/raw.c (ffffffff819f685b)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819fb463)
Location: include/net/sock.h:625
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a46d69)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81aa6f56)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac24d4)
Location: include/net/sock.h:625
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
