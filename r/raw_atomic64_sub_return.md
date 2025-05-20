# Function: <code>raw_atomic64_sub_return</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
Location: include/linux/atomic/atomic-arch-fallback.h:2891
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In kernel/bpf/syscall.c (ffffffff812eba5d)
Location: include/linux/atomic/atomic-arch-fallback.h:2891
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In mm/page_counter.c (ffffffff81482805)
Location: include/linux/atomic/atomic-arch-fallback.h:2891
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff814f1ef5)
Location: include/linux/atomic/atomic-arch-fallback.h:2891
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In drivers/xen/grant-table.c (ffffffff81a62c34)
Location: include/linux/atomic/atomic-arch-fallback.h:2891
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In net/core/net_namespace.c (ffffffff81e24902)
Location: include/linux/atomic/atomic-arch-fallback.h:2891
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e752f3)
Location: include/linux/atomic/atomic-arch-fallback.h:2891
Inline: True
```
```
In net/core/xdp.c (ffffffff81e797a8)
Location: include/linux/atomic/atomic-arch-fallback.h:2891
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e83997)
Location: include/linux/atomic/atomic-arch-fallback.h:2891
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
Location: include/linux/atomic/atomic-arch-fallback.h:2896
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In kernel/bpf/syscall.c (ffffffff81309fad)
Location: include/linux/atomic/atomic-arch-fallback.h:2896
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In mm/page_counter.c (ffffffff814b1b85)
Location: include/linux/atomic/atomic-arch-fallback.h:2896
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff81526605)
Location: include/linux/atomic/atomic-arch-fallback.h:2896
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In drivers/xen/grant-table.c (ffffffff81ab5264)
Location: include/linux/atomic/atomic-arch-fallback.h:2896
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In net/core/skbuff.c (ffffffff81ed12f1)
Location: include/linux/atomic/atomic-arch-fallback.h:2896
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/net_namespace.c (ffffffff81ee2552)
Location: include/linux/atomic/atomic-arch-fallback.h:2896
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81f34b93)
Location: include/linux/atomic/atomic-arch-fallback.h:2896
Inline: True
```
```
In net/core/xdp.c (ffffffff81f3978a)
Location: include/linux/atomic/atomic-arch-fallback.h:2896
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81f4481a)
Location: include/linux/atomic/atomic-arch-fallback.h:2896
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
