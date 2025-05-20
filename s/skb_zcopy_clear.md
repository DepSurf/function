# Function: <code>skb_zcopy_clear</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81835614)
Location: include/linux/skbuff.h:1295
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8188126e)
Location: include/linux/skbuff.h:1306
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a050c)
Location: include/linux/skbuff.h:1364
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
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
In net/core/skbuff.c (ffffffff818eaf39)
Location: include/linux/skbuff.h:1452
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff8198c70e)
Location: include/linux/skbuff.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81991613)
Location: include/linux/skbuff.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8199e6b5)
Location: include/linux/skbuff.h:1452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff8191d09e)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff819c307d)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819c81ed)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819d51b0)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff819ef3eb)
Location: include/linux/skbuff.h:1455
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff81aae66e)
Location: include/linux/skbuff.h:1455
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ab4fb2)
Location: include/linux/skbuff.h:1455
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ac0221)
Location: include/linux/skbuff.h:1455
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
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
In net/core/skbuff.c (ffffffff819ef09b)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff81ab8946)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ac00dc)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81acbc7b)
Location: include/linux/skbuff.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
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
In net/core/skbuff.c (ffffffff819d4879)
Location: include/linux/skbuff.h:1509
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff81aa3c3a)
Location: include/linux/skbuff.h:1509
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7106)
Location: include/linux/skbuff.h:1509
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ab6eeb)
Location: include/linux/skbuff.h:1509
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
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
In net/core/skbuff.c (ffffffff81a84740)
Location: include/linux/skbuff.h:1522
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff81b5fdea)
Location: include/linux/skbuff.h:1522
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81b63703)
Location: include/linux/skbuff.h:1522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81b740d8)
Location: include/linux/skbuff.h:1522
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfa445)
Location: include/linux/skbuff.h:1871
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da934a)
Location: include/linux/skbuff.h:1721
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e17f8e)
Location: include/linux/skbuff.h:1750
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed536f)
Location: include/linux/skbuff.h:1757
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
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
In net/core/skbuff.c (ffff800010bb7840)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffff800010c75e4c)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffff800010c7bccc)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffff800010c87e08)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (c0cd4448)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (c0d844f4)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (c0d89c4c)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c0d9717c)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (c000000000c8f50c)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (c000000000d7d794)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (c000000000d84944)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c000000000d94b54)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffe000747296)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffe0007d8e56)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffe0007dde44)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffe0007e90e0)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff818bd09e)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff81962eed)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8196805d)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81975020)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff81876fde)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff8191c9dd)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81921b4d)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8192eae0)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff8190e09e)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff819cd6bd)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819d282d)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819df7f0)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff8192f1ce)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp.c (ffffffff819d724d)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819dc3cd)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819e94a0)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
</details>
</li>
</ul>

## Differences
