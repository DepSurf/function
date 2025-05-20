# Function: <code>queue_rcu_work</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a9ed0)
Location: kernel/workqueue.c:1625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810a9ed0-ffffffff810a9f00: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b2fa0)
Location: kernel/workqueue.c:1645
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810b2fa0-ffffffff810b2fd0: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8b90)
Location: kernel/workqueue.c:1741
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810b8b90-ffffffff810b8bbf: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bf0b0)
Location: kernel/workqueue.c:1744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810bf0b0-ffffffff810bf0df: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c62b0)
Location: kernel/workqueue.c:1741
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - fs/aio.c:free_ioctx_reqs
  - block/partitions/core.c:hd_struct_free
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810c62b0-ffffffff810c62df: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1310)
Location: kernel/workqueue.c:1747
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - fs/aio.c:free_ioctx_reqs
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810c1310-ffffffff810c133f: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2cf0)
Location: kernel/workqueue.c:1748
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - fs/aio.c:free_ioctx_reqs
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - net/core/skmsg.c:sk_psock_drop
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810c2cf0-ffffffff810c2d1f: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d5830)
Location: kernel/workqueue.c:1778
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/aio.c:free_ioctx_reqs
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - net/core/skmsg.c:sk_psock_drop
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810d5830-ffffffff810d585f: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810eebc0)
Location: kernel/workqueue.c:1768
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/aio.c:free_ioctx_reqs
  - drivers/acpi/osl.c:acpi_os_unmap_generic_address
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - net/core/skmsg.c:sk_psock_drop
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810eebc0-ffffffff810eebff: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8110feb0)
Location: kernel/workqueue.c:1768
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/aio.c:free_ioctx_reqs
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - net/core/skmsg.c:sk_psock_drop
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff8110feb0-ffffffff8110feef: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111c4b0)
Location: kernel/workqueue.c:1970
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/aio.c:free_ioctx_reqs
  - drivers/acpi/osl.c:acpi_os_unmap_generic_address
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - net/core/skmsg.c:sk_psock_drop
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff8111c4b0-ffffffff8111c4ef: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81126c20)
Location: kernel/workqueue.c:2056
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/aio.c:free_ioctx_reqs
  - drivers/acpi/osl.c:acpi_os_unmap_generic_address
  - drivers/acpi/osl.c:acpi_os_unmap_iomem
  - drivers/xen/events/events_base.c:xen_free_irq
  - net/core/skmsg.c:sk_psock_drop
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff81126c20-ffffffff81126c5f: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011cb80)
Location: kernel/workqueue.c:1744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffff80001011cb80-ffff80001011cc18: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0370f3c)
Location: kernel/workqueue.c:1744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
c0370f3c-c0370f8c: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000163d70)
Location: kernel/workqueue.c:1744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
c000000000163d70-c000000000163df0: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d6040)
Location: kernel/workqueue.c:1744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffe0000d6040-ffffffe0000d6098: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9420)
Location: kernel/workqueue.c:1744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810b9420-ffffffff810b944f: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7d60)
Location: kernel/workqueue.c:1744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810a7d60-ffffffff810a7d8f: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8980)
Location: kernel/workqueue.c:1744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810b8980-ffffffff810b89af: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct *wq, struct rcu_work *rwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1100)
Location: kernel/workqueue.c:1744
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - fs/aio.c:free_ioctx_reqs
  - block/partition-generic.c:__delete_partition
  - net/sched/cls_api.c:tcf_queue_work
```
**Symbols:**

```
ffffffff810c1100-ffffffff810c112f: queue_rcu_work (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
