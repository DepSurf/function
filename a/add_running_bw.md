# Function: <code>add_running_bw</code>

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
In kernel/sched/deadline.c (ffffffff810c5eec)
Location: kernel/sched/deadline.c:80
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810cd892)
Location: kernel/sched/deadline.c:81
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810d5f62)
Location: kernel/sched/deadline.c:142
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
In kernel/sched/deadline.c (ffffffff810dfe32)
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (ffffffff810e7b68)
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (ffffffff810f31a8)
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (ffffffff810fc860)
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (ffffffff810fa9ea)
Location: kernel/sched/deadline.c:220
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
In kernel/sched/deadline.c (ffffffff810fcbf3)
Location: kernel/sched/deadline.c:220
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
In kernel/sched/deadline.c (ffffffff8111918f)
Location: kernel/sched/deadline.c:220
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
In kernel/sched/build_policy.c (ffffffff811357ec)
Location: kernel/sched/deadline.c:294
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
In kernel/sched/build_policy.c (ffffffff8115fd6c)
Location: kernel/sched/deadline.c:296
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
In kernel/sched/build_policy.c (ffffffff8117047c)
Location: kernel/sched/deadline.c:298
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
In kernel/sched/build_policy.c (ffffffff8117d287)
Location: kernel/sched/deadline.c:311
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
In kernel/sched/deadline.c (ffff800010155414)
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (c03a2c0c)
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (c0000000001a9518)
Location: kernel/sched/deadline.c:143
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
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (ffffffff810ec5a8)
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (ffffffff810dc648)
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (ffffffff810e96d8)
Location: kernel/sched/deadline.c:143
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
In kernel/sched/deadline.c (ffffffff810f4688)
Location: kernel/sched/deadline.c:143
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
