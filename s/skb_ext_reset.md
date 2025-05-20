# Function: <code>skb_ext_reset</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919e9a)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff8192d4cb)
Location: include/linux/skbuff.h:4170
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e8159)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/skbuff.c (ffffffff819ec05c)
Location: include/linux/skbuff.h:4210
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff81a01316)
Location: include/linux/skbuff.h:4210
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/ipv4/tcp.c (ffffffff81aae662)
Location: include/linux/skbuff.h:4210
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ab4fa7)
Location: include/linux/skbuff.h:4210
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ac0215)
Location: include/linux/skbuff.h:4210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
```
In net/ipv4/udp.c (ffffffff81ad6064)
Location: include/linux/skbuff.h:4210
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81bab5dc)
Location: include/linux/skbuff.h:4210
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/skbuff.c (ffffffff819eb86c)
Location: include/linux/skbuff.h:4239
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff81a01b06)
Location: include/linux/skbuff.h:4239
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/ipv4/tcp.c (ffffffff81ab893a)
Location: include/linux/skbuff.h:4239
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ac00d1)
Location: include/linux/skbuff.h:4239
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81acbc6f)
Location: include/linux/skbuff.h:4239
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
```
In net/ipv4/udp.c (ffffffff81ae2644)
Location: include/linux/skbuff.h:4239
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81bbd15c)
Location: include/linux/skbuff.h:4239
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/skbuff.c (ffffffff819d1e5c)
Location: include/linux/skbuff.h:4303
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff819e8ab6)
Location: include/linux/skbuff.h:4303
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/ipv4/tcp.c (ffffffff81aa3c2e)
Location: include/linux/skbuff.h:4303
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aa70fa)
Location: include/linux/skbuff.h:4303
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ab6edf)
Location: include/linux/skbuff.h:4303
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
```
In net/ipv4/udp.c (ffffffff81acd564)
Location: include/linux/skbuff.h:4303
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81bac9ac)
Location: include/linux/skbuff.h:4303
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/skbuff.c (ffffffff81a81adc)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff81a96298)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/ipv4/tcp.c (ffffffff81b5fdde)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81b636f7)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81b740cc)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
```
In net/ipv4/udp.c (ffffffff81b8bf38)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81c7932c)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/skbuff.c (ffffffff81bf62cc)
Location: include/linux/skbuff.h:4763
Inline: True
```
```
In net/core/gro.c (ffffffff81c5381f)
Location: include/linux/skbuff.h:4763
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/ipv4/udp.c (ffffffff81d18c1c)
Location: include/linux/skbuff.h:4763
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81e1e2b9)
Location: include/linux/skbuff.h:4763
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/skbuff.c (ffffffff81da4bbc)
Location: include/linux/skbuff.h:4659
Inline: True
```
```
In net/core/gro.c (ffffffff81e08ef6)
Location: include/linux/skbuff.h:4659
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/ipv4/udp.c (ffffffff81ee1aa9)
Location: include/linux/skbuff.h:4659
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81ff6d05)
Location: include/linux/skbuff.h:4659
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff8200ef13)
Location: include/linux/skbuff.h:4659
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
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
In net/core/skbuff.c (ffffffff81e13830)
Location: include/linux/skbuff.h:4691
Inline: True
```
```
In net/core/gro.c (ffffffff81e7b617)
Location: include/linux/skbuff.h:4691
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/ipv4/udp.c (ffffffff81f414d9)
Location: include/linux/skbuff.h:4691
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff820733e5)
Location: include/linux/skbuff.h:4691
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff8208bb0c)
Location: include/linux/skbuff.h:4691
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
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
In net/core/skbuff.c (ffffffff81ed0860)
Location: include/linux/skbuff.h:4731
Inline: True
```
```
In net/core/gro.c (ffffffff81f3b8a7)
Location: include/linux/skbuff.h:4731
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/ipv4/udp.c (ffffffff82007135)
Location: include/linux/skbuff.h:4731
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff82147635)
Location: include/linux/skbuff.h:4731
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/fastopen.c (ffffffff8216190c)
Location: include/linux/skbuff.h:4731
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
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
In net/core/skbuff.c (ffff800010bb3d8c)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffff800010bc956c)
Location: include/linux/skbuff.h:4170
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9c724)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/skbuff.c (c0cd0d18)
Location: include/linux/skbuff.h:4170
Inline: True
```
```
In net/core/dev.c (c0ce4c08)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
```
```
In net/ipv4/udp.c (c0da7840)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/skbuff.c (c000000000c8a574)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (c000000000cab31c)
Location: include/linux/skbuff.h:4170
Inline: True
```
```
In net/ipv4/udp.c (c000000000daecf0)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/skbuff.c (ffffffe0007447c8)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffe0007561f2)
Location: include/linux/skbuff.h:4170
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fa718)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/skbuff.c (ffffffff818b9e9a)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff818cd4cb)
Location: include/linux/skbuff.h:4170
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81987fc9)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/skbuff.c (ffffffff81873dea)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff818875eb)
Location: include/linux/skbuff.h:4170
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81941a89)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/skbuff.c (ffffffff8190ae9a)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff8191e4cb)
Location: include/linux/skbuff.h:4170
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f2799)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/skbuff.c (ffffffff8192bf9a)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
```
```
In net/core/dev.c (ffffffff8193fb5b)
Location: include/linux/skbuff.h:4170
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fc5e5)
Location: include/linux/skbuff.h:4170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
</details>
</li>
</ul>

## Differences
