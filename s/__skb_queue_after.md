# Function: <code>__skb_queue_after</code>

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
Location: include/linux/skbuff.h:1580
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81704fb0)
Location: include/linux/skbuff.h:1580
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:skb_append
```
```
In net/ipv4/tcp_input.c (ffffffff817705e6)
Location: include/linux/skbuff.h:1580
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81775591)
Location: include/linux/skbuff.h:1580
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8176bc85)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_input.c (ffffffff817df453)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff817e663e)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1696
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81798d55)
Location: include/linux/skbuff.h:1696
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81816d7e)
Location: include/linux/skbuff.h:1696
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1689
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff817b7305)
Location: include/linux/skbuff.h:1689
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81836fff)
Location: include/linux/skbuff.h:1689
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1771
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8182f905)
Location: include/linux/skbuff.h:1771
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff818b3ce5)
Location: include/linux/skbuff.h:1771
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1782
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81879e25)
Location: include/linux/skbuff.h:1782
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81908c73)
Location: include/linux/skbuff.h:1782
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1860
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8189aa95)
Location: include/linux/skbuff.h:1860
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81936ebb)
Location: include/linux/skbuff.h:1860
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818e50bb)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff8199c4d3)
Location: include/linux/skbuff.h:1950
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8191724b)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff819d2f79)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1987
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/xen-netfront.c (ffffffff8189a2d2)
Location: include/linux/skbuff.h:1987
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819e9bcb)
Location: include/linux/skbuff.h:1987
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81abd9b3)
Location: include/linux/skbuff.h:1987
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/xen-netfront.c (ffffffff818a9457)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819e996b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81ac923b)
Location: include/linux/skbuff.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:2024
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
```
```
In drivers/net/xen-netfront.c (ffffffff8188c828)
Location: include/linux/skbuff.h:2024
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff819cfa8b)
Location: include/linux/skbuff.h:2024
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81ab4163)
Location: include/linux/skbuff.h:2024
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:2053
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
```
```
In drivers/net/xen-netfront.c (ffffffff8191fd06)
Location: include/linux/skbuff.h:2053
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81a7f5db)
Location: include/linux/skbuff.h:2053
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81b70fe1)
Location: include/linux/skbuff.h:2053
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:2404
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81bf394b)
Location: include/linux/skbuff.h:2404
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81d00461)
Location: include/linux/skbuff.h:2404
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:2262
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81da170b)
Location: include/linux/skbuff.h:2262
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81ec5541)
Location: include/linux/skbuff.h:2262
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81e0fffb)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81f268c1)
Location: include/linux/skbuff.h:2298
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:2305
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81eccaab)
Location: include/linux/skbuff.h:2305
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81feb2a9)
Location: include/linux/skbuff.h:2305
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffff800010bb3988)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffff800010c85b1c)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (c0ccdc48)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (c0d94d64)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (c000000000c86478)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (c000000000d91d60)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffe0007416b8)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffe0007e72d2)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff818b724b)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff81972de9)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
In net/core/skbuff.c (ffffffff8187119b)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff8192c8b9)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8190824b)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff819dd5b9)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
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
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff8192928b)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_queue_head
```
```
In net/ipv4/tcp_output.c (ffffffff819e7239)
Location: include/linux/skbuff.h:1964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
</details>
</li>
</ul>

## Differences
