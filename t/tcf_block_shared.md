# Function: <code>tcf_block_shared</code>

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
In net/sched/sch_api.c (0)
Location: include/net/pkt_cls.h:53
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/pkt_cls.h:53
Inline: True
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
In net/sched/sch_api.c (0)
Location: include/net/pkt_cls.h:57
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/pkt_cls.h:57
Inline: True
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
In net/sched/sch_api.c (0)
Location: include/net/pkt_cls.h:57
Inline: True
```
```
In net/sched/cls_api.c (ffffffff8195f1a9)
Location: include/net/pkt_cls.h:57
Inline: True
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
In net/sched/sch_api.c (0)
Location: include/net/pkt_cls.h:57
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81996579)
Location: include/net/pkt_cls.h:57
Inline: True
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
In net/sched/sch_api.c (ffffffff81a686b5)
Location: include/net/pkt_cls.h:57
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
```
```
In net/sched/cls_api.c (ffffffff81a710c6)
Location: include/net/pkt_cls.h:57
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:tc_block_indr_cleanup
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
In net/sched/sch_api.c (ffffffff81a70dc5)
Location: include/net/pkt_cls.h:63
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
```
```
In net/sched/cls_api.c (ffffffff81a79aa6)
Location: include/net/pkt_cls.h:63
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:tc_block_indr_cleanup
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
In net/sched/sch_api.c (ffffffff81a59715)
Location: include/net/pkt_cls.h:63
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
```
```
In net/sched/cls_api.c (ffffffff81a62c67)
Location: include/net/pkt_cls.h:63
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:tc_block_indr_cleanup
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
In net/sched/sch_api.c (ffffffff81b127c9)
Location: include/net/pkt_cls.h:63
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
```
```
In net/sched/cls_api.c (ffffffff81b1bf77)
Location: include/net/pkt_cls.h:63
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:tc_block_indr_cleanup
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
In net/sched/sch_api.c (ffffffff81c9ab09)
Location: include/net/pkt_cls.h:63
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
```
```
In net/sched/cls_api.c (ffffffff81ca173c)
Location: include/net/pkt_cls.h:63
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:tc_block_indr_cleanup
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
In net/sched/sch_api.c (ffffffff81e56f7e)
Location: include/net/pkt_cls.h:63
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81e5e14c)
Location: include/net/pkt_cls.h:63
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:tc_block_indr_cleanup
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
In net/sched/sch_api.c (ffffffff81eb167e)
Location: include/net/pkt_cls.h:65
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81ebbc7c)
Location: include/net/pkt_cls.h:65
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:tc_block_indr_cleanup
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
In net/sched/sch_api.c (ffffffff81f7412e)
Location: include/net/pkt_cls.h:65
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81f7ee9c)
Location: include/net/pkt_cls.h:65
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:tc_block_indr_cleanup
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
In net/sched/sch_api.c (0)
Location: include/net/pkt_cls.h:57
Inline: True
```
```
In net/sched/cls_api.c (ffff800010c42e84)
Location: include/net/pkt_cls.h:57
Inline: True
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
In net/sched/sch_api.c (c0d4eb7c)
Location: include/net/pkt_cls.h:57
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
```
```
In net/sched/cls_api.c (c0d56e14)
Location: include/net/pkt_cls.h:57
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_offload_cmd
  - net/sched/cls_api.c:tc_indr_block_call
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
In net/sched/sch_api.c (c000000000d36858)
Location: include/net/pkt_cls.h:57
Inline: True
```
```
In net/sched/cls_api.c (c000000000d421a8)
Location: include/net/pkt_cls.h:57
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
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
In net/sched/sch_api.c (ffffffe0007ad5f8)
Location: include/net/pkt_cls.h:57
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
```
```
In net/sched/cls_api.c (ffffffe0007b4146)
Location: include/net/pkt_cls.h:57
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
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
In net/sched/sch_api.c (0)
Location: include/net/pkt_cls.h:57
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819363e9)
Location: include/net/pkt_cls.h:57
Inline: True
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
In net/sched/sch_api.c (0)
Location: include/net/pkt_cls.h:57
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818efee9)
Location: include/net/pkt_cls.h:57
Inline: True
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
In net/sched/sch_api.c (0)
Location: include/net/pkt_cls.h:57
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81987579)
Location: include/net/pkt_cls.h:57
Inline: True
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
In net/sched/sch_api.c (0)
Location: include/net/pkt_cls.h:57
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819a9a39)
Location: include/net/pkt_cls.h:57
Inline: True
```
</details>
</li>
</ul>

## Differences
