# Function: <code>plist_head_init</code>

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
In kernel/sched/rt.c (ffffffff810c108c)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/futex.c (ffffffff81f80bfe)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In drivers/base/power/qos.c (ffffffff815551db)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810c4b1c)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/futex.c (ffffffff81fa9c33)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In drivers/base/power/qos.c (ffffffff815a723b)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810cab6c)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/futex.c (ffffffff81fe5beb)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In drivers/base/power/qos.c (ffffffff815d59fb)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810c4ec2)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/futex.c (ffffffff820c64f1)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In drivers/base/power/qos.c (ffffffff815ea44b)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810cc572)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/futex.c (ffffffff826ceb71)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff826dcec4)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff81651805)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810d44ba)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/futex.c (ffffffff826f9282)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff827073f5)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff8168d0f5)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810ddeea)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/futex.c (ffffffff828b015c)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff828be7c7)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff816ad345)
Location: include/linux/plist.h:124
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810e4efa)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/futex.c (ffffffff828c8cd4)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff828d7984)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff816e6f07)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810f01f9)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/power/qos.c (ffffffff81107215)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffff828d1245)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff828dfdf5)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff8170b247)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810f984a)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff81111c15)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffff82cf2087)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff82cfd243)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff817c61d7)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810f7c0a)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff8110ece5)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffff82fdeb5c)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff82fe9c74)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff817dac77)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810f9d7a)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff8110f785)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffff831e9672)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff831f460f)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff817bf0b7)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff81114b29)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff8112f0d5)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffff832cdc73)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff832da8ca)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff81849427)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/build_policy.c (ffffffff81133a10)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff81150685)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex/core.c (ffffffff834818e5)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In mm/swapfile.c (ffffffff8348fa18)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff8198e085)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/build_policy.c (ffffffff8115de80)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff8117f015)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex/core.c (ffffffff83eaea97)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In mm/swapfile.c (ffffffff83ec21bd)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff81afe015)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/build_policy.c (ffffffff8116e560)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff8118fc65)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex/core.c (ffffffff836d3a59)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In mm/swapfile.c (ffffffff836e77ad)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff81b4c3d5)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/build_policy.c (ffffffff8117bb18)
Location: include/linux/plist.h:115
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff8119e625)
Location: include/linux/plist.h:115
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex/core.c (ffffffff83905a4c)
Location: include/linux/plist.h:115
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In mm/swapfile.c (ffffffff8391a83d)
Location: include/linux/plist.h:115
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff81ba48a3)
Location: include/linux/plist.h:115
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffff8000101514f0)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (ffff80001016e124)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffff800011449570)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffff800011458fdc)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffff8000108f9d0c)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (c039e7ec)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (c03b8ff0)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (c1523738)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (c1532f28)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (c09e4fd4)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (c0000000001a4d5c)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (c0000000001c5a34)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (c00000000136e7a0)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (c000000001382988)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (c0000000009962bc)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffe0000f97aa)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffe00010d608)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffe00000a9ea)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffe000017586)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffe0005895ac)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810e97ea)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff81100525)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffff828ba0f6)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff828c8ca9)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff816d0997)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810d95b9)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/power/qos.c (ffffffff810f0715)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffff828b2789)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff828c13ce)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff816abcb7)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810e6729)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/power/qos.c (ffffffff810fd6e5)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffff828cce79)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff828dba29)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff816fef07)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
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
In kernel/sched/rt.c (ffffffff810f184a)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/power/qos.c (ffffffff811089a5)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
```
```
In kernel/futex.c (ffffffff828d2273)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In mm/swapfile.c (ffffffff828e0e4a)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
```
```
In drivers/base/power/qos.c (ffffffff81719357)
Location: include/linux/plist.h:122
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
```
</details>
</li>
</ul>

## Differences
