# Function: <code>update_dl_entity</code>

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
In kernel/sched/deadline.c (ffffffff810c1dda)
Location: kernel/sched/deadline.c:491
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810c5967)
Location: kernel/sched/deadline.c:507
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810cb947)
Location: kernel/sched/deadline.c:495
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810c79a1)
Location: kernel/sched/deadline.c:819
Inline: True
Inline callers:
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
In kernel/sched/deadline.c (ffffffff810cef6e)
Location: kernel/sched/deadline.c:818
Inline: True
Inline callers:
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
In kernel/sched/deadline.c (ffffffff810d68b0)
Location: kernel/sched/deadline.c:851
Inline: True
Inline callers:
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
In kernel/sched/deadline.c (ffffffff810e0df0)
Location: kernel/sched/deadline.c:852
Inline: True
Inline callers:
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
In kernel/sched/deadline.c (ffffffff810e7726)
Location: kernel/sched/deadline.c:851
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810f2d44)
Location: kernel/sched/deadline.c:884
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb6f0)
Location: kernel/sched/deadline.c:886
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810fb6f0-ffffffff810fb95f: update_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f9aa0)
Location: kernel/sched/deadline.c:961
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810f9aa0-ffffffff810f9d0c: update_dl_entity (STB_LOCAL)
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
In kernel/sched/deadline.c (ffffffff810fc6c3)
Location: kernel/sched/deadline.c:947
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff81118c03)
Location: kernel/sched/deadline.c:947
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/build_policy.c (ffffffff811351f4)
Location: kernel/sched/deadline.c:1010
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
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
In kernel/sched/build_policy.c (ffffffff8115f74c)
Location: kernel/sched/deadline.c:1016
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
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
In kernel/sched/build_policy.c (ffffffff8116fcc4)
Location: kernel/sched/deadline.c:1011
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
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
In kernel/sched/build_policy.c (ffffffff8117d53a)
Location: kernel/sched/deadline.c:1012
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffff800010154fa8)
Location: kernel/sched/deadline.c:884
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (c03a243c)
Location: kernel/sched/deadline.c:884
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (c0000000001a8ed4)
Location: kernel/sched/deadline.c:884
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffe0000fca58)
Location: kernel/sched/deadline.c:884
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810ec144)
Location: kernel/sched/deadline.c:884
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810dc179)
Location: kernel/sched/deadline.c:884
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810e9274)
Location: kernel/sched/deadline.c:884
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810f4224)
Location: kernel/sched/deadline.c:884
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sched_dl_entity *pi_se</code>
</li>
</ul>
</details>
</li>
</ul>
