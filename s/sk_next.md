# Function: <code>sk_next</code>

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
In net/ipv4/raw.c (ffffffff817841e6)
Location: include/net/sock.h:530
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff817be3a3)
Location: include/net/sock.h:530
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff817e6a5e)
Location: include/net/sock.h:530
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/tcp_ipv4.c (ffffffff817e9196)
Location: include/net/sock.h:523
Inline: True
```
```
In net/ipv4/raw.c (ffffffff817f1786)
Location: include/net/sock.h:523
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff817f46b9)
Location: include/net/sock.h:523
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff8182b333)
Location: include/net/sock.h:523
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81854e34)
Location: include/net/sock.h:523
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/tcp_ipv4.c (ffffffff81819396)
Location: include/net/sock.h:544
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81822506)
Location: include/net/sock.h:544
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81825786)
Location: include/net/sock.h:544
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff8185cd63)
Location: include/net/sock.h:544
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81886ba4)
Location: include/net/sock.h:544
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/tcp_ipv4.c (ffffffff8183a55c)
Location: include/net/sock.h:559
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81843180)
Location: include/net/sock.h:559
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818477b6)
Location: include/net/sock.h:559
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff8188150f)
Location: include/net/sock.h:559
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff818ad0bf)
Location: include/net/sock.h:559
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/tcp_ipv4.c (ffffffff818ba05c)
Location: include/net/sock.h:563
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818c2b40)
Location: include/net/sock.h:563
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c7216)
Location: include/net/sock.h:563
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff819026af)
Location: include/net/sock.h:563
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff8192fcd2)
Location: include/net/sock.h:563
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/tcp_ipv4.c (ffffffff81910b1d)
Location: include/net/sock.h:570
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81918d87)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191c67a)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff81958bd3)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81988a12)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/tcp_ipv4.c (ffffffff8193e80d)
Location: include/net/sock.h:590
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819475d7)
Location: include/net/sock.h:590
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194ac1a)
Location: include/net/sock.h:590
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff8198d783)
Location: include/net/sock.h:590
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff819bf37f)
Location: include/net/sock.h:590
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/tcp_ipv4.c (ffffffff819a2c3f)
Location: include/net/sock.h:592
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819abc6a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819af261)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff819f8ea6)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a2dfba)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/raw.c (ffffffff819e291a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e5f71)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff81a2faf6)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a64b2a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/raw.c (ffffffff81acff1a)
Location: include/net/sock.h:634
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad25f1)
Location: include/net/sock.h:634
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff81b23b79)
Location: include/net/sock.h:634
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81b5d472)
Location: include/net/sock.h:634
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
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
In net/ipv4/raw.c (ffffffff81adbe9a)
Location: include/net/sock.h:641
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81adeda5)
Location: include/net/sock.h:641
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b32549)
Location: include/net/sock.h:641
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81b6bc62)
Location: include/net/sock.h:641
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
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
In net/ipv4/raw.c (ffffffff81ac6d3a)
Location: include/net/sock.h:641
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ac9d96)
Location: include/net/sock.h:641
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff81b20079)
Location: include/net/sock.h:641
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81b59f82)
Location: include/net/sock.h:641
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
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
In net/ipv4/raw.c (ffffffff81b8555a)
Location: include/net/sock.h:653
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b88626)
Location: include/net/sock.h:653
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff81be4f03)
Location: include/net/sock.h:653
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81c215f4)
Location: include/net/sock.h:653
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
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
In net/ipv4/udp.c (ffffffff81d19a61)
Location: include/net/sock.h:692
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff81d7ddae)
Location: include/net/sock.h:692
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_get_first
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
In net/ipv4/udp.c (ffffffff81ee0451)
Location: include/net/sock.h:723
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff81f4b164)
Location: include/net/sock.h:723
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_get_first
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
In net/ipv4/raw.c (ffffffff81f3af09)
Location: include/net/sock.h:725
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
```
```
In net/ipv4/udp.c (ffffffff81f4000e)
Location: include/net/sock.h:725
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/ping.c (ffffffff81f6b81c)
Location: include/net/sock.h:725
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
```
```
In net/unix/af_unix.c (ffffffff81faaf04)
Location: include/net/sock.h:725
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_get_first
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
In net/ipv4/raw.c (ffffffff82001019)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
```
```
In net/ipv4/udp.c (ffffffff82005f8e)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/ping.c (ffffffff82031b1c)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
```
```
In net/unix/af_unix.c (ffffffff820782f4)
Location: include/net/sock.h:708
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_get_first
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
In net/ipv4/raw.c (ffff800010c9682c)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9ad48)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffff800010ceefec)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffff800010d2aa18)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/raw.c (c0da4ec4)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0da7e70)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (c0df69d0)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (c0e2e918)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/raw.c (c000000000da8284)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000daba90)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (c000000000e14b74)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (c000000000e5bbc4)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/raw.c (ffffffe0007f5a58)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007f7520)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffe00083c0b8)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffe00086b0ce)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/raw.c (ffffffff8198278a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81985de1)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff819cf186)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a041ba)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/raw.c (ffffffff8193c24a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8193f8a1)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff8198bf46)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff819c0f7a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/raw.c (ffffffff819ecf5a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f05b1)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff81a39c06)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a6ec3a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/raw.c (ffffffff819f6e4a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fb631)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/unix/af_unix.c (ffffffff81a46246)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a7b26a)
Location: include/net/sock.h:592
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
</details>
</li>
</ul>

## Differences
