# Function: <code>qdisc_dev</code>

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
In net/sched/sch_generic.c (ffffffff81740f61)
Location: include/net/sch_generic.h:324
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81741ff5)
Location: include/net/sch_generic.h:324
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_get
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_graft
```
```
In net/sched/sch_api.c (ffffffff8174314c)
Location: include/net/sch_generic.h:324
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff8174602e)
Location: include/net/sch_generic.h:324
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/sch_fifo.c (ffffffff81748ed5)
Location: include/net/sch_generic.h:324
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff81749bd1)
Location: include/net/sch_generic.h:324
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
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
In net/sched/sch_generic.c (ffffffff817add6e)
Location: include/net/sch_generic.h:311
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff817aefc9)
Location: include/net/sch_generic.h:311
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_get
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff817b06c4)
Location: include/net/sch_generic.h:311
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b303a)
Location: include/net/sch_generic.h:311
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/sch_fifo.c (ffffffff817b5f25)
Location: include/net/sch_generic.h:311
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff817b6b3d)
Location: include/net/sch_generic.h:311
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
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
In net/sched/sch_generic.c (ffffffff817dd3e7)
Location: include/net/sch_generic.h:319
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff817de649)
Location: include/net/sch_generic.h:319
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_get
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff817dfba3)
Location: include/net/sch_generic.h:319
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff817e28ba)
Location: include/net/sch_generic.h:319
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/sch_fifo.c (ffffffff817e5925)
Location: include/net/sch_generic.h:319
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff817e65cb)
Location: include/net/sch_generic.h:319
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
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
In net/sched/sch_generic.c (ffffffff817fca28)
Location: include/net/sch_generic.h:348
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff817fdc79)
Location: include/net/sch_generic.h:348
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_get
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff817ff454)
Location: include/net/sch_generic.h:348
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff818021a1)
Location: include/net/sch_generic.h:348
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/sch_fifo.c (ffffffff8180545c)
Location: include/net/sch_generic.h:348
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
```
```
In net/sched/ematch.c (ffffffff818060ec)
Location: include/net/sch_generic.h:348
Inline: True
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
In net/sched/sch_generic.c (ffffffff8187b044)
Location: include/net/sch_generic.h:355
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff8187b889)
Location: include/net/sch_generic.h:355
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff8187d1c4)
Location: include/net/sch_generic.h:355
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff818803f2)
Location: include/net/sch_generic.h:355
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
```
```
In net/sched/sch_fifo.c (ffffffff8188416c)
Location: include/net/sch_generic.h:355
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffffffff818cd431)
Location: include/net/sch_generic.h:423
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff818cdf55)
Location: include/net/sch_generic.h:423
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff818cf7e4)
Location: include/net/sch_generic.h:423
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff818d316a)
Location: include/net/sch_generic.h:423
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff818d7d6c)
Location: include/net/sch_generic.h:423
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffffffff818f6fd4)
Location: include/net/sch_generic.h:488
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff818f9125)
Location: include/net/sch_generic.h:488
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff818fab81)
Location: include/net/sch_generic.h:488
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff818feb03)
Location: include/net/sch_generic.h:488
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff8190455c)
Location: include/net/sch_generic.h:488
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffffffff819566fd)
Location: include/net/sch_generic.h:563
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81958935)
Location: include/net/sch_generic.h:563
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff8195a449)
Location: include/net/sch_generic.h:563
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff8195e500)
Location: include/net/sch_generic.h:563
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff8196575c)
Location: include/net/sch_generic.h:563
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffffffff8198cb9d)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff8198edd5)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff819908e9)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81994dd0)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff8199c1ec)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/core/net-traces.c (ffffffff81a45d57)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
```
In net/sched/sch_generic.c (ffffffff81a64cc1)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81a66c05)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff81a68a29)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81a6db00)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff81a753bd)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/core/net-traces.c (ffffffff81a4a5e7)
Location: include/net/sch_generic.h:549
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
```
In net/sched/sch_generic.c (ffffffff81a6ce01)
Location: include/net/sch_generic.h:549
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81a6ebd5)
Location: include/net/sch_generic.h:549
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff81a7113a)
Location: include/net/sch_generic.h:549
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81a764c0)
Location: include/net/sch_generic.h:549
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff81a7ddcd)
Location: include/net/sch_generic.h:549
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/core/net-traces.c (ffffffff81a2f547)
Location: include/net/sch_generic.h:596
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
```
In net/sched/sch_generic.c (ffffffff81a55611)
Location: include/net/sch_generic.h:596
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81a57465)
Location: include/net/sch_generic.h:596
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff81a5990a)
Location: include/net/sch_generic.h:596
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81a5e3c0)
Location: include/net/sch_generic.h:596
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff81a66c1d)
Location: include/net/sch_generic.h:596
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/core/net-traces.c (ffffffff81ae4b27)
Location: include/net/sch_generic.h:601
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
```
In net/sched/sch_generic.c (ffffffff81b0e191)
Location: include/net/sch_generic.h:601
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81b102c5)
Location: include/net/sch_generic.h:601
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_change_real_num_tx
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff81b129ca)
Location: include/net/sch_generic.h:601
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81b175a0)
Location: include/net/sch_generic.h:601
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff81b200dd)
Location: include/net/sch_generic.h:601
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/core/net-traces.c (ffffffff81c64fc9)
Location: include/net/sch_generic.h:581
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
```
In net/sched/sch_generic.c (ffffffff81c94b35)
Location: include/net/sch_generic.h:581
Inline: True
Inline callers:
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81c974e5)
Location: include/net/sch_generic.h:581
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff81c98fbf)
Location: include/net/sch_generic.h:581
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81c9f350)
Location: include/net/sch_generic.h:581
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff81ca82ed)
Location: include/net/sch_generic.h:581
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/core/net-traces.c (ffffffff81e1b989)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
```
In net/sched/sch_generic.c (ffffffff81e505a5)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81e53365)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff81e54e9f)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81e5b580)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff81e650ed)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/core/net-traces.c (ffffffff81e8fbf5)
Location: include/net/sch_generic.h:566
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
  - net/core/net-traces.c:trace_event_get_offsets_qdisc_destroy
  - net/core/net-traces.c:trace_event_get_offsets_qdisc_reset
