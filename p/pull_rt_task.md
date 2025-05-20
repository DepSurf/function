# Function: <code>pull_rt_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810bf5f0)
Location: kernel/sched/rt.c:1962
Inline: False
```
**Symbols:**

```
ffffffff810bf5f0-ffffffff810bf8b7: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c2f00)
Location: kernel/sched/rt.c:2025
Inline: False
```
**Symbols:**

```
ffffffff810c2f00-ffffffff810c31e5: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c8f60)
Location: kernel/sched/rt.c:2024
Inline: False
```
**Symbols:**

```
ffffffff810c8f60-ffffffff810c924e: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c3030)
Location: kernel/sched/rt.c:2116
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810c3030-ffffffff810c32d7: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810caa20)
Location: kernel/sched/rt.c:2037
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810caa20-ffffffff810cad08: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d3c90)
Location: kernel/sched/rt.c:2048
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810d3c90-ffffffff810d3f60: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dd930)
Location: kernel/sched/rt.c:2059
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810dd930-ffffffff810ddc00: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:2059
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810e4920-ffffffff810e4bf6: pull_rt_task (STB_LOCAL)
ffffffff810e5331-ffffffff810e5375: pull_rt_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810efaf0)
Location: kernel/sched/rt.c:2049
Inline: False
```
**Symbols:**

```
ffffffff810efaf0-ffffffff810efdc9: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f94d0)
Location: kernel/sched/rt.c:2119
Inline: False
Direct callers:
  - kernel/sched/rt.c:balance_rt
```
**Symbols:**

```
ffffffff810f94d0-ffffffff810f9720: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f77d0)
Location: kernel/sched/rt.c:2148
Inline: False
Direct callers:
  - kernel/sched/rt.c:balance_rt
```
**Symbols:**

```
ffffffff810f77d0-ffffffff810f7ac8: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f9470)
Location: kernel/sched/rt.c:2148
Inline: False
Direct callers:
  - kernel/sched/rt.c:balance_rt
```
**Symbols:**

```
ffffffff810f9470-ffffffff810f98bf: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81112c30)
Location: kernel/sched/rt.c:2173
Inline: False
Direct callers:
  - kernel/sched/rt.c:balance_rt
```
**Symbols:**

```
ffffffff81112c30-ffffffff81113120: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112ff20)
Location: kernel/sched/rt.c:2350
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:balance_rt
```
**Symbols:**

```
ffffffff8112ff20-ffffffff811303b1: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115a170)
Location: kernel/sched/rt.c:2349
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:balance_rt
```
**Symbols:**

```
ffffffff8115a170-ffffffff8115a5ea: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116a380)
Location: kernel/sched/rt.c:2353
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:balance_rt
```
**Symbols:**

```
ffffffff8116a380-ffffffff8116a7fa: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81177a40)
Location: kernel/sched/rt.c:2300
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:balance_rt
```
**Symbols:**

```
ffffffff81177a40-ffffffff81177ed8: pull_rt_task (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010150ee0)
Location: kernel/sched/rt.c:2049
Inline: False
```
**Symbols:**

```
ffff800010150ee0-ffff80001015135c: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039c204)
Location: kernel/sched/rt.c:2049
Inline: False
```
**Symbols:**

```
c039c204-c039c5b8: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a1d50)
Location: kernel/sched/rt.c:2049
Inline: False
```
**Symbols:**

```
c0000000001a1d50-c0000000001a220c: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f952e)
Location: kernel/sched/rt.c:2049
Inline: False
```
**Symbols:**

```
ffffffe0000f952e-ffffffe0000f966c: pull_rt_task (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e93e0)
Location: kernel/sched/rt.c:2049
Inline: False
```
**Symbols:**

```
ffffffff810e93e0-ffffffff810e96b9: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d8eb0)
Location: kernel/sched/rt.c:2049
Inline: False
```
**Symbols:**

```
ffffffff810d8eb0-ffffffff810d9184: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e6020)
Location: kernel/sched/rt.c:2049
Inline: False
```
**Symbols:**

```
ffffffff810e6020-ffffffff810e62f9: pull_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pull_rt_task(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810efd20)
Location: kernel/sched/rt.c:2049
Inline: False
```
**Symbols:**

```
ffffffff810efd20-ffffffff810f0019: pull_rt_task (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
