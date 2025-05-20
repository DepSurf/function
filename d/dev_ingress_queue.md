# Function: <code>dev_ingress_queue</code>

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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:75
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:75
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:75
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:75
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:75
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:75
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:75
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:75
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:75
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:76
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:76
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:76
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:79
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:79
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:79
Inline: True
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:81
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:81
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:81
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/rtnetlink.h:83
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/rtnetlink.h:83
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/rtnetlink.h:83
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
In net/core/dev.c (ffffffff81a0e6e5)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (ffffffff81a66978)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_api.c (ffffffff81a67e58)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
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
In net/core/dev.c (ffffffff81a0f4c5)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (ffffffff81a6ea58)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_api.c (ffffffff81a7055b)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
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
In net/core/dev.c (ffffffff819f6335)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (ffffffff81a572e8)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_api.c (ffffffff81a58e5a)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
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
In net/core/dev.c (ffffffff81aa7d75)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (ffffffff81b10148)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_api.c (ffffffff81b11e9a)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
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
In net/core/dev.c (ffffffff81c1fc65)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (ffffffff81c97308)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
```
```
In net/sched/sch_api.c (ffffffff81c99182)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
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
In net/core/dev.c (ffffffff81dd09d5)
Location: include/linux/rtnetlink.h:84
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (ffffffff81e53138)
Location: include/linux/rtnetlink.h:84
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
```
```
In net/sched/sch_api.c (ffffffff81e55072)
Location: include/linux/rtnetlink.h:84
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
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
In net/core/dev.c (ffffffff81e415d5)
Location: include/linux/rtnetlink.h:75
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (ffffffff81eae9b7)
Location: include/linux/rtnetlink.h:75
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
```
```
In net/sched/sch_api.c (ffffffff81eb0922)
Location: include/linux/rtnetlink.h:75
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
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
In net/core/dev.c (ffffffff81efff55)
Location: include/linux/rtnetlink.h:94
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (ffffffff81f71454)
Location: include/linux/rtnetlink.h:94
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_activate
```
```
In net/sched/sch_api.c (ffffffff81f73392)
Location: include/linux/rtnetlink.h:94
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/rtnetlink.h:83
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
In net/core/dev.c (c0cf2c54)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (c0d4c77c)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_api.c (c0d4e160)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (c0d51708)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dev_block
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
In net/core/dev.c (c000000000cb7c88)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (c000000000d336e0)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_api.c (c000000000d3674c)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (c000000000d3a3a0)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dev_block
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
In net/core/dev.c (ffffffe0007610ec)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/core/dev.c:dev_ingress_queue_create
```
```
In net/sched/sch_generic.c (ffffffe0007ab69c)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_shutdown
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_api.c (ffffffe0007ad316)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffe0007af660)
Location: include/linux/rtnetlink.h:83
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dev_block
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/rtnetlink.h:83
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/rtnetlink.h:83
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/rtnetlink.h:83
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
In net/core/dev.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/linux/rtnetlink.h:83
Inline: True
```
</details>
</li>
</ul>

## Differences
