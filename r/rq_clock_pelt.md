# Function: <code>rq_clock_pelt</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dd438)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810e3a07)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e85dc)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/fair.c (ffffffff810e7a77)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810ef547)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810f1720)
Location: kernel/sched/pelt.h:117
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
In kernel/sched/fair.c (ffffffff810ed6e7)
Location: kernel/sched/pelt.h:137
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810f8e48)
Location: kernel/sched/pelt.h:137
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa990)
Location: kernel/sched/pelt.h:137
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
In kernel/sched/fair.c (ffffffff810eb4f9)
Location: kernel/sched/pelt.h:142
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810f7038)
Location: kernel/sched/pelt.h:142
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810f8e43)
Location: kernel/sched/pelt.h:142
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
In kernel/sched/fair.c (ffffffff810edda5)
Location: kernel/sched/pelt.h:133
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810f9188)
Location: kernel/sched/pelt.h:133
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810fade1)
Location: kernel/sched/pelt.h:133
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
In kernel/sched/fair.c (ffffffff81106b9e)
Location: kernel/sched/pelt.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff81114759)
Location: kernel/sched/pelt.h:135
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff811169c1)
Location: kernel/sched/pelt.h:135
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
In kernel/sched/fair.c (ffffffff8112d17e)
Location: kernel/sched/pelt.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/build_policy.c (ffffffff81137f39)
Location: kernel/sched/pelt.h:135
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/core.c (ffffffff81137222)
Location: kernel/sched/pelt.h:64
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81156ef8)
Location: kernel/sched/pelt.h:64
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/build_policy.c (ffffffff811625f9)
Location: kernel/sched/pelt.h:64
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/core.c (ffffffff81146281)
Location: kernel/sched/pelt.h:64
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81166fab)
Location: kernel/sched/pelt.h:64
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/build_policy.c (ffffffff81172d79)
Location: kernel/sched/pelt.h:64
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/core.c (ffffffff81151851)
Location: kernel/sched/pelt.h:64
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81173d2b)
Location: kernel/sched/pelt.h:64
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/build_policy.c (ffffffff81180689)
Location: kernel/sched/pelt.h:64
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/fair.c (ffff800010148058)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffff8000101507b0)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffff800010153fac)
Location: kernel/sched/pelt.h:117
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
In kernel/sched/fair.c (c0393fcc)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (c039e46c)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (c03a07f4)
Location: kernel/sched/pelt.h:117
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
In kernel/sched/fair.c (c000000000198eec)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (c0000000001a4870)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (c0000000001a7678)
Location: kernel/sched/pelt.h:117
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
In kernel/sched/fair.c (ffffffe0000f0b98)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffe0000f8e82)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fbb3e)
Location: kernel/sched/pelt.h:117
Inline: True
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
In kernel/sched/fair.c (ffffffff810e1c27)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810e8dc7)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810eab20)
Location: kernel/sched/pelt.h:117
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
In kernel/sched/fair.c (ffffffff810d0d07)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810d8907)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810dab40)
Location: kernel/sched/pelt.h:117
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
In kernel/sched/fair.c (ffffffff810ddfa7)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810e5a77)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e7c50)
Location: kernel/sched/pelt.h:117
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
In kernel/sched/fair.c (ffffffff810e9a97)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810f0957)
Location: kernel/sched/pelt.h:117
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810f2ec0)
Location: kernel/sched/pelt.h:117
Inline: True
```
</details>
</li>
</ul>

## Differences
