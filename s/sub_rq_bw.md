# Function: <code>sub_rq_bw</code>

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
In kernel/sched/deadline.c (ffffffff810c5e59)
Location: kernel/sched/deadline.c:113
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810cd7fe)
Location: kernel/sched/deadline.c:114
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810d7a56)
Location: kernel/sched/deadline.c:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810e0686)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810e7344)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810f2964)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810fbfbb)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810fa516)
Location: kernel/sched/deadline.c:213
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810fc44b)
Location: kernel/sched/deadline.c:213
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff81117fc1)
Location: kernel/sched/deadline.c:213
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81132ab1)
Location: kernel/sched/deadline.c:287
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115cdc1)
Location: kernel/sched/deadline.c:289
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116db96)
Location: kernel/sched/deadline.c:291
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
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
In kernel/sched/build_policy.c (ffffffff8117a966)
Location: kernel/sched/deadline.c:304
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
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
In kernel/sched/deadline.c (ffff800010154c04)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (c03a1ccc)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (c0000000001aa0f0)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffe0000fd65e)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810ebd64)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810dbd84)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810e8e94)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810f3e44)
Location: kernel/sched/deadline.c:136
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
```
</details>
</li>
</ul>

## Differences
