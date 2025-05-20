# Function: <code>tell_cpu_to_push</code>

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
In kernel/sched/rt.c (ffffffff810bf624)
Location: kernel/sched/rt.c:1868
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810c2f34)
Location: kernel/sched/rt.c:1931
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810c8f94)
Location: kernel/sched/rt.c:1930
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810c3065)
Location: kernel/sched/rt.c:2022
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
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
In kernel/sched/rt.c (ffffffff810caa65)
Location: kernel/sched/rt.c:1967
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
In kernel/sched/rt.c (ffffffff810d3cd4)
Location: kernel/sched/rt.c:1978
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
In kernel/sched/rt.c (ffffffff810dd974)
Location: kernel/sched/rt.c:1989
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
In kernel/sched/rt.c (ffffffff810e495c)
Location: kernel/sched/rt.c:1989
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
In kernel/sched/rt.c (ffffffff810efb2c)
Location: kernel/sched/rt.c:1979
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tell_cpu_to_push(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8020)
Location: kernel/sched/rt.c:2049
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810f8020-ffffffff810f812d: tell_cpu_to_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tell_cpu_to_push(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f6230)
Location: kernel/sched/rt.c:2077
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810f6230-ffffffff810f633d: tell_cpu_to_push (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810f94ba)
Location: kernel/sched/rt.c:2077
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
In kernel/sched/rt.c (ffffffff81112c7a)
Location: kernel/sched/rt.c:2102
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
In kernel/sched/build_policy.c (ffffffff8112ff81)
Location: kernel/sched/rt.c:2279
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
In kernel/sched/build_policy.c (ffffffff8115a1cc)
Location: kernel/sched/rt.c:2278
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
In kernel/sched/build_policy.c (ffffffff8116a3dc)
Location: kernel/sched/rt.c:2282
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
In kernel/sched/build_policy.c (ffffffff81177a9c)
Location: kernel/sched/rt.c:2229
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
In kernel/sched/rt.c (ffff800010150f2c)
Location: kernel/sched/rt.c:1979
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
In kernel/sched/rt.c (c039c490)
Location: kernel/sched/rt.c:1979
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
In kernel/sched/rt.c (c0000000001a1d98)
Location: kernel/sched/rt.c:1979
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
In kernel/sched/rt.c (ffffffe0000f9572)
Location: kernel/sched/rt.c:1979
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
In kernel/sched/rt.c (ffffffff810e941c)
Location: kernel/sched/rt.c:1979
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
In kernel/sched/rt.c (ffffffff810d8eec)
Location: kernel/sched/rt.c:1979
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
In kernel/sched/rt.c (ffffffff810e605c)
Location: kernel/sched/rt.c:1979
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
In kernel/sched/rt.c (ffffffff810efd5c)
Location: kernel/sched/rt.c:1979
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
