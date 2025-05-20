# Function: <code>tcf_queue_work</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tcf_queue_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187f550)
Location: net/sched/cls_api.c:105
Inline: False
```
**Symbols:**

```
ffffffff8187f550-ffffffff8187f56f: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2370)
Location: net/sched/cls_api.c:106
Inline: False
```
**Symbols:**

```
ffffffff818d2370-ffffffff818d23a7: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fd910)
Location: net/sched/cls_api.c:136
Inline: False
```
**Symbols:**

```
ffffffff818fd910-ffffffff818fd947: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195d2e0)
Location: net/sched/cls_api.c:144
Inline: False
```
**Symbols:**

```
ffffffff8195d2e0-ffffffff8195d317: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819937e0)
Location: net/sched/cls_api.c:203
Inline: False
```
**Symbols:**

```
ffffffff819937e0-ffffffff81993817: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6b880)
Location: net/sched/cls_api.c:204
Inline: False
```
**Symbols:**

```
ffffffff81a6b880-ffffffff81a6b8b7: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a73ff0)
Location: net/sched/cls_api.c:204
Inline: False
```
**Symbols:**

```
ffffffff81a73ff0-ffffffff81a74027: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5cb40)
Location: net/sched/cls_api.c:204
Inline: False
```
**Symbols:**

```
ffffffff81a5cb40-ffffffff81a5cb77: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b15cf0)
Location: net/sched/cls_api.c:204
Inline: False
```
**Symbols:**

```
ffffffff81b15cf0-ffffffff81b15d27: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9d2d0)
Location: net/sched/cls_api.c:221
Inline: False
```
**Symbols:**

```
ffffffff81c9d2d0-ffffffff81c9d30f: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e597b0)
Location: net/sched/cls_api.c:223
Inline: False
```
**Symbols:**

```
ffffffff81e597b0-ffffffff81e597ef: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb51e0)
Location: net/sched/cls_api.c:325
Inline: False
```
**Symbols:**

```
ffffffff81eb51e0-ffffffff81eb521f: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f77ea0)
Location: net/sched/cls_api.c:325
Inline: False
```
**Symbols:**

```
ffffffff81f77ea0-ffffffff81f77edf: tcf_queue_work (STB_GLOBAL)
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
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c3fba0)
Location: net/sched/cls_api.c:203
Inline: False
```
**Symbols:**

```
ffff800010c3fba0-ffff800010c3fbec: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d51860)
Location: net/sched/cls_api.c:203
Inline: False
```
**Symbols:**

```
c0d51860-c0d518ac: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3a5b0)
Location: net/sched/cls_api.c:203
Inline: False
```
**Symbols:**

```
c000000000d3a5b0-c000000000d3a61c: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007af766)
Location: net/sched/cls_api.c:203
Inline: False
```
**Symbols:**

```
ffffffe0007af766-ffffffe0007af7b2: tcf_queue_work (STB_GLOBAL)
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
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81933650)
Location: net/sched/cls_api.c:203
Inline: False
```
**Symbols:**

```
ffffffff81933650-ffffffff81933687: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ed150)
Location: net/sched/cls_api.c:203
Inline: False
```
**Symbols:**

```
ffffffff818ed150-ffffffff818ed187: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819847e0)
Location: net/sched/cls_api.c:203
Inline: False
```
**Symbols:**

```
ffffffff819847e0-ffffffff81984817: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tcf_queue_work(struct rcu_work *rwork, work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a6e60)
Location: net/sched/cls_api.c:203
Inline: False
```
**Symbols:**

```
ffffffff819a6e60-ffffffff819a6e97: tcf_queue_work (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rcu_work *rwork</code>
</li>
<li>
<b>Param added. </b>
<code>work_func_t func</code>
</li>
<li>
<b>Param removed. </b>
<code>struct work_struct *work</code>
</li>
</ul>
</details>
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
