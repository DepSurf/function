# Function: <code>global_rt_period</code>

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
In kernel/sched/core.c (ffffffff810b0a7c)
Location: kernel/sched/sched.h:1012
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1012
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
In kernel/sched/core.c (ffffffff810b3447)
Location: kernel/sched/sched.h:1050
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/deadline.c (ffffffff810c68ba)
Location: kernel/sched/sched.h:1050
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
In kernel/sched/core.c (ffffffff810b9a97)
Location: kernel/sched/sched.h:1084
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/deadline.c (ffffffff810cc8aa)
Location: kernel/sched/sched.h:1084
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
In kernel/sched/core.c (ffffffff820c345d)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810c5108)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810c8bd6)
Location: kernel/sched/sched.h:1252
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
In kernel/sched/core.c (ffffffff826cb4ee)
Location: kernel/sched/sched.h:1289
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810cc825)
Location: kernel/sched/sched.h:1289
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810d02f6)
Location: kernel/sched/sched.h:1289
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
In kernel/sched/core.c (ffffffff826f5633)
Location: kernel/sched/sched.h:1378
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810d4752)
Location: kernel/sched/sched.h:1378
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810d8805)
Location: kernel/sched/sched.h:1378
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
In kernel/sched/core.c (ffffffff828ac478)
Location: kernel/sched/sched.h:1532
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810de182)
Location: kernel/sched/sched.h:1532
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810e2305)
Location: kernel/sched/sched.h:1532
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
In kernel/sched/core.c (ffffffff828c4d4d)
Location: kernel/sched/sched.h:1590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810e51b6)
Location: kernel/sched/sched.h:1590
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810e8e05)
Location: kernel/sched/sched.h:1590
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
In kernel/sched/core.c (ffffffff828cd33b)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810f0602)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffffffff810f48e5)
Location: kernel/sched/sched.h:1604
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
In kernel/sched/core.c (ffffffff82cee7af)
Location: kernel/sched/sched.h:1644
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810f9b3f)
Location: kernel/sched/sched.h:1644
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810fdff5)
Location: kernel/sched/sched.h:1644
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
In kernel/sched/core.c (ffffffff82fdaead)
Location: kernel/sched/sched.h:1709
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810f7f1f)
Location: kernel/sched/sched.h:1709
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810fc69c)
Location: kernel/sched/sched.h:1709
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
In kernel/sched/core.c (ffffffff831e59ab)
Location: kernel/sched/sched.h:1720
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810fa086)
Location: kernel/sched/sched.h:1720
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810fe9ec)
Location: kernel/sched/sched.h:1720
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
In kernel/sched/core.c (ffffffff832c99cd)
Location: kernel/sched/sched.h:2008
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff81114e6f)
Location: kernel/sched/sched.h:2008
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff8111a3ac)
Location: kernel/sched/sched.h:2008
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
In kernel/sched/core.c (ffffffff8347cc61)
Location: kernel/sched/sched.h:2003
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/build_policy.c (ffffffff8113a137)
Location: kernel/sched/sched.h:2003
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff83ea808d)
Location: kernel/sched/sched.h:2053
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/build_policy.c (ffffffff811649c7)
Location: kernel/sched/sched.h:2053
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff836cc95d)
Location: kernel/sched/sched.h:2096
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/build_policy.c (ffffffff81175167)
Location: kernel/sched/sched.h:2096
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
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
In kernel/sched/core.c (ffffffff838fdd5d)
Location: kernel/sched/sched.h:2138
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/build_policy.c (ffffffff81183477)
Location: kernel/sched/sched.h:2138
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
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
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffff800010151d10)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffff800010156f1c)
Location: kernel/sched/sched.h:1604
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
In kernel/sched/core.c (c151ec1c)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (c039efc4)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (c03a4b0c)
Location: kernel/sched/sched.h:1604
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
In kernel/sched/core.c (c0000000013693c8)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (c0000000001a569c)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (c0000000001aba10)
Location: kernel/sched/sched.h:1604
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
In kernel/sched/core.c (ffffffe000006a50)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffe0000f9ec0)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffffffe0000fde58)
Location: kernel/sched/sched.h:1604
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
In kernel/sched/core.c (ffffffff828b6117)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810e9aa6)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810edce5)
Location: kernel/sched/sched.h:1604
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
In kernel/sched/core.c (ffffffff828ae2b9)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810d99c2)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffffffff810ddd75)
Location: kernel/sched/sched.h:1604
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
In kernel/sched/core.c (ffffffff828c902d)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810e6b32)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_rt_schedulable
```
```
In kernel/sched/deadline.c (ffffffff810eae15)
Location: kernel/sched/sched.h:1604
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
In kernel/sched/core.c (ffffffff828ce36d)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/rt.c (ffffffff810f1b14)
Location: kernel/sched/sched.h:1604
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
```
```
In kernel/sched/deadline.c (ffffffff810f5de5)
Location: kernel/sched/sched.h:1604
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
