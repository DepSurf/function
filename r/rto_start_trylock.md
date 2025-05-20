# Function: <code>rto_start_trylock</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810caa6c)
Location: kernel/sched/rt.c:1957
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810d3cdb)
Location: kernel/sched/rt.c:1968
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810dd97b)
Location: kernel/sched/rt.c:1979
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810e496b)
Location: kernel/sched/rt.c:1979
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810efb3b)
Location: kernel/sched/rt.c:1969
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810f8033)
Location: kernel/sched/rt.c:2039
Inline: True
Inline callers:
  - kernel/sched/rt.c:tell_cpu_to_push
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
In kernel/sched/rt.c (ffffffff810f6243)
Location: kernel/sched/rt.c:2067
Inline: True
Inline callers:
  - kernel/sched/rt.c:tell_cpu_to_push
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
In kernel/sched/rt.c (ffffffff810f94c9)
Location: kernel/sched/rt.c:2067
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff81112c89)
Location: kernel/sched/rt.c:2092
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/build_policy.c (ffffffff8112ff8f)
Location: kernel/sched/rt.c:2269
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
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
In kernel/sched/build_policy.c (ffffffff8115a1da)
Location: kernel/sched/rt.c:2268
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
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
In kernel/sched/build_policy.c (ffffffff8116a3ea)
Location: kernel/sched/rt.c:2272
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
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
In kernel/sched/build_policy.c (ffffffff81177aaa)
Location: kernel/sched/rt.c:2219
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
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
In kernel/sched/rt.c (ffff800010150f40)
Location: kernel/sched/rt.c:1969
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (c039c4b4)
Location: kernel/sched/rt.c:1969
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (c0000000001a1dac)
Location: kernel/sched/rt.c:1969
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffe0000f957c)
Location: kernel/sched/rt.c:1969
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810e942b)
Location: kernel/sched/rt.c:1969
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810d8efb)
Location: kernel/sched/rt.c:1969
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810e606b)
Location: kernel/sched/rt.c:1969
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810efd6b)
Location: kernel/sched/rt.c:1969
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
</details>
</li>
</ul>

## Differences
