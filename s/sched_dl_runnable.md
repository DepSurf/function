# Function: <code>sched_dl_runnable</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1809
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1809
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
In kernel/sched/rt.c (ffffffff810f9758)
Location: kernel/sched/sched.h:1838
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd453)
Location: kernel/sched/sched.h:1838
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
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
In kernel/sched/rt.c (ffffffff810f7b07)
Location: kernel/sched/sched.h:1927
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fba13)
Location: kernel/sched/sched.h:1927
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
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
In kernel/sched/rt.c (ffffffff810f98f7)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fdd33)
Location: kernel/sched/sched.h:1938
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
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
In kernel/sched/rt.c (ffffffff81113157)
Location: kernel/sched/sched.h:2228
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff81116b35)
Location: kernel/sched/sched.h:2228
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:balance_dl
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
In kernel/sched/build_policy.c (ffffffff811391c5)
Location: kernel/sched/sched.h:2223
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:balance_rt
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
In kernel/sched/build_policy.c (ffffffff81163885)
Location: kernel/sched/sched.h:2274
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:balance_rt
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
In kernel/sched/build_policy.c (ffffffff81174065)
Location: kernel/sched/sched.h:2321
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:balance_rt
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
In kernel/sched/build_policy.c (ffffffff8117e8a5)
Location: kernel/sched/sched.h:2373
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_task_dl
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:balance_rt
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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1809
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1809
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
In kernel/sched/rt.c (c039c60c)
Location: kernel/sched/sched.h:1809
Inline: True
```
```
In kernel/sched/deadline.c (c03a0104)
Location: kernel/sched/sched.h:1809
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
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
In kernel/sched/rt.c (c0000000001a2260)
Location: kernel/sched/sched.h:1809
Inline: True
```
```
In kernel/sched/deadline.c (c0000000001a7814)
Location: kernel/sched/sched.h:1809
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:balance_dl
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
In kernel/sched/rt.c (ffffffe0000f96b4)
Location: kernel/sched/sched.h:1809
Inline: True
```
```
In kernel/sched/deadline.c (ffffffe0000fba8e)
Location: kernel/sched/sched.h:1809
Inline: True
Inline callers:
  - kernel/sched/deadline.c:balance_dl
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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1809
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1809
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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1809
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1809
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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1809
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1809
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
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1809
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1809
Inline: True
```
</details>
</li>
</ul>

## Differences
