# Function: <code>arch_atomic_long_sub_return</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
Location: include/linux/atomic/atomic-long.h:111
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff813aaed9)
Location: include/linux/atomic/atomic-long.h:111
Inline: True
```
```
In net/core/page_pool.c (ffffffff81ad946c)
Location: include/linux/atomic/atomic-long.h:111
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
Location: include/linux/atomic/atomic-long.h:111
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In mm/page_counter.c (ffffffff813c8875)
Location: include/linux/atomic/atomic-long.h:111
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff81431aa5)
Location: include/linux/atomic/atomic-long.h:111
Inline: True
```
```
In net/core/xdp.c (ffffffff81c51aa6)
Location: include/linux/atomic/atomic-long.h:111
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81c5a625)
Location: include/linux/atomic/atomic-long.h:111
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
Location: include/linux/atomic/atomic-long.h:111
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In mm/page_counter.c (ffffffff8144cf45)
Location: include/linux/atomic/atomic-long.h:111
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff814bcdd5)
Location: include/linux/atomic/atomic-long.h:111
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In net/core/xdp.c (ffffffff81e06e65)
Location: include/linux/atomic/atomic-long.h:111
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e10105)
Location: include/linux/atomic/atomic-long.h:111
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
