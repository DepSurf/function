# Function: <code>css_get</code>

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
In kernel/cgroup.c (ffffffff811145e4)
Location: include/linux/cgroup.h:293
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cpuset.c (ffffffff8111c52f)
Location: include/linux/cgroup.h:293
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/backing-dev.c (ffffffff811af140)
Location: include/linux/cgroup.h:293
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff811fb394)
Location: include/linux/cgroup.h:293
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:__memcg_kmem_get_cache
```
```
In block/bio.c (ffffffff813b10c5)
Location: include/linux/cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkcg
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
In kernel/cgroup.c (ffffffff8111bf92)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cpuset.c (ffffffff8112442f)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/backing-dev.c (ffffffff811c8563)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff8121ec91)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/bio.c (ffffffff813f4a95)
Location: include/linux/cgroup.h:292
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
In kernel/cgroup.c (ffffffff811242d2)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cpuset.c (ffffffff8112d5c0)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/backing-dev.c (ffffffff811d8693)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff81236775)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/bio.c (ffffffff8140e485)
Location: include/linux/cgroup.h:292
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
In kernel/cgroup/cgroup.c (ffffffff81128aa7)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8112ebff)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/backing-dev.c (ffffffff811e1c22)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff811e77c4)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/memcontrol.c (ffffffff81242228)
Location: include/linux/cgroup.h:292
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/bio.c (ffffffff8141b205)
Location: include/linux/cgroup.h:292
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
In kernel/kthread.c (ffffffff810ac948)
Location: include/linux/cgroup.h:304
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81135116)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8113ba9f)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/backing-dev.c (ffffffff811f7cbb)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff811fda04)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/memcontrol.c (ffffffff8126201c)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/bio.c (ffffffff81445e2c)
Location: include/linux/cgroup.h:304
Inline: True
```
```
In drivers/block/loop.c (ffffffff8166fc89)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810b395d)
Location: include/linux/cgroup.h:304
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114384d)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8114a352)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/backing-dev.c (ffffffff81218ffb)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8121ed3f)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/memcontrol.c (ffffffff8128601c)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/bio.c (ffffffff81479aa9)
Location: include/linux/cgroup.h:304
Inline: True
```
```
In drivers/block/loop.c (ffffffff816ab97a)
Location: include/linux/cgroup.h:304
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810bcc5d)
Location: include/linux/cgroup.h:306
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f36d)
Location: include/linux/cgroup.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81156d29)
Location: include/linux/cgroup.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/backing-dev.c (ffffffff8122bf39)
Location: include/linux/cgroup.h:306
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81231d1f)
Location: include/linux/cgroup.h:306
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/memcontrol.c (ffffffff8129af7c)
Location: include/linux/cgroup.h:306
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In drivers/block/loop.c (ffffffff816cc71b)
Location: include/linux/cgroup.h:306
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810c2a49)
Location: include/linux/cgroup.h:313
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b1c0)
Location: include/linux/cgroup.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81164669)
Location: include/linux/cgroup.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/cgroup.c (ffffffff811f8c95)
Location: include/linux/cgroup.h:313
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8123bbd9)
Location: include/linux/cgroup.h:313
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff812419a0)
Location: include/linux/cgroup.h:313
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b624c)
Location: include/linux/cgroup.h:313
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffffffff817081b0)
Location: include/linux/cgroup.h:313
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810c8fb8)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81166e7e)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff811704a9)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff81205cc5)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8124a090)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8124fe40)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c1e3d)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffffffff8172c400)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810d09a8)
Location: include/linux/cgroup.h:321
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811785da)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff811817f9)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/cgroup.c (ffffffff8122d445)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81278254)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/slab_common.c (ffffffff8127e46c)
Location: include/linux/cgroup.h:321
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c5751)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/hugetlb.c:region_del
```
```
In mm/memcontrol.c (ffffffff812f61f5)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffffffff817e7bc0)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810cb588)
Location: include/linux/cgroup.h:321
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8117536e)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e6f9)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/cgroup.c (ffffffff81235955)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff812829e5)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff812d13b9)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/hugetlb.c:region_del
```
```
In mm/memcontrol.c (ffffffff81309d19)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_reparent_objcgs
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In drivers/block/loop.c (ffffffff817fcaa0)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810ccec9)
Location: include/linux/cgroup.h:321
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81175eee)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e708)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff81239ba5)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81287b0a)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff812d7889)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/hugetlb.c:region_del
```
```
In mm/memcontrol.c (ffffffff81310579)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffffffff817e1670)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810df918)
Location: include/linux/cgroup.h:321
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d4cd)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff811a6428)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff81274315)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff812c72ac)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff8131c931)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/memcontrol.c (ffffffff8135b898)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In drivers/block/loop.c (ffffffff8186fd6c)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In kernel/kthread.c (ffffffff810f9c7b)
Location: include/linux/cgroup.h:321
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd7ed)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff811d7858)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff812c49b5)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81323af5)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff81388b71)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/memcontrol.c (ffffffff813d50c9)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In drivers/block/loop.c (ffffffff819b6725)
Location: include/linux/cgroup.h:321
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In kernel/kthread.c (ffffffff8111c9bb)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81210e8d)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8121c52a)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/helpers.c (ffffffff812f44a1)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/cgroup_iter.c (ffffffff813254fb)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff81329e85)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81398363)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff81406bfa)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/memcontrol.c (ffffffff8145ab32)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In drivers/block/loop.c (ffffffff81b2b935)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In kernel/kthread.c (ffffffff81129b4b)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8122687d)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8123291a)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8135573b)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff81359fc5)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff813cb2e3)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff8143a25d)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/memcontrol.c (ffffffff81490792)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In drivers/block/loop.c (ffffffff81b7bc45)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In kernel/kthread.c (ffffffff8113418b)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e50d)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8124c09a)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e0bb)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff81382b75)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff813f5aea)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff8147486d)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/memcontrol.c (ffffffff814c006f)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In drivers/block/loop.c (ffffffff81bcfc74)
Location: include/linux/cgroup_refcnt.h:8
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In kernel/kthread.c (ffff80001012887c)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8d10)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffff8000101e333c)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffff80001028ef28)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffff8000102df7d4)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffff8000102e6d98)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In mm/memcontrol.c (ffff800010366314)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffff800010924f0c)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (c037acc8)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/cgroup/cgroup.c (c041ba94)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (c04240ec)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/cgroup.c (c04be780)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (c05045f0)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (c050af94)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In mm/memcontrol.c (c055697c)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (c0a07ce4)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (c0000000001734a4)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In kernel/cgroup/cgroup.c (c000000000246128)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (c000000000253d44)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (c00000000033bad0)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (c00000000039f328)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (c0000000003a8820)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In mm/memcontrol.c (c000000000450b0c)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (c0000000009c7924)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffe0000df528)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffe000151c98)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffe000158fa4)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/cgroup.c (ffffffe0001c20ba)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffe0001f74bc)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffe0001fcaee)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In mm/memcontrol.c (ffffffe0002430cc)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffffffe0005a1070)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810c3338)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f49e)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81168ac9)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff811fe2e5)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff812426e0)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81248490)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ba41d)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffffffff816f21e0)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810b1b78)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115272e)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8115bcd9)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff811f1035)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff812356b0)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8123b440)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ab5dd)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffffffff816cc2e0)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810c2888)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d26e)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81166899)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff811fc0b5)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81240480)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81246230)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b822d)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffffffff8171f8c0)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/kthread.c (ffffffff810cae78)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a3f1)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81173ef9)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff8120acd5)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8124fb7b)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81255a1c)
Location: include/linux/cgroup.h:315
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c8b5d)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In drivers/block/loop.c (ffffffff8173ad00)
Location: include/linux/cgroup.h:315
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
</details>
</li>
</ul>

## Differences
