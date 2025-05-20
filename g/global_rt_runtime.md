# Function: <code>global_rt_runtime</code>

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
In kernel/sched/core.c (ffffffff81f7e08c)
Location: kernel/sched/sched.h:1017
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810c2f1f)
Location: kernel/sched/sched.h:1017
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff810b3436)
Location: kernel/sched/sched.h:1055
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/deadline.c (ffffffff810c68af)
Location: kernel/sched/sched.h:1055
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff810b9a86)
Location: kernel/sched/sched.h:1089
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/deadline.c (ffffffff810cc89f)
Location: kernel/sched/sched.h:1089
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff820c3447)
Location: kernel/sched/sched.h:1257
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810c5093)
Location: kernel/sched/sched.h:1257
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810c8bdc)
Location: kernel/sched/sched.h:1257
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff826cb4d8)
Location: kernel/sched/sched.h:1294
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810cc7b8)
Location: kernel/sched/sched.h:1294
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810d02fc)
Location: kernel/sched/sched.h:1294
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff826f561d)
Location: kernel/sched/sched.h:1383
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810d46d8)
Location: kernel/sched/sched.h:1383
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810d8831)
Location: kernel/sched/sched.h:1383
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff828ac462)
Location: kernel/sched/sched.h:1537
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810de108)
Location: kernel/sched/sched.h:1537
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810e2331)
Location: kernel/sched/sched.h:1537
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff828c4d37)
Location: kernel/sched/sched.h:1595
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810e5147)
Location: kernel/sched/sched.h:1595
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810e8e31)
Location: kernel/sched/sched.h:1595
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff828cd325)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810f05e9)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffffffff810f4911)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff82cee799)
Location: kernel/sched/sched.h:1649
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810f9b02)
Location: kernel/sched/sched.h:1649
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810fe021)
Location: kernel/sched/sched.h:1649
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff82fdae97)
Location: kernel/sched/sched.h:1714
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810f7ee2)
Location: kernel/sched/sched.h:1714
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810fc6a3)
Location: kernel/sched/sched.h:1714
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff831e5995)
Location: kernel/sched/sched.h:1725
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810fa049)
Location: kernel/sched/sched.h:1725
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810fe9f3)
Location: kernel/sched/sched.h:1725
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff832c99b7)
Location: kernel/sched/sched.h:2013
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff81114e16)
Location: kernel/sched/sched.h:2013
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff8111a3b3)
Location: kernel/sched/sched.h:2013
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff8347cc4b)
Location: kernel/sched/sched.h:2008
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/build_policy.c (ffffffff8113a12f)
Location: kernel/sched/sched.h:2008
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:sched_rt_handler
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
In kernel/sched/core.c (ffffffff83ea8077)
Location: kernel/sched/sched.h:2058
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/build_policy.c (ffffffff811649bf)
Location: kernel/sched/sched.h:2058
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:sched_rt_handler
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
In kernel/sched/core.c (ffffffff836cc947)
Location: kernel/sched/sched.h:2101
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/build_policy.c (ffffffff8117515f)
Location: kernel/sched/sched.h:2101
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
  - kernel/sched/build_policy.c:init_dl_bw
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:sched_rt_handler
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
In kernel/sched/core.c (ffffffff838fdd47)
Location: kernel/sched/sched.h:2143
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/build_policy.c (ffffffff8118346f)
Location: kernel/sched/sched.h:2143
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
  - kernel/sched/build_policy.c:init_dl_bw
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:sched_rt_handler
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
In kernel/sched/core.c (ffff800011444b90)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffff800010151ce8)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffff800010156f40)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (c151ec50)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (c039ef94)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (c03a4b3c)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (c0000000013693e0)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (c0000000001a5680)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (c0000000001aba38)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffe000006a58)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffe0000f9eb0)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffffffe0000fde70)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff828b6101)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810e9a37)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810edd11)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff828ae2a3)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810d99a9)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffffffff810ddda1)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff828c9017)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810e6b19)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffffffff810eae41)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff828ce357)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810f1aa5)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810f5e11)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
</details>
</li>
</ul>

## Differences
