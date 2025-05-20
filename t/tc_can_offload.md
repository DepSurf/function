# Function: <code>tc_can_offload</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff818ce1bb)
Location: include/net/pkt_cls.h:648
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/cls_api.c (ffffffff818d4ba2)
Location: include/net/pkt_cls.h:648
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (ffffffff818f8fbc)
Location: include/net/pkt_cls.h:680
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff818f9a03)
Location: include/net/pkt_cls.h:680
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff818ff535)
Location: include/net/pkt_cls.h:680
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (ffffffff819587cc)
Location: include/net/pkt_cls.h:583
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff819591fb)
Location: include/net/pkt_cls.h:583
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff8195fef5)
Location: include/net/pkt_cls.h:583
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (ffffffff8198ec6c)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff8198f69b)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81996f60)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (ffffffff81a66f99)
Location: include/net/pkt_cls.h:591
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a675b5)
Location: include/net/pkt_cls.h:591
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_graft_helper
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81a6f2b8)
Location: include/net/pkt_cls.h:591
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/sch_fifo.c (ffffffff81a753d1)
Location: include/net/pkt_cls.h:591
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_mq.c (ffffffff81a6ef4a)
Location: include/net/pkt_cls.h:641
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a6fcd5)
Location: include/net/pkt_cls.h:641
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_graft_helper
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81a77c98)
Location: include/net/pkt_cls.h:641
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/sch_fifo.c (ffffffff81a7dde1)
Location: include/net/pkt_cls.h:641
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_mq.c (ffffffff81a5780a)
Location: include/net/pkt_cls.h:641
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81a58825)
Location: include/net/pkt_cls.h:641
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_graft_helper
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81a63799)
Location: include/net/pkt_cls.h:641
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/sch_fifo.c (ffffffff81a66c31)
Location: include/net/pkt_cls.h:641
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_mq.c (ffffffff81b1077a)
Location: include/net/pkt_cls.h:637
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81b11835)
Location: include/net/pkt_cls.h:637
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_graft_helper
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81b1cb19)
Location: include/net/pkt_cls.h:637
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/sch_fifo.c (ffffffff81b200f1)
Location: include/net/pkt_cls.h:637
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_mq.c (ffffffff81c97a61)
Location: include/net/pkt_cls.h:655
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81c989c5)
Location: include/net/pkt_cls.h:655
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_graft_helper
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81ca0d3c)
Location: include/net/pkt_cls.h:655
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/sch_fifo.c (ffffffff81ca8321)
Location: include/net/pkt_cls.h:655
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_mq.c (ffffffff81e53951)
Location: include/net/pkt_cls.h:680
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81e549f5)
Location: include/net/pkt_cls.h:680
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_graft_helper
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81e5cd7c)
Location: include/net/pkt_cls.h:680
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/sch_fifo.c (ffffffff81e65121)
Location: include/net/pkt_cls.h:680
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_mq.c (ffffffff81eaf1d1)
Location: include/net/pkt_cls.h:693
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81eb02a5)
Location: include/net/pkt_cls.h:693
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_graft_helper
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81eb9924)
Location: include/net/pkt_cls.h:693
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/sch_fifo.c (ffffffff81ec1061)
Location: include/net/pkt_cls.h:693
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_mq.c (ffffffff81f71c71)
Location: include/net/pkt_cls.h:680
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f72d15)
Location: include/net/pkt_cls.h:680
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_graft_helper
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81f7caec)
Location: include/net/pkt_cls.h:680
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/sch_fifo.c (ffffffff81f84361)
Location: include/net/pkt_cls.h:680
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_mq.c (ffff800010c3a9a0)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffff800010c3b608)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffff800010c4405c)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (c0d4c820)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (c0d4d360)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (c0d54aa0)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (c000000000d33784)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (c000000000d347c0)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (c000000000d3f3a4)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (ffffffe0007ab716)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffe0007ac24e)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffe0007b24a4)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (ffffffff8192eadc)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff8192f50b)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81936dd0)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (ffffffff818e85dc)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff818e900b)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff818f08d0)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (ffffffff8197fc6c)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff8198069b)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff81987f60)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/sch_mq.c (ffffffff819a21cc)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff819a2c0b)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_offload_dump_helper
```
```
In net/sched/cls_api.c (ffffffff819aa1c0)
Location: include/net/pkt_cls.h:570
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
</details>
</li>
</ul>

## Differences
