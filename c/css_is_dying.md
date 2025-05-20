# Function: <code>css_is_dying</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112fa44)
Location: include/linux/cgroup.h:361
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8113c9a8)
Location: include/linux/cgroup.h:373
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8114b25b)
Location: include/linux/cgroup.h:373
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81157b99)
Location: include/linux/cgroup.h:375
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81164b74)
Location: include/linux/cgroup.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cpuset.c (ffffffff81170a54)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff81312cd5)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cpuset.c (ffffffff81182779)
Location: include/linux/cgroup.h:390
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff8134c5d3)
Location: include/linux/cgroup.h:390
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
In kernel/cgroup/cpuset.c (ffffffff8117f697)
Location: include/linux/cgroup.h:390
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff813595ed)
Location: include/linux/cgroup.h:390
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
In kernel/cgroup/cpuset.c (ffffffff8117fcd7)
Location: include/linux/cgroup.h:390
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff81360251)
Location: include/linux/cgroup.h:390
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
In kernel/cgroup/cpuset.c (ffffffff811a7d93)
Location: include/linux/cgroup.h:390
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff813ae8d5)
Location: include/linux/cgroup.h:390
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
In kernel/cgroup/cpuset.c (ffffffff811d8eae)
Location: include/linux/cgroup.h:390
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff814330dd)
Location: include/linux/cgroup.h:390
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cpuset.c (ffffffff8121e087)
Location: include/linux/cgroup.h:346
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff814c10cd)
Location: include/linux/cgroup.h:346
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cpuset.c (ffffffff81234187)
Location: include/linux/cgroup.h:345
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff814f637d)
Location: include/linux/cgroup.h:345
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cpuset.c (ffffffff8124dd21)
Location: include/linux/cgroup.h:344
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff8152aabd)
Location: include/linux/cgroup.h:344
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cpuset.c (ffff8000101e419c)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffff8000103c81f4)
Location: include/linux/cgroup.h:384
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
In kernel/cgroup/cpuset.c (c0425104)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (c05a2948)
Location: include/linux/cgroup.h:384
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
In kernel/cgroup/cpuset.c (c000000000254774)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (c0000000004c67e4)
Location: include/linux/cgroup.h:384
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
In kernel/cgroup/cpuset.c (ffffffe00015a4f2)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffe000286c54)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cpuset.c (ffffffff81169074)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff8130b2b5)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cpuset.c (ffffffff8115c27e)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff812fbed5)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cpuset.c (ffffffff81166e44)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff813090a5)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cpuset.c (ffffffff8117453f)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff8131adb3)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
</details>
</li>
</ul>

## Differences
