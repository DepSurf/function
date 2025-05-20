# Function: <code>pr_cont_cgroup_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811ff07c)
Location: include/linux/cgroup.h:531
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In kernel/cgroup_pids.c (ffffffff8112238e)
Location: include/linux/cgroup.h:552
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff81222e2e)
Location: include/linux/cgroup.h:552
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In kernel/cgroup_pids.c (ffffffff8112a9a7)
Location: include/linux/cgroup.h:568
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff8123521e)
Location: include/linux/cgroup.h:568
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In kernel/cgroup/pids.c (ffffffff8112b6a0)
Location: include/linux/cgroup.h:588
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff81240d6b)
Location: include/linux/cgroup.h:588
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In kernel/cgroup/pids.c (ffffffff811384a0)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff81260aab)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In kernel/cgroup/pids.c (ffffffff81147030)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff81286e8c)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In kernel/cgroup/pids.c (ffffffff81152bb0)
Location: include/linux/cgroup.h:648
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff8129be8d)
Location: include/linux/cgroup.h:648
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (ffffffff8115f1fc)
Location: include/linux/cgroup.h:661
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff812b701a)
Location: include/linux/cgroup.h:661
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (ffffffff8116ae5c)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff812c8eef)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (ffffffff8117c98b)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff812fe540)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (ffffffff81be47cc)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff81be9d79)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In block/blk-iocost.c (ffffffff81bf3ba2)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
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
In kernel/cgroup/pids.c (ffffffff81bd65f5)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/misc.c (ffffffff81bd66cf)
Location: include/linux/cgroup.h:669
Inline: True
```
```
In mm/memcontrol.c (ffffffff81bdbd96)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In block/blk-iocost.c (ffffffff81be5a02)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
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
In kernel/cgroup/pids.c (ffffffff81cb320f)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/misc.c (ffffffff811a8fc0)
Location: include/linux/cgroup.h:669
Inline: True
```
```
In mm/memcontrol.c (ffffffff81cc2af0)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In block/blk-iocost.c (ffffffff81cd9dea)
Location: include/linux/cgroup.h:669
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
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
In kernel/cgroup/pids.c (ffffffff81e64014)
Location: include/linux/cgroup.h:670
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff81e7506d)
Location: include/linux/cgroup.h:670
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In block/blk-iocost.c (ffffffff81e8d94d)
Location: include/linux/cgroup.h:670
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
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
In kernel/cgroup/pids.c (ffffffff81216566)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff81457499)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In block/blk-iocost.c (ffffffff8176e111)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
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
In kernel/cgroup/pids.c (ffffffff8122bea6)
Location: include/linux/cgroup.h:609
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff8148ccf9)
Location: include/linux/cgroup.h:609
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In block/blk-iocost.c (ffffffff817adc8b)
Location: include/linux/cgroup.h:609
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
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
In kernel/cgroup/pids.c (ffffffff81243ed6)
Location: include/linux/cgroup.h:607
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff814bc639)
Location: include/linux/cgroup.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In block/blk-iocost.c (ffffffff817f1a9b)
Location: include/linux/cgroup.h:607
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
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
In kernel/cgroup/pids.c (ffff8000101ded54)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffff80001036c330)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (c04207d0)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (c055d408)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (c00000000024ce90)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (c00000000045c064)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (ffffffe0001560f2)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffe0002492fa)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (ffffffff8116347c)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff812c14cf)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (ffffffff811566cc)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff812b251f)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (ffffffff8116124c)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff812bf2df)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
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
In kernel/cgroup/pids.c (ffffffff8116e69c)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In mm/memcontrol.c (ffffffff812cfd3b)
Location: include/linux/cgroup.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
</details>
</li>
</ul>

## Differences
