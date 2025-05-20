# Function: <code>qstats_drop_inc</code>

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
In net/core/dev.c (ffffffff8171a83f)
Location: include/net/sch_generic.h:558
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
```
In net/sched/sch_generic.c (ffffffff81741365)
Location: include/net/sch_generic.h:558
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81745a42)
Location: include/net/sch_generic.h:558
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8174913a)
Location: include/net/sch_generic.h:558
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
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
In net/core/dev.c (ffffffff81782e4a)
Location: include/net/sch_generic.h:578
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817ae0e9)
Location: include/net/sch_generic.h:578
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff817b2934)
Location: include/net/sch_generic.h:578
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff817b6113)
Location: include/net/sch_generic.h:578
Inline: True
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
In net/sched/sch_generic.c (ffffffff817dd7cc)
Location: include/net/sch_generic.h:586
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff817e20e4)
Location: include/net/sch_generic.h:586
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff817e5b97)
Location: include/net/sch_generic.h:586
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff817fce07)
Location: include/net/sch_generic.h:631
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81801634)
Location: include/net/sch_generic.h:631
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818056c7)
Location: include/net/sch_generic.h:631
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8187a567)
Location: include/net/sch_generic.h:646
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff8187f374)
Location: include/net/sch_generic.h:646
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818843d7)
Location: include/net/sch_generic.h:646
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_blackhole.c (ffffffff818d2157)
Location: include/net/sch_generic.h:744
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818d7f70)
Location: include/net/sch_generic.h:744
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_blackhole.c (ffffffff818fd547)
Location: include/net/sch_generic.h:843
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81904760)
Location: include/net/sch_generic.h:843
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81957086)
Location: include/net/sch_generic.h:912
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff8195cf87)
Location: include/net/sch_generic.h:912
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff819659d6)
Location: include/net/sch_generic.h:912
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8198d526)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81993487)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8199c466)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81a65214)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81a6b677)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81a755e9)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_generic.c (ffffffff81a6d344)
Location: include/net/sch_generic.h:877
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81a73de7)
Location: include/net/sch_generic.h:877
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81a74bd6)
Location: include/net/sch_generic.h:877
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81a7e3b9)
Location: include/net/sch_generic.h:877
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_generic.c (ffffffff81a55bc4)
Location: include/net/sch_generic.h:930
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81a5c987)
Location: include/net/sch_generic.h:930
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81a5d77f)
Location: include/net/sch_generic.h:930
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81a67206)
Location: include/net/sch_generic.h:930
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_generic.c (ffffffff81b0e944)
Location: include/net/sch_generic.h:937
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81b15b37)
Location: include/net/sch_generic.h:937
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81b16a5f)
Location: include/net/sch_generic.h:937
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81b206e6)
Location: include/net/sch_generic.h:937
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_generic.c (ffffffff81c94eed)
Location: include/net/sch_generic.h:903
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81c9cf57)
Location: include/net/sch_generic.h:903
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81c9e19f)
Location: include/net/sch_generic.h:903
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_handle
```
```
In net/sched/sch_fifo.c (ffffffff81ca8a0c)
Location: include/net/sch_generic.h:903
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_generic.c (ffffffff81e5099d)
Location: include/net/sch_generic.h:882
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81e593d7)
Location: include/net/sch_generic.h:882
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81e5a8bf)
Location: include/net/sch_generic.h:882
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_handle
```
```
In net/sched/sch_fifo.c (ffffffff81e6587c)
Location: include/net/sch_generic.h:882
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_generic.c (ffffffff81eac196)
Location: include/net/sch_generic.h:894
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81eb4e07)
Location: include/net/sch_generic.h:894
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81eb657e)
Location: include/net/sch_generic.h:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_handle
```
```
In net/sched/sch_fifo.c (ffffffff81ec17bc)
Location: include/net/sch_generic.h:894
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_generic.c (ffffffff81f6ec26)
Location: include/net/sch_generic.h:922
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81f77ac7)
Location: include/net/sch_generic.h:922
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81f7928e)
Location: include/net/sch_generic.h:922
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_handle
```
```
In net/sched/sch_fifo.c (ffffffff81f84afc)
Location: include/net/sch_generic.h:922
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_generic.c (ffff800010c38828)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (ffff800010c3f968)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffff800010c49714)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (c0d4aa04)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (c0d51310)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (c0d5a474)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (c000000000d31744)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (c000000000d39f0c)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (c000000000d46f88)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffe0007a9f28)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffe0007af464)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffe0007b6daa)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8192d396)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff819332f7)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8193c2d6)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff818e6e96)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff818ecdf7)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818f5dd6)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8197e526)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81984487)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8198d466)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff819a06dc)
Location: include/net/sch_generic.h:885
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff819a69c7)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff819afcf6)
Location: include/net/sch_generic.h:885
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
</details>
</li>
</ul>

## Differences
