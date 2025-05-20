# Function: <code>__skb_queue_head</code>

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
In drivers/net/xen-netfront.c (ffffffff815fbcab)
Location: include/linux/skbuff.h:1608
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81704fb0)
Location: include/linux/skbuff.h:1608
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_input.c (ffffffff8177083d)
Location: include/linux/skbuff.h:1608
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8177946a)
Location: include/linux/skbuff.h:1608
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In drivers/net/xen-netfront.c (ffffffff8165bafa)
Location: include/linux/skbuff.h:1709
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8176bb80)
Location: include/linux/skbuff.h:1709
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_input.c (ffffffff817df82a)
Location: include/linux/skbuff.h:1709
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff817e663e)
Location: include/linux/skbuff.h:1709
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In drivers/net/xen-netfront.c (ffffffff816898d2)
Location: include/linux/skbuff.h:1724
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81798c50)
Location: include/linux/skbuff.h:1724
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81816d7e)
Location: include/linux/skbuff.h:1724
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In drivers/net/xen-netfront.c (ffffffff8169f051)
Location: include/linux/skbuff.h:1717
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff817b7200)
Location: include/linux/skbuff.h:1717
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81836fff)
Location: include/linux/skbuff.h:1717
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
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
In drivers/net/xen-netfront.c (ffffffff8170a1e8)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8182f800)
Location: include/linux/skbuff.h:1799
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff81748fc0)
Location: include/linux/skbuff.h:1810
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81879d20)
Location: include/linux/skbuff.h:1810
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff8176d05b)
Location: include/linux/skbuff.h:1888
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8189a990)
Location: include/linux/skbuff.h:1888
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff817aae38)
Location: include/linux/skbuff.h:1977
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818e4fb6)
Location: include/linux/skbuff.h:1977
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff817ce87b)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81917146)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In fs/io_uring.c (ffffffff81380549)
Location: include/linux/skbuff.h:2014
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/xen-netfront.c (ffffffff8189a2d2)
Location: include/linux/skbuff.h:2014
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819e9ac6)
Location: include/linux/skbuff.h:2014
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In fs/io_uring.c (ffffffff8138ee19)
Location: include/linux/skbuff.h:2035
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/xen-netfront.c (ffffffff818a9457)
Location: include/linux/skbuff.h:2035
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819e9866)
Location: include/linux/skbuff.h:2035
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In fs/io_uring.c (ffffffff8139bc9d)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
```
```
In drivers/net/xen-netfront.c (ffffffff8188c828)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819cf986)
Location: include/linux/skbuff.h:2051
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In fs/io_uring.c (ffffffff813e73a9)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/xen-netfront.c (ffffffff8191fd06)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81a7f4d6)
Location: include/linux/skbuff.h:2080
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff81a74e17)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81bf3816)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff81c090a1)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81da15a6)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff81c6e849)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81e0fe96)
Location: include/linux/skbuff.h:2325
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff81d230f4)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81ecc946)
Location: include/linux/skbuff.h:2332
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffff800010a08f50)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffff800010bb3a54)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccdb38)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c862b0)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074159e)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff8179349b)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818b7146)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871096)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff817c36fb)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81908146)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
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
In drivers/net/xen-netfront.c (ffffffff817dd9b9)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81929186)
Location: include/linux/skbuff.h:1991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
```
</details>
</li>
</ul>

## Differences
