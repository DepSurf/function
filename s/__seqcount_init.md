# Function: <code>__seqcount_init</code>

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
In kernel/fork.c (ffffffff8107ebc0)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In mm/page_alloc.c (ffffffff8181d6bc)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In fs/dcache.c (ffffffff81225816)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/fs_struct.c (ffffffff81241713)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff81259e6e)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff813cb605)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff813cd3ba)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In lib/flex_proportions.c (ffffffff813e9826)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a30fe)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/md/md.c (ffffffff8168f3d7)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - drivers/md/md.c:md_rdev_init
```
```
In net/core/neighbour.c (ffffffff81728e22)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
```
```
In net/ipv4/inetpeer.c (ffffffff81757c5d)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81793db2)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/ipv4/inet_fragment.c (ffffffff817a180a)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b3671)
Location: include/linux/seqlock.h:54
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
In kernel/fork.c (ffffffff81080884)
Location: include/linux/seqlock.h:54
Inline: True
```
```
In mm/page_alloc.c (ffffffff818979ea)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In fs/dcache.c (ffffffff8124d911)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/fs_struct.c (ffffffff81269a53)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff8128287e)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff8140f8c5)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff81411801)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff814131b0)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In lib/flex_proportions.c (ffffffff8142fc06)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa171)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8164c5d8)
Location: include/linux/seqlock.h:54
Inline: True
```
```
In net/core/neighbour.c (ffffffff81792902)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
```
```
In net/sched/sch_generic.c (ffffffff817ae773)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff817c3efd)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81801712)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f4e0)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/xfrm/xfrm_policy.c (ffffffff81820e83)
Location: include/linux/seqlock.h:54
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
In kernel/fork.c (ffffffff8108514a)
Location: include/linux/seqlock.h:54
Inline: True
```
```
In mm/page_alloc.c (ffffffff818cc13d)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In fs/dcache.c (ffffffff812609f1)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/fs_struct.c (ffffffff8127ca03)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff8129639e)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff8142ac55)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff8142cb91)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff8142e6e0)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In lib/flex_proportions.c (ffffffff8144be36)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8162843e)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8167e2e8)
Location: include/linux/seqlock.h:54
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff817a422a)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff817c01d2)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
```
```
In net/sched/sch_generic.c (ffffffff817dde15)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff817f3a1d)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81832522)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/ipv4/inet_fragment.c (ffffffff81840a30)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/xfrm/xfrm_policy.c (ffffffff8202a14c)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
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
In arch/x86/kernel/tsc.c (0)
Location: include/linux/seqlock.h:54
Inline: True
```
```
In kernel/fork.c (ffffffff81082066)
Location: include/linux/seqlock.h:54
Inline: True
```
```
In mm/page_alloc.c (ffffffff819036c0)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In fs/dcache.c (ffffffff8126e1f9)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/fs_struct.c (0)
Location: include/linux/seqlock.h:54
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812a3225)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff81438e74)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff81439e99)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff8143ba00)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163dd58)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81693428)
Location: include/linux/seqlock.h:54
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff817c2374)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff817de84a)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
```
```
In net/sched/sch_generic.c (ffffffff817fd3f2)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81813e0d)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff8185382c)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/ipv4/inet_fragment.c (ffffffff8186231f)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/xfrm/xfrm_policy.c (ffffffff8210d784)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
```
```
In lib/flex_proportions.c (ffffffff818ec5e6)
Location: include/linux/seqlock.h:54
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In kernel/fork.c (ffffffff810888d0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In mm/page_alloc.c (ffffffff8198d5d0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In fs/dcache.c (ffffffff81290b19)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/fs_struct.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812c65b5)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff81464e51)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff81465eb9)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff81467a10)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a6ad8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816fd338)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8183bd8d)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff818590b7)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
```
```
In net/sched/sch_generic.c (ffffffff8187ae6d)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818d36ac)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/ipv4/inet_fragment.c (ffffffff818e240f)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/xfrm/xfrm_policy.c (ffffffff82717b00)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
```
```
In lib/flex_proportions.c (ffffffff819725b6)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff826dcb87)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In kernel/fork.c (ffffffff8108c7ee)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In mm/page_alloc.c (ffffffff819e9e7e)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/fs_struct.c (ffffffff812d47c1)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff812ef6e5)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff814987a2)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff8149989b)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff8149b880)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e2d92)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8173b444)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff818864fc)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff818a46ad)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
```
```
In net/sched/sch_generic.c (ffffffff818cd249)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff818e7765)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81929b65)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff82741ef6)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
```
```
In lib/flex_proportions.c (ffffffff819ce9e6)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff82892fed)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810943af)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In kernel/sched/psi.c (ffffffff810eee9c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (ffffffff828b945d)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/fs_struct.c (ffffffff812e9b91)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff81304095)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff814b28f2)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814b3afe)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff814b5b90)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81706234)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8175ec04)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff818a6c7c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff818c7cd4)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (ffffffff818f85a9)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81914615)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81959155)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff828fc1c1)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (ffffffff81a07ea6)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff828aa677)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810987ee)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (ffffffff810f5f23)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (ffffffff828d6554)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/fs_struct.c (ffffffff81308591)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff81325625)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff814e0d88)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814e209e)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff814e40e0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81741316)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8179c267)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff818f210c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81914734)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (ffffffff81957d67)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81976b15)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff819bdc25)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff82918cc6)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (ffffffff81a777f6)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff828ad6d1)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff8109eda9)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (ffffffff81101cb3)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (ffffffff828de9e3)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/fs_struct.c (ffffffff8131b631)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff813383b5)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff814fa1b8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814fb45e)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff814fd4a0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff81511fac)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81767a70)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817bfd17)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8192405c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81946da4)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (ffffffff8198e207)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff819ad4a5)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff819f4835)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff82922b35)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (ffffffff81aaebe6)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff82cd2b38)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810a63d5)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/sched/psi.c (ffffffff8110c543)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (ffffffff82cfb90f)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:71
Inline: True
```
```
In fs/fs_struct.c (ffffffff813552f1)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff813721f5)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/badblocks.c (ffffffff8155c900)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff81572f68)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/flex_proportions.c (ffffffff815e8936)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81828450)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In net/core/gen_estimator.c (ffffffff819f7c0c)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81a17021)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/sched/sch_generic.c (ffffffff81a65e91)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81a97245)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81ae2545)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff82d2f11f)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
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
In arch/x86/kernel/tsc.c (ffffffff82fbe97f)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810a1cf2)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
```
```
In kernel/sched/psi.c (ffffffff81109743)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In kernel/time/hrtimer.c (ffffffff81143ec8)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In mm/page_alloc.c (ffffffff82fe83c1)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:72
Inline: True
```
```
In fs/fs_struct.c (ffffffff81361c11)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff81380045)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/badblocks.c (ffffffff81578a50)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff8158f8db)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/flex_proportions.c (ffffffff8160d9e6)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81838ea0)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In net/core/gen_estimator.c (ffffffff819f767c)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81a17311)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/sched/sch_generic.c (ffffffff81a6df8d)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81aa1205)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81aef3e5)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff8301dd11)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
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
In arch/x86/kernel/tsc.c (ffffffff831c8f59)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810a2b47)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
```
```
In kernel/sched/psi.c (ffffffff8110b593)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In kernel/time/hrtimer.c (ffffffff81145058)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In mm/page_alloc.c (ffffffff831f3138)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:72
Inline: True
```
```
In fs/fs_struct.c (ffffffff813686f1)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff81386cf5)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/badblocks.c (ffffffff815807a0)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff81596861)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/flex_proportions.c (ffffffff815f1126)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c160)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In net/core/gen_estimator.c (ffffffff819dd7fc)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff819fdfee)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/sched/sch_generic.c (ffffffff81a567fd)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c265)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81adab35)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0a758)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:72
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
In arch/x86/kernel/tsc.c (ffffffff832aa1ac)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810b426c)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
```
```
In kernel/sched/psi.c (ffffffff81129f3f)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In kernel/time/hrtimer.c (ffffffff811688bc)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In mm/page_alloc.c (ffffffff81d4ee5a)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:72
Inline: True
```
```
In fs/fs_struct.c (ffffffff813b73f1)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff813d3e15)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/badblocks.c (ffffffff815e5ac0)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff815fde77)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/flex_proportions.c (ffffffff8165e286)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a65f0)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In net/core/gen_estimator.c (ffffffff81a8dadc)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81ab00f1)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/sched/sch_generic.c (ffffffff81b0f612)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81b47235)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81b99e25)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd233d)
Location: include/linux/seqlock.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:72
Inline: True
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
In arch/x86/kernel/tsc.c (ffffffff8345998f)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810ca5dc)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
```
```
In kernel/sched/build_utility.c (ffffffff8113d961)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:group_init
```
```
In kernel/time/hrtimer.c (ffffffff8119c40c)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In mm/page_alloc.c (ffffffff81f1ed1b)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:71
Inline: True
```
```
In fs/fs_struct.c (ffffffff8143caad)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff8145d815)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/badblocks.c (ffffffff81694cb0)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff816ae580)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/flex_proportions.c (ffffffff817779a6)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
```
```
In net/core/gen_estimator.c (ffffffff81c035f6)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81c29037)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81cd4355)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81d2be15)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d693e9)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:71
Inline: True
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
In arch/x86/kernel/tsc.c (ffffffff83e7936c)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810e7c45)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
```
```
In kernel/sched/build_utility.c (ffffffff8116d122)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:group_init
```
```
In kernel/time/hrtimer.c (ffffffff811dadcc)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In mm/page_alloc.c (ffffffff83ebe436)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:71
Inline: True
```
```
In fs/fs_struct.c (ffffffff814cb1fd)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff814ed345)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/badblocks.c (ffffffff81753cd0)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff8176d279)
Location: include/linux/seqlock.h:71
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81db2be6)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81ddbd57)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81e945d5)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81ef39d5)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f346c9)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:71
Inline: True
```
```
In lib/flex_proportions.c (ffffffff82020626)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff8369ba92)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810f3866)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
```
```
In kernel/sched/build_utility.c (ffffffff8117dad2)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:group_init
```
```
In kernel/time/hrtimer.c (ffffffff811ef2e7)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In mm/mm_init.c (ffffffff836e1266)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:71
Inline: True
```
```
In fs/fs_struct.c (ffffffff8150143d)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff81524015)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/badblocks.c (ffffffff8178fe80)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff817acd73)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In net/core/gen_estimator.c (ffffffff81e231b6)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81e4caa7)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81ef2da5)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81f53485)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f942e9)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:71
Inline: True
```
```
In lib/flex_proportions.c (ffffffff820a0666)
Location: include/linux/seqlock.h:71
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff838cb872)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810fcc37)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
```
```
In kernel/sched/build_utility.c (ffffffff8118b822)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:group_init
```
```
In kernel/time/hrtimer.c (ffffffff81205467)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In mm/mm_init.c (ffffffff83913b66)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:41
Inline: True
```
```
In fs/fs_struct.c (ffffffff8153608d)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff815585a5)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/badblocks.c (ffffffff817d23d4)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff817f0b72)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb4a90)
Location: include/linux/seqlock.h:41
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81ee1126)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81f0b7bc)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81fb6d35)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff8201984c)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff820616d3)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:41
Inline: True
```
```
In lib/flex_proportions.c (ffffffff8217863b)
Location: include/linux/seqlock.h:41
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In virt/kvm/eventfd.c (ffff8000100c1164)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
```
In kernel/fork.c (ffff8000100f38c0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (ffff8000101668ac)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (ffff8000114576f0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/fs_struct.c (ffff8000103d2bdc)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffff8000103f6b28)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffff8000105fbcfc)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffff8000105fd474)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffff8000105fe6b8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffff800010615698)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/dma-buf/dma-resv.c (ffff800010968cd0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/net/phy/fixed_phy.c (ffff8000109da230)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffff800010bbf8b8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffff800010be7f44)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (ffff800010c399f8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffff800010c5d670)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffff800010caa764)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffff8000114b3964)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (ffff800010d882d4)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In kernel/fork.c (c035205c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (c03b2d90)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In kernel/cgroup/rstat.c (c041c4dc)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_init
```
```
In kernel/bpf/core.c (c0490fd0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc
```
```
In fs/dcache.c (c058af24)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (c058c988)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
```
```
In fs/fs_struct.c (c05ad720)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (c05cb21c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (c07a6dc0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (c07a83a0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (c07aa28c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (c07bfea0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/dma-buf/dma-resv.c (c0a3ee0c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/net/loopback.c (c0ab82fc)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_dev_init
```
```
In drivers/net/phy/fixed_phy.c (c0ac0e08)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In drivers/net/tun.c (c0ac3dc8)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/sock.c (c0cc8044)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
```
```
In net/core/gen_estimator.c (c0cdb368)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (c0d012d8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/drop_monitor.c (c15b66e4)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
```
```
In net/core/devlink.c (c0d43364)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
```
```
In net/sched/sch_generic.c (c0d4be64)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/act_api.c (c0d57fa0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (c0d6cbc8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (c0db6e90)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
```
```
In net/xfrm/xfrm_policy.c (c15b8c44)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/af_inet6.c (c0dfc878)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/ipv6/addrconf.c (c0e0a99c)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In lib/flex_proportions.c (c0e830a0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In kernel/fork.c (c00000000013969c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (c0000000001be46c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (c000000000eec450)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In fs/dcache.c (c0000000004a4c30)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/fs_struct.c (c0000000004d57d4)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (c0000000004feb88)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (c0000000007950b8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (c000000000796d3c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (c000000000798f8c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (c0000000007b4e18)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/dma-buf/dma-resv.c (c000000000a20a40)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/net/phy/fixed_phy.c (c000000000a9c144)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (c000000000c98c7c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (c000000000cca54c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (c000000000d3284c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (c000000000d5fc30)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (c000000000dc0894)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (c0000000013c5040)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (c000000000ec8854)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In kernel/fork.c (ffffffe0000c001a)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (ffffffe000108946)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In fs/dcache.c (ffffffe00026fc8e)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/fs_struct.c (ffffffe00028de08)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffe0002a6dfa)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffe000437d72)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffe000439092)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffe00043a600)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffe00044c804)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d4882)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffe00062505a)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffe00074d26c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffe00076c6ae)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (ffffffe0007aad8a)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffe0007c60a8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffe0008054f2)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffe00004272c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (ffffffe0008b2374)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff8289b6f0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810986c9)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (ffffffff810fafc3)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (ffffffff828c7897)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/fs_struct.c (ffffffff81313c11)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff81330995)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff814f2798)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814f3a3e)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff814f5a80)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff8150a58c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c160)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817847e7)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff818c405c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff818e6d74)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (ffffffff8192e077)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff8194d315)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff819945d5)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff82907839)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (ffffffff81a4da36)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff8289398d)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff81087039)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (ffffffff810eb1e3)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (ffffffff828bffbc)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/fs_struct.c (ffffffff81304821)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff81321585)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff814e2cc8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814e3f4e)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff814e5f90)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff814faa1c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f55c0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81764137)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8187df9c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff818a0bb4)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (ffffffff818e7b77)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81906e05)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff8194e095)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff828ffb87)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (ffffffff81a0ab46)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff828ae6b3)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff81098679)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (ffffffff810f8183)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (ffffffff828da617)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/fs_struct.c (ffffffff81311a01)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff8132e465)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff814ee828)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff814eface)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff814f1b10)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff8150661c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175af30)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817b4b97)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8191505c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81937da4)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (ffffffff8197f207)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a08ed)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start
```
```
In net/ipv4/inetpeer.c (ffffffff819b7ae5)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff819fee75)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff8291d133)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (ffffffff81ab9e26)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
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
In arch/x86/kernel/tsc.c (ffffffff828ae6e1)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
```
```
In kernel/fork.c (ffffffff810a02a0)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/sched/psi.c (ffffffff811032c3)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - kernel/sched/psi.c:group_init
```
```
In mm/page_alloc.c (ffffffff828dfa38)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In fs/fs_struct.c (ffffffff81323241)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/fs_struct.c:copy_fs_struct
```
```
In fs/userfaultfd.c (ffffffff81340e95)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
```
```
In block/genhd.c (ffffffff815078c8)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffff81508b5e)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/badblocks.c (ffffffff8150ac20)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/blk-iocost.c (ffffffff8151f90c)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81776510)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817ceb67)
Location: include/linux/seqlock.h:55
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff819361dc)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/neighbour.c (ffffffff81959584)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
```
```
In net/sched/sch_generic.c (ffffffff819a1767)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff819c1355)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_peer_base_init
```
```
In net/ipv4/af_inet.c (ffffffff81a08f45)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
```
```
In net/xfrm/xfrm_policy.c (ffffffff82923b97)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In lib/flex_proportions.c (ffffffff81ac6276)
Location: include/linux/seqlock.h:55
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_global_init
```
</details>
</li>
</ul>

## Differences
