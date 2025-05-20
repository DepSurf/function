# Function: <code>sched_asym_prefer</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b87d7)
Location: kernel/sched/sched.h:543
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/fair.c (ffffffff810c8000)
Location: kernel/sched/sched.h:543
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810c1cb0)
Location: kernel/sched/sched.h:611
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810cd173)
Location: kernel/sched/sched.h:611
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810c9424)
Location: kernel/sched/sched.h:607
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
```
```
In kernel/sched/topology.c (ffffffff810d40bb)
Location: kernel/sched/sched.h:607
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810d159f)
Location: kernel/sched/sched.h:678
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
```
```
In kernel/sched/topology.c (ffffffff810dbd84)
Location: kernel/sched/sched.h:678
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810daecd)
Location: kernel/sched/sched.h:708
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810e5a2b)
Location: kernel/sched/sched.h:708
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810e2264)
Location: kernel/sched/sched.h:702
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810ec5f3)
Location: kernel/sched/sched.h:702
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810ec914)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810f808f)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810f6648)
Location: kernel/sched/sched.h:736
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
```
```
In kernel/sched/topology.c (ffffffff8110079d)
Location: kernel/sched/sched.h:736
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_sched_groups_capacity
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
In kernel/sched/fair.c (ffffffff810f47b8)
Location: kernel/sched/sched.h:748
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810ff2ed)
Location: kernel/sched/sched.h:748
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_sched_groups_capacity
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
In kernel/sched/fair.c (ffffffff810f681b)
Location: kernel/sched/sched.h:757
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
```
```
In kernel/sched/topology.c (ffffffff8110305f)
Location: kernel/sched/sched.h:757
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff81110630)
Location: kernel/sched/sched.h:774
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
```
```
In kernel/sched/topology.c (ffffffff8111fce8)
Location: kernel/sched/sched.h:774
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff8112c83f)
Location: kernel/sched/sched.h:769
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
```
```
In kernel/sched/build_utility.c (ffffffff81149df7)
Location: kernel/sched/sched.h:769
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff8115651b)
Location: kernel/sched/sched.h:799
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
```
```
In kernel/sched/build_utility.c (ffffffff81178724)
Location: kernel/sched/sched.h:799
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff811665d7)
Location: kernel/sched/sched.h:802
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
```
```
In kernel/sched/build_utility.c (ffffffff811893cf)
Location: kernel/sched/sched.h:802
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff8117332a)
Location: kernel/sched/sched.h:828
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
```
```
In kernel/sched/build_utility.c (ffffffff8118cb45)
Location: kernel/sched/sched.h:828
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:init_sched_groups_capacity
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
In kernel/sched/fair.c (ffff80001014cdf4)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffff80001015c590)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (c039ab40)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (c03a8fe0)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (c00000000019fb04)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (c0000000001b0d80)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffe0000f624e)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffe000101752)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810e6a74)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810f148f)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810d5c14)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810e14ff)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810e2e44)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810ee5bf)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810eea1e)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810f95ff)
Location: kernel/sched/sched.h:709
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
</ul>

## Differences
