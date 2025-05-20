# Function: <code>arch_atomic64_sub_return</code>

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
In kernel/locking/rwsem-xadd.c (ffffffff819efc45)
Location: arch/x86/include/asm/atomic64_64.h:157
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff8127e315)
Location: arch/x86/include/asm/atomic64_64.h:157
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812c9a35)
Location: arch/x86/include/asm/atomic64_64.h:157
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
Location: arch/x86/include/asm/atomic64_64.h:163
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In mm/page_counter.c (ffffffff81292a05)
Location: arch/x86/include/asm/atomic64_64.h:163
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812dec65)
Location: arch/x86/include/asm/atomic64_64.h:163
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
Location: arch/x86/include/asm/atomic64_64.h:163
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fd316)
Location: arch/x86/include/asm/atomic64_64.h:163
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
Location: arch/x86/include/asm/atomic64_64.h:163
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130f806)
Location: arch/x86/include/asm/atomic64_64.h:163
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
In kernel/bpf/syscall.c (ffffffff811fc369)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81246ced)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812a54f6)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812bbc3d)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812d3d18)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/page_counter.c (ffffffff812f4351)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_uncharge
```
```
In fs/fs-writeback.c (ffffffff81348f15)
Location: arch/x86/include/asm/atomic64_64.h:164
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
In kernel/bpf/syscall.c (ffffffff811fb4bd)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8125135a)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812b0984)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812c76ed)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812df710)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/page_counter.c (ffffffff812ffc41)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_uncharge
```
```
In fs/fs-writeback.c (ffffffff81355e78)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f9469)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/net_namespace.c:__net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a35cd0)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In kernel/bpf/syscall.c (ffffffff811fc1dd)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81255454)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812b5fb6)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812ce066)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff812e8040)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/page_counter.c (ffffffff81306785)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff8135ca58)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819dea58)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81a1ce23)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In kernel/bpf/syscall.c (ffffffff8122cd3d)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In kernel/events/uprobes.c (ffffffff81290e93)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812f885d)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff813134e6)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff8132ff52)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/page_counter.c (ffffffff813505c4)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff813aaed9)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81a8e861)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81ad06a3)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/core/page_pool.c (ffffffff81ad946c)
Location: arch/x86/include/asm/atomic64_64.h:164
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
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In kernel/bpf/syscall.c (ffffffff8126f0fd)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In kernel/events/uprobes.c (ffffffff812e634c)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8135eddb)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8137e8a8)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff813a0347)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/page_counter.c (ffffffff813c8875)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff81431aa5)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81c04782)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81c4df32)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/core/xdp.c (ffffffff81c51aa6)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81c5a625)
Location: arch/x86/include/asm/atomic64_64.h:164
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
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In kernel/bpf/syscall.c (ffffffff812c497d)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In mm/page_counter.c (ffffffff8144cf45)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff814bcdd5)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In net/core/net_namespace.c (ffffffff81db4252)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e02d73)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
```
```
In net/core/xdp.c (ffffffff81e06e65)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e10105)
Location: arch/x86/include/asm/atomic64_64.h:164
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
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In kernel/bpf/syscall.c (ffffffff812eba5d)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In mm/page_counter.c (ffffffff81482805)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff814f1ef5)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In drivers/xen/grant-table.c (ffffffff81a62c34)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In net/core/net_namespace.c (ffffffff81e24902)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81e752f3)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
```
```
In net/core/xdp.c (ffffffff81e797a8)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e83997)
Location: arch/x86/include/asm/atomic64_64.h:83
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
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - kernel/ucount.c:inc_rlimit_get_ucounts
  - kernel/ucount.c:do_dec_rlimit_put_ucounts
  - kernel/ucount.c:dec_rlimit_ucounts
```
```
In kernel/bpf/syscall.c (ffffffff81309fad)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In mm/page_counter.c (ffffffff814b1b85)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In fs/fs-writeback.c (ffffffff81526605)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_io_lists_depopulated
```
```
In drivers/xen/grant-table.c (ffffffff81ab5264)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In net/core/skbuff.c (ffffffff81ed12f1)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/net_namespace.c (ffffffff81ee2552)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/sock_diag.c (ffffffff81f34b93)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
```
```
In net/core/xdp.c (ffffffff81f3978a)
Location: arch/x86/include/asm/atomic64_64.h:83
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81f4481a)
Location: arch/x86/include/asm/atomic64_64.h:83
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
In kernel/kthread.c (ffff8000101288f8)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
```
```
In kernel/acct.c (ffff8000101c7f34)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d082c)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dca60)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de818)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfa00)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4acc)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/audit_tree.c (ffff8000101f550c)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/arraymap.c (ffff80001027b8fc)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffff80001028ff58)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffff80001029c468)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffff8000102b7c90)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffff8000102bc748)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: arch/arm64/include/asm/atomic.h:92
Inline: False
```
```
In mm/backing-dev.c (ffff8000102df660)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffff8000102e783c)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffff8000102f2794)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffff8000103466cc)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/page_counter.c (ffff800010360a9c)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
```
```
In mm/memcontrol.c (ffff800010364cc8)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - mm/memcontrol.c:percpu_ref_put_many
```
```
In mm/hugetlb_cgroup.c (ffff80001036d724)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (0)
Location: arch/arm64/include/asm/atomic.h:92
Inline: False
```
```
In mm/hmm.c (ffff80001037b988)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffff80001038571c)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
```
```
In fs/inode.c (ffff8000103acee8)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffff8000103caaec)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffff8000103d92c8)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffff8000103e1478)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffff8000103e8f5c)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffff8000103e93bc)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In fs/aio.c (ffff8000103fc564)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__arm64_sys_io_destroy
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffff800010405dc0)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db5dc)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
```
```
In block/blk-core.c (ffff8000105e4184)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffff8000105e8858)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
```
```
In block/blk-merge.c (ffff8000105eb908)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
```
```
In block/blk-mq-sched.c (ffff8000105f71c4)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffff80001060ea38)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffff800010611c50)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffff80001063559c)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffff800010922318)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: arch/arm64/include/asm/atomic.h:92
Inline: False
```
```
In drivers/scsi/scsi_lib.c (ffff80001097831c)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffff800010aeab08)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In net/unix/scm.c (ffff800010cf548c)
Location: arch/arm64/include/asm/atomic.h:92
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b74f5)
Location: arch/x86/include/asm/atomic64_64.h:163
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81307de6)
Location: arch/x86/include/asm/atomic64_64.h:163
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
Location: arch/x86/include/asm/atomic64_64.h:163
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812f8a06)
Location: arch/x86/include/asm/atomic64_64.h:163
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
Location: arch/x86/include/asm/atomic64_64.h:163
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81305bd6)
Location: arch/x86/include/asm/atomic64_64.h:163
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
Location: arch/x86/include/asm/atomic64_64.h:163
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81317116)
Location: arch/x86/include/asm/atomic64_64.h:163
Inline: True
```
</details>
</li>
</ul>

## Differences
