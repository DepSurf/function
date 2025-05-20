# Function: <code>trace_sched_stat_runtime</code>

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
In kernel/sched/fair.c (ffffffff810b4b13)
Location: include/trace/events/sched.h:406
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b7683)
Location: include/trace/events/sched.h:406
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf993)
Location: include/trace/events/sched.h:406
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bb345)
Location: include/trace/events/sched.h:407
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810c2ee5)
Location: include/trace/events/sched.h:413
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810c93b2)
Location: include/trace/events/sched.h:413
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810d37a2)
Location: include/trace/events/sched.h:428
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810dac95)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e4bb5)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ee1c5)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebfd3)
Location: include/trace/events/sched.h:519
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ee96f)
Location: include/trace/events/sched.h:519
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81106fb6)
Location: include/trace/events/sched.h:517
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff81124147)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff8113612f)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:update_curr_rt
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
In kernel/sched/fair.c (ffffffff8114c0e8)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff8116070f)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:update_curr_rt
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
In kernel/sched/fair.c (ffffffff8115a378)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81170e35)
Location: include/trace/events/sched.h:520
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81164b2b)
Location: include/trace/events/sched.h:517
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff8000101448f8)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c039220c)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000195b38)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f14d2)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ded65)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cdd75)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810db0e5)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6da5)
Location: include/trace/events/sched.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
</ul>

## Differences
