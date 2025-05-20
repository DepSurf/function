# Function: <code>sk_rethink_txhash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8177a08f)
Location: include/net/sock.h:1703
Inline: True
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
In net/core/sock.c (ffffffff8176b3da)
Location: include/net/sock.h:1664
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff817e72a6)
Location: include/net/sock.h:1664
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff817984ad)
Location: include/net/sock.h:1726
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81817b54)
Location: include/net/sock.h:1726
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff817b6049)
Location: include/net/sock.h:1731
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81837f99)
Location: include/net/sock.h:1731
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8182e0a6)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff818b76d1)
Location: include/net/sock.h:1745
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8187897d)
Location: include/net/sock.h:1756
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff8190cfb9)
Location: include/net/sock.h:1756
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8189941a)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff819326da)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b2df)
Location: include/net/sock.h:1841
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff818e371a)
Location: include/net/sock.h:1853
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff819965fb)
Location: include/net/sock.h:1853
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f6b3)
Location: include/net/sock.h:1853
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff819158fa)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff819cd171)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff819d6262)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff819e8a8a)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81ab9348)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac26d5)
Location: include/net/sock.h:1912
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff819e8bca)
Location: include/net/sock.h:1924
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81ac474e)
Location: include/net/sock.h:1924
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdf84)
Location: include/net/sock.h:1924
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff819ced00)
Location: include/net/sock.h:1941
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81aaf836)
Location: include/net/sock.h:1941
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9115)
Location: include/net/sock.h:1941
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff81a7e41c)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81b6c568)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff81b7664d)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff81bf1f27)
Location: include/net/sock.h:2102
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81cfb7c5)
Location: include/net/sock.h:2102
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05df6)
Location: include/net/sock.h:2102
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff81d9f6cf)
Location: include/net/sock.h:2139
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0305)
Location: include/net/sock.h:2139
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb121)
Location: include/net/sock.h:2139
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_plb.c (ffffffff81edb627)
Location: include/net/sock.h:2139
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
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
In net/core/sock.c (ffffffff81e0d647)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81f1e85f)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29c94)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_plb.c (ffffffff81f3a6e7)
Location: include/net/sock.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
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
In net/core/sock.c (ffffffff81eca7d8)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81fd96f0)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee804)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
```
```
In net/ipv4/tcp_plb.c (ffffffff82000857)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/ipv4/tcp_plb.c:tcp_plb_check_rehash
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
In net/core/sock.c (ffff800010bae9c4)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffff800010c7faa0)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffff800010c89250)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (c0ccc1e0)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (c0d8ee38)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (c0d982ac)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (c000000000c847a0)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (c000000000d8a3c0)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (c000000000d964e0)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffe000740800)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffe0007e199a)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea1ba)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff818b58fa)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff8196cfe1)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff819760d2)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8186f84a)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81926ad1)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff8192fb92)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff819068fa)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff819d77b1)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff819e08a2)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8192792c)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff819e13d1)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea562)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
</details>
</li>
</ul>

## Differences
