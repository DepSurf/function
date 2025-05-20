# Function: <code>to_rcu_work</code>

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
In kernel/cgroup/cgroup.c (ffffffff81142175)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff812f2cc5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
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
In kernel/cgroup/cgroup.c (ffffffff8114dbf5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff81307a35)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (ffffffff814b37d5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff811599a5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff81329515)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (ffffffff814e1d55)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff81165625)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff8133c1c5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (ffffffff814fb115)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/rcu/tree.c (ffffffff81133965)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/cgroup/cgroup.c (ffffffff811768e5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff81377695)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partitions/core.c (ffffffff8155d055)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partitions/core.c:hd_struct_free_work
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
In kernel/rcu/tree.c (ffffffff8112f83c)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/cgroup/cgroup.c (ffffffff811735c5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff81384ff5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In drivers/acpi/osl.c (ffffffff8169e135)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_remove
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
In kernel/rcu/tree.c (ffffffff8112fbcc)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/cgroup/cgroup.c (ffffffff811741a5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff8138bda5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In drivers/acpi/osl.c (ffffffff81680e75)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_remove
```
```
In net/core/skmsg.c (ffffffff81a4d6e5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
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
In kernel/rcu/tree.c (ffffffff8115155c)
Location: include/linux/workqueue.h:158
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/cgroup/cgroup.c (ffffffff8119b235)
Location: include/linux/workqueue.h:158
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/fs-writeback.c (ffffffff813ae555)
Location: include/linux/workqueue.h:158
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/aio.c (ffffffff813d9355)
Location: include/linux/workqueue.h:158
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In drivers/acpi/osl.c (ffffffff816f5fc5)
Location: include/linux/workqueue.h:158
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_remove
```
```
In net/core/skmsg.c (ffffffff81b05da5)
Location: include/linux/workqueue.h:158
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
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
In kernel/rcu/tree.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/workqueue.h:158
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
In kernel/rcu/tree.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/workqueue.h:158
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/workqueue.h:158
Inline: True
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
In kernel/rcu/tree.c (0)
Location: include/linux/workqueue.h:159
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/workqueue.h:159
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/workqueue.h:159
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/workqueue.h:159
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/workqueue.h:159
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/workqueue.h:159
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/workqueue.h:159
Inline: True
```
```
In net/devlink/core.c (0)
Location: include/linux/workqueue.h:159
Inline: True
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
In kernel/rcu/tree.c (0)
Location: include/linux/workqueue.h:197
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/workqueue.h:197
Inline: True
```
```
In kernel/trace/trace_events_user.c (0)
Location: include/linux/workqueue.h:197
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/workqueue.h:197
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/workqueue.h:197
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/workqueue.h:197
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/workqueue.h:197
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/linux/workqueue.h:197
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/workqueue.h:197
Inline: True
```
```
In net/devlink/core.c (0)
Location: include/linux/workqueue.h:197
Inline: True
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
In kernel/cgroup/cgroup.c (ffff8000101d710c)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffff8000103fb04c)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (ffff8000105fcfd4)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/cgroup/cgroup.c (c0419d78)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (c05cf6ac)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (c07a7954)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/cgroup/cgroup.c (c000000000243698)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (c0000000005042b4)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (c00000000079682c)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/cgroup/cgroup.c (ffffffe0001501fc)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffe0002aa952)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (ffffffe000438d48)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff8115dc45)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff813347a5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (ffffffff814f36f5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff81150f25)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff81325135)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (ffffffff814e3c05)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff8115ba15)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff81332275)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (ffffffff814ef785)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff81168ad5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In fs/aio.c (ffffffff813447c5)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx
```
```
In block/partition-generic.c (ffffffff81508815)
Location: include/linux/workqueue.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:delete_partition_work_fn
```
</details>
</li>
</ul>

## Differences
