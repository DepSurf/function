# Function: <code>list_cut_before</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b800a)
Location: include/linux/list.h:325
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
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
In mm/compaction.c (ffffffff81244d7b)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (ffffffff8190425f)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
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
In mm/compaction.c (ffffffff8125323b)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (ffffffff819353ae)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff81281f20)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In block/blk-mq.c (ffffffff815527c7)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
```
In net/core/dev.c (ffffffff81a09fa3)
Location: include/linux/list.h:399
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_list
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
In mm/compaction.c (ffffffff8128c05c)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In block/blk-mq.c (ffffffff8156e928)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
```
In block/blk-mq-sched.c (ffffffff8157325e)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In net/core/dev.c (ffffffff81a0b543)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_list
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
In mm/compaction.c (ffffffff81290f1a)
Location: include/linux/list.h:417
Inline: True
```
```
In block/blk-mq.c (ffffffff81576508)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
```
In block/blk-mq-sched.c (ffffffff8157b2ae)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In net/core/dev.c (ffffffff819f1b87)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff812d287b)
Location: include/linux/list.h:417
Inline: True
```
```
In block/blk-mq.c (ffffffff815db108)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
```
In block/blk-mq-sched.c (ffffffff815e061e)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In net/core/dev.c (ffffffff81aa34a7)
Location: include/linux/list.h:417
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff8132f8d6)
Location: include/linux/list.h:426
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff8168f08c)
Location: include/linux/list.h:426
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In net/core/dev.c (ffffffff81c1bbbc)
Location: include/linux/list.h:426
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff813a64da)
Location: include/linux/list.h:426
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff8174db8c)
Location: include/linux/list.h:426
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In net/core/dev.c (ffffffff81dccb8c)
Location: include/linux/list.h:426
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff813d9ca2)
Location: include/linux/list.h:426
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/migrate.c (ffffffff8146b464)
Location: include/linux/list.h:426
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In block/blk-mq-sched.c (ffffffff8178a10c)
Location: include/linux/list.h:426
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In net/core/dev.c (ffffffff81e3d6ec)
Location: include/linux/list.h:426
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff814039c7)
Location: include/linux/list.h:507
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/migrate.c (ffffffff8149a1cf)
Location: include/linux/list.h:507
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In block/blk-mq-sched.c (ffffffff817cc889)
Location: include/linux/list.h:507
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In net/core/dev.c (ffffffff81efbf8c)
Location: include/linux/list.h:507
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffff8000102ea828)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (ffff800010bd3648)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (c050dfdc)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (c0cee37c)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (c0000000003ad438)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (c000000000cb2230)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffe0001feec6)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (ffffffe00075d858)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff8124b88b)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (ffffffff818d5382)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff8123e82b)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (ffffffff8188f1f2)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff8124962b)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (ffffffff819263ae)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In mm/compaction.c (ffffffff81258eab)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In net/core/dev.c (ffffffff81947953)
Location: include/linux/list.h:385
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
</details>
</li>
</ul>

## Differences
