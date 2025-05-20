# Function: <code>__add_running_bw</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d5f6b)
Location: kernel/sched/deadline.c:78
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810dfe3b)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810e7b73)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/deadline.c (ffffffff810f31b3)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/deadline.c (ffffffff810fc86b)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/deadline.c (ffffffff810fa9f5)
Location: kernel/sched/deadline.c:156
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/deadline.c (ffffffff810fcbfe)
Location: kernel/sched/deadline.c:156
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/deadline.c (ffffffff8111919a)
Location: kernel/sched/deadline.c:156
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/build_policy.c (ffffffff811357f5)
Location: kernel/sched/deadline.c:230
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:dl_task_offline_migration
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
In kernel/sched/build_policy.c (ffffffff8115fd75)
Location: kernel/sched/deadline.c:232
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:dl_task_offline_migration
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
In kernel/sched/build_policy.c (ffffffff81170485)
Location: kernel/sched/deadline.c:234
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:dl_task_offline_migration
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
In kernel/sched/build_policy.c (ffffffff8117d28d)
Location: kernel/sched/deadline.c:247
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_contending
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
In kernel/sched/deadline.c (ffff80001015541c)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/deadline.c (c03a2c18)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/deadline.c (c0000000001a9524)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/deadline.c (ffffffe0000fce9e)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/deadline.c (ffffffff810ec5b3)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/deadline.c (ffffffff810dc653)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/deadline.c (ffffffff810e96e3)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/deadline.c (ffffffff810f4693)
Location: kernel/sched/deadline.c:79
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
```
</details>
</li>
</ul>

## Differences
