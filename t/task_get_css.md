# Function: <code>task_get_css</code>

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
In kernel/cpuset.c (ffffffff8111d96c)
Location: include/linux/cgroup.h:444
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8119a5e9)
Location: include/linux/cgroup.h:444
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff8123ab28)
Location: include/linux/cgroup.h:444
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813b0fa1)
Location: include/linux/cgroup.h:444
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
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
In kernel/cpuset.c (ffffffff8112583c)
Location: include/linux/cgroup.h:448
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff811aeef9)
Location: include/linux/cgroup.h:448
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff812629c8)
Location: include/linux/cgroup.h:448
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813f4991)
Location: include/linux/cgroup.h:448
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
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
In kernel/cpuset.c (ffffffff8112f228)
Location: include/linux/cgroup.h:448
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff811bf5a9)
Location: include/linux/cgroup.h:448
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81275e18)
Location: include/linux/cgroup.h:448
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8140e381)
Location: include/linux/cgroup.h:448
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
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
In kernel/cgroup/rdma.c (ffffffff8112bebe)
Location: include/linux/cgroup.h:468
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811308a8)
Location: include/linux/cgroup.h:468
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff811c72e9)
Location: include/linux/cgroup.h:468
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81283297)
Location: include/linux/cgroup.h:468
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8141bf72)
Location: include/linux/cgroup.h:468
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
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
In kernel/cgroup/rdma.c (ffffffff81138cce)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d7e8)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff811dc0f9)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff812a5e07)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff81147918)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff811fdb22)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff812cc9bb)
Location: include/linux/cgroup.h:490
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff811531d8)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8121063e)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff812e1cdb)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff8115fb22)
Location: include/linux/cgroup.h:499
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81165448)
Location: include/linux/cgroup.h:499
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8121fc97)
Location: include/linux/cgroup.h:499
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81300298)
Location: include/linux/cgroup.h:499
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff8116b782)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81171338)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8122d747)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff813122d4)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff8117d3b2)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81183048)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8125b16f)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81349dec)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff8117a212)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8117ffca)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81265394)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81356ce9)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff8117ad92)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180a9a)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812695a3)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff8135f50b)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff811a2852)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a888a)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812a601d)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff813abe25)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff811d32c2)
Location: include/linux/cgroup.h:508
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9a38)
Location: include/linux/cgroup.h:508
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff812fed0c)
Location: include/linux/cgroup.h:508
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81431fc8)
Location: include/linux/cgroup.h:508
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff81217242)
Location: include/linux/cgroup.h:450
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ef08)
Location: include/linux/cgroup.h:450
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81369489)
Location: include/linux/cgroup.h:450
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In fs/fs-writeback.c (ffffffff814c0018)
Location: include/linux/cgroup.h:450
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff8122cb62)
Location: include/linux/cgroup.h:449
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81235038)
Location: include/linux/cgroup.h:449
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8139b629)
Location: include/linux/cgroup.h:449
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In fs/fs-writeback.c (ffffffff814f6478)
Location: include/linux/cgroup.h:449
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff81244c22)
Location: include/linux/cgroup.h:447
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ec87)
Location: include/linux/cgroup.h:447
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff813c5599)
Location: include/linux/cgroup.h:447
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In fs/fs-writeback.c (ffffffff8152abb8)
Location: include/linux/cgroup.h:447
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffff8000101dfad4)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffff8000101e49cc)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffff8000102bc628)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffff8000103c85c0)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (c0421414)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c04257d4)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (c04e8cc8)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (c05a4e8c)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (c00000000024e1dc)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c0000000002551ec)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (c0000000003748dc)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (c0000000004c9a28)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffe000156ad0)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffe00015abc2)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffe0001df2e8)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffe000284b86)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff81163da2)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81169958)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81225d97)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff8130a8b4)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff81156ff2)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cb58)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81218f37)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff812fb4d4)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff81161b72)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81167728)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81223b37)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff813086a4)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In kernel/cgroup/rdma.c (ffffffff8116efd2)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81174db8)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff81232c5c)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81318097)
Location: include/linux/cgroup.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
</ul>

## Differences
