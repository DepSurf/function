# Function: <code>sock_recv_ts_and_drops</code>

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
In net/ipv4/raw.c (ffffffff817845f8)
Location: include/net/sock.h:2165
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff817884c3)
Location: include/net/sock.h:2165
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff817e2e52)
Location: include/net/sock.h:2165
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff817e577e)
Location: include/net/sock.h:2165
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff8180446f)
Location: include/net/sock.h:2165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff817f1bb8)
Location: include/net/sock.h:2145
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff817f5d7d)
Location: include/net/sock.h:2145
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff8185131d)
Location: include/net/sock.h:2145
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81853a36)
Location: include/net/sock.h:2145
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff818784e6)
Location: include/net/sock.h:2145
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff818229a8)
Location: include/net/sock.h:2212
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff818270c2)
Location: include/net/sock.h:2212
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81883170)
Location: include/net/sock.h:2212
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81885746)
Location: include/net/sock.h:2212
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff818acd3c)
Location: include/net/sock.h:2212
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff818435df)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81847208)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff818a7fd7)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff818abb0d)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff818d5374)
Location: include/net/sock.h:2237
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff818c2fbf)
Location: include/net/sock.h:2251
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff818c6c68)
Location: include/net/sock.h:2251
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff8192aa87)
Location: include/net/sock.h:2251
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8192e6cd)
Location: include/net/sock.h:2251
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81959e24)
Location: include/net/sock.h:2251
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff81918acc)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8191d318)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81982da0)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff8198765d)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff819aef77)
Location: include/net/sock.h:2258
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff81947299)
Location: include/net/sock.h:2372
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8194b8c8)
Location: include/net/sock.h:2372
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819b9466)
Location: include/net/sock.h:2372
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bdc6e)
Location: include/net/sock.h:2372
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff819e5944)
Location: include/net/sock.h:2372
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff819ab919)
Location: include/net/sock.h:2378
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819aff9f)
Location: include/net/sock.h:2378
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a27f43)
Location: include/net/sock.h:2378
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a2c754)
Location: include/net/sock.h:2378
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81a55371)
Location: include/net/sock.h:2378
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff819e25e9)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819e6c3c)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a5e9ac)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a63294)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81a8c441)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff81ad0429)
Location: include/net/sock.h:2451
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ad448a)
Location: include/net/sock.h:2451
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b57f12)
Location: include/net/sock.h:2451
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b5c1e4)
Location: include/net/sock.h:2451
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81b87811)
Location: include/net/sock.h:2451
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff81adc439)
Location: include/net/sock.h:2472
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ae09f1)
Location: include/net/sock.h:2472
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b665c6)
Location: include/net/sock.h:2472
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b6a8d4)
Location: include/net/sock.h:2472
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81b972f1)
Location: include/net/sock.h:2472
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff81ac73ab)
Location: include/net/sock.h:2508
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81acca9a)
Location: include/net/sock.h:2508
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b54747)
Location: include/net/sock.h:2508
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81b58e74)
Location: include/net/sock.h:2508
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81b862f1)
Location: include/net/sock.h:2508
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff81b85bcb)
Location: include/net/sock.h:2567
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81b8b423)
Location: include/net/sock.h:2567
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81c1bbe4)
Location: include/net/sock.h:2567
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81c20422)
Location: include/net/sock.h:2567
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81c526b1)
Location: include/net/sock.h:2567
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffff800010c96454)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffff800010c9d150)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffff800010d25ea0)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d28598)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffff800010d57c44)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (c0da56e8)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (c0daa6cc)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (c0e2a2cc)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d674)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (c0e59bac)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (c000000000da7d50)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (c000000000dac2b8)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (c000000000e53c08)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c000000000e59954)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (c000000000e92cdc)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffe0007f5668)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffe0007f91d6)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffe000865222)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffe000869e22)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffe00088f8fe)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff81982459)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81986aac)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819fe03c)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a02924)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81a2bad1)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff8193bf19)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8194056c)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819badfc)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff819bf6e4)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff819e8cc1)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff819ecc29)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819f127c)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a68abc)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a6d3a4)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81a97681)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
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
In net/ipv4/raw.c (ffffffff819f6b19)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819faf5c)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a750a7)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81a799c4)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81aa3fa1)
Location: include/net/sock.h:2399
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
</details>
</li>
</ul>

## Differences
