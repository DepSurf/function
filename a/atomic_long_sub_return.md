# Function: <code>atomic_long_sub_return</code>

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
In mm/page_counter.c (ffffffff811f92d5)
Location: include/asm-generic/atomic-long.h:73
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812361bb)
Location: include/asm-generic/atomic-long.h:73
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff8189d8f0)
Location: include/asm-generic/atomic-long.h:73
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8121ce55)
Location: include/asm-generic/atomic-long.h:73
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8125fb35)
Location: include/asm-generic/atomic-long.h:73
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
In kernel/locking/rwsem-xadd.c (ffffffff818d27c0)
Location: include/asm-generic/atomic-long.h:73
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8122f455)
Location: include/asm-generic/atomic-long.h:73
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81273055)
Location: include/asm-generic/atomic-long.h:73
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff81909687)
Location: include/asm-generic/atomic-long.h:73
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8123acb6)
Location: include/asm-generic/atomic-long.h:73
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812804b9)
Location: include/asm-generic/atomic-long.h:73
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
In kernel/locking/rwsem-xadd.c (ffffffff81993677)
Location: include/asm-generic/atomic-long.h:74
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8125a546)
Location: include/asm-generic/atomic-long.h:74
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a2fe9)
Location: include/asm-generic/atomic-long.h:74
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff819efc45)
Location: include/asm-generic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8127e315)
Location: include/asm-generic/atomic-long.h:76
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812c9a35)
Location: include/asm-generic/atomic-long.h:76
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
In kernel/locking/rwsem-xadd.c (ffffffff81a2b675)
Location: include/asm-generic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff81292a05)
Location: include/asm-generic/atomic-long.h:76
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812dec65)
Location: include/asm-generic/atomic-long.h:76
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
In mm/page_counter.c (ffffffff812ad3c5)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fd316)
Location: include/asm-generic/atomic-long.h:110
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
In mm/page_counter.c (ffffffff812bef15)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130f806)
Location: include/asm-generic/atomic-long.h:110
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
In mm/page_counter.c (ffffffff812f4351)
Location: include/asm-generic/atomic-long.h:111
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_uncharge
```
```
In fs/fs-writeback.c (ffffffff81348f15)
Location: include/asm-generic/atomic-long.h:111
Inline: True
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
In mm/page_counter.c (ffffffff812ffc41)
Location: include/asm-generic/atomic-long.h:111
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_uncharge
```
```
In fs/fs-writeback.c (ffffffff81355e78)
Location: include/asm-generic/atomic-long.h:111
Inline: True
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
In mm/page_counter.c (ffffffff81306785)
Location: include/asm-generic/atomic-long.h:111
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff8135ca58)
Location: include/asm-generic/atomic-long.h:111
Inline: True
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
In mm/page_counter.c (ffffffff813505c4)
Location: include/linux/atomic/atomic-instrumented.h:1279
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff813aaed9)
Location: include/linux/atomic/atomic-instrumented.h:1279
Inline: True
```
```
In net/core/page_pool.c (ffffffff81ad946c)
Location: include/linux/atomic/atomic-instrumented.h:1279
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
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
In kernel/ucount.c (ffffffff8110517a)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In mm/page_counter.c (ffffffff813c8875)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff81431aa5)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
```
```
In net/core/xdp.c (ffffffff81c51aa6)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81c5a625)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
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
In kernel/ucount.c (ffffffff8112abca)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In mm/page_counter.c (ffffffff8144cf45)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff814bcdd5)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In net/core/xdp.c (ffffffff81e06e65)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e10105)
Location: include/linux/atomic/atomic-instrumented.h:1366
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
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
In kernel/ucount.c (ffffffff81137d56)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In mm/page_counter.c (ffffffff81482805)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff814f1ef5)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In net/core/xdp.c (ffffffff81e797a8)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e83997)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
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
In kernel/ucount.c (ffffffff81142f66)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In mm/page_counter.c (ffffffff814b1b85)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff81526605)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In net/core/skbuff.c (ffffffff81ed12f1)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/xdp.c (ffffffff81f3978a)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81f4481a)
Location: include/linux/atomic/atomic-instrumented.h:3414
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
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
In mm/page_counter.c (ffff800010360a9c)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c7268)
Location: include/asm-generic/atomic-long.h:110
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
In mm/page_counter.c (c0553208)
Location: include/asm-generic/atomic-long.h:604
Inline: True
```
```
In fs/fs-writeback.c (c05a1594)
Location: include/asm-generic/atomic-long.h:604
Inline: True
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
In mm/page_counter.c (c00000000044bc10)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
```
In fs/fs-writeback.c (c0000000004c4ec8)
Location: include/asm-generic/atomic-long.h:110
Inline: True
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
In mm/page_counter.c (ffffffe00024033c)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
```
In fs/fs-writeback.c (ffffffe000283f12)
Location: include/asm-generic/atomic-long.h:110
Inline: True
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
In mm/page_counter.c (ffffffff812b74f5)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81307de6)
Location: include/asm-generic/atomic-long.h:110
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
In mm/page_counter.c (ffffffff812a86c5)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812f8a06)
Location: include/asm-generic/atomic-long.h:110
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
In mm/page_counter.c (ffffffff812b5305)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81305bd6)
Location: include/asm-generic/atomic-long.h:110
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
In mm/page_counter.c (ffffffff812c5845)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81317116)
Location: include/asm-generic/atomic-long.h:110
Inline: True
```
</details>
</li>
</ul>

## Differences
