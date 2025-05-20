# Function: <code>skb_get_tx_queue</code>

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
In net/core/netpoll.c (ffffffff81738cfb)
Location: include/linux/netdevice.h:1912
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:1912
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818037ac)
Location: include/linux/netdevice.h:1912
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/netpoll.c (ffffffff817a4fbb)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817ae572)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/packet/af_packet.c (ffffffff818749ec)
Location: include/linux/netdevice.h:1952
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/netpoll.c (ffffffff817d3a2b)
Location: include/linux/netdevice.h:1934
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817ddbfe)
Location: include/linux/netdevice.h:1934
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/packet/af_packet.c (ffffffff818a8f3e)
Location: include/linux/netdevice.h:1934
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/sched/sch_generic.c (ffffffff817fd205)
Location: include/linux/netdevice.h:1958
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/packet/af_packet.c (ffffffff818cf925)
Location: include/linux/netdevice.h:1958
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/sched/sch_generic.c (ffffffff8187ac26)
Location: include/linux/netdevice.h:1974
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/packet/af_packet.c (ffffffff81954898)
Location: include/linux/netdevice.h:1974
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff81893a5a)
Location: include/linux/netdevice.h:2042
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff818ccf0d)
Location: include/linux/netdevice.h:2042
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (ffffffff818b4477)
Location: include/linux/netdevice.h:2107
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff818f824e)
Location: include/linux/netdevice.h:2107
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (ffffffff81900d97)
Location: include/linux/netdevice.h:2096
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff81957986)
Location: include/linux/netdevice.h:2096
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (ffffffff819330c7)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff8198de26)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (ffffffff81a07f3b)
Location: include/linux/netdevice.h:2194
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff81a65d3e)
Location: include/linux/netdevice.h:2194
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
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
In net/core/dev.c (ffffffff81a0962d)
Location: include/linux/netdevice.h:2258
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff81a6de5e)
Location: include/linux/netdevice.h:2258
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
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
In net/core/dev.c (ffffffff819eff9d)
Location: include/linux/netdevice.h:2322
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff81a566ce)
Location: include/linux/netdevice.h:2322
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
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
In net/core/dev.c (ffffffff81aa13cd)
Location: include/linux/netdevice.h:2342
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff81b0f4b3)
Location: include/linux/netdevice.h:2342
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
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
In net/core/dev.c (ffffffff81c192c0)
Location: include/linux/netdevice.h:2422
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff81c9665e)
Location: include/linux/netdevice.h:2422
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv6/ioam6.c (ffffffff81dd7244)
Location: include/linux/netdevice.h:2422
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In net/core/dev.c (ffffffff81dca2c0)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff81e5227e)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv6/ioam6.c (ffffffff81fa8bff)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In net/core/dev.c (ffffffff81e3ae40)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff81eadaee)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv6/ioam6.c (ffffffff8200958f)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In net/core/dev.c (ffffffff81ef91ce)
Location: include/linux/netdevice.h:2561
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff81f7058e)
Location: include/linux/netdevice.h:2561
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv6/ioam6.c (ffffffff820d852f)
Location: include/linux/netdevice.h:2561
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In net/core/dev.c (ffff800010bd10a4)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffff800010c394e4)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (c0cebd50)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (c0d4b910)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (c000000000caf344)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (c000000000d321cc)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (ffffffe00075b698)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffe0007aa90c)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (ffffffff818d30c7)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff8192dc96)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (ffffffff8188cf57)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff818e7796)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (ffffffff819240c7)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff8197ee26)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
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
In net/core/dev.c (ffffffff81945537)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
```
```
In net/sched/sch_generic.c (ffffffff819a13ac)
Location: include/linux/netdevice.h:2126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
</details>
</li>
</ul>

## Differences