```
```
In net/sched/sch_generic.c (ffffffff81eabd65)
Location: include/net/sch_generic.h:566
Inline: True
Inline callers:
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81eaebe5)
Location: include/net/sch_generic.h:566
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff81eb074f)
Location: include/net/sch_generic.h:566
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81eb7ca8)
Location: include/net/sch_generic.h:566
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff81ec102d)
Location: include/net/sch_generic.h:566
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/core/net-traces.c (ffffffff81f51d29)
Location: include/net/sch_generic.h:567
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_destroy
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_destroy
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
  - net/core/net-traces.c:trace_event_get_offsets_qdisc_destroy
  - net/core/net-traces.c:trace_event_get_offsets_qdisc_reset
```
```
In net/sched/sch_generic.c (ffffffff81f6e805)
Location: include/net/sch_generic.h:567
Inline: True
Inline callers:
  - net/sched/sch_generic.c:mq_change_real_num_tx
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff81f71685)
Location: include/net/sch_generic.h:567
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
```
In net/sched/sch_api.c (ffffffff81f731bf)
Location: include/net/sch_generic.h:567
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81f7acb8)
Location: include/net/sch_generic.h:567
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff81f8432d)
Location: include/net/sch_generic.h:567
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_destroy
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_hd_init
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffff800010c38190)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffff800010c3abd0)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffff800010c3cb6c)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffff800010c43f68)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffff800010c4945c)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (c0d4a3ac)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (c0d4c9b8)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (c0d4e8d0)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (c0d5377c)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (c0d5a19c)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (c000000000d3100c)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (c000000000d339a0)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (c000000000d37c5c)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (c000000000d3d604)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (c000000000d46c00)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffffffe0007a9526)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffe0007ab8e8)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffe0007ad3ea)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffe0007b12f8)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffe0007b6aec)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffffffff8192ca0d)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff8192ec45)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff81930759)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81934c40)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff8193c05c)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffffffff818e650d)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff818e8745)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff818ea259)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff818ee740)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff818f5b5c)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffffffff8197db9d)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff8197fdd5)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff819818e9)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff81985dd0)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff8198d1ec)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
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
In net/sched/sch_generic.c (ffffffff819a010d)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff819a2335)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_walk
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump_class
  - net/sched/sch_mq.c:mq_find
  - net/sched/sch_mq.c:mq_leaf
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_graft
  - net/sched/sch_mq.c:mq_select_queue
  - net/sched/sch_mq.c:mq_dump
  - net/sched/sch_mq.c:mq_attach
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
  - net/sched/sch_mq.c:mq_offload
```
```
In net/sched/sch_api.c (ffffffff819a3e43)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_offload_dump_helper
  - net/sched/sch_api.c:qdisc_match_from_root
```
```
In net/sched/cls_api.c (ffffffff819a8dd0)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_chain_fill_node
  - net/sched/cls_api.c:tcf_fill_node
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_netif_keep_dst
```
```
In net/sched/sch_fifo.c (ffffffff819afa7c)
Location: include/net/sch_generic.h:552
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:fifo_init
  - net/sched/sch_fifo.c:fifo_init
```
</details>
</li>
</ul>

## Differences
