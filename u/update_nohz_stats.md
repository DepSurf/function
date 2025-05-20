# Function: <code>update_nohz_stats</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810caef0)
Location: kernel/sched/fair.c:8089
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810caef0-ffffffff810caf44: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d34d0)
Location: kernel/sched/fair.c:8109
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810d34d0-ffffffff810d3524: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dd900)
Location: kernel/sched/fair.c:8016
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810dd900-ffffffff810dd957: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e7fc0)
Location: kernel/sched/fair.c:7999
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810e7fc0-ffffffff810e8017: update_nohz_stats (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810f5a79)
Location: kernel/sched/fair.c:8308
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sg_lb_stats
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
In kernel/sched/fair.c (ffffffff810f3b89)
Location: kernel/sched/fair.c:8386
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sg_lb_stats
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
In kernel/sched/fair.c (ffffffff810f63a4)
Location: kernel/sched/fair.c:10432
Inline: True
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
In kernel/sched/fair.c (ffffffff8111017a)
Location: kernel/sched/fair.c:10674
Inline: True
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
In kernel/sched/fair.c (ffffffff8112c284)
Location: kernel/sched/fair.c:10780
Inline: True
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
In kernel/sched/fair.c (ffffffff81155f64)
Location: kernel/sched/fair.c:11308
Inline: True
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
In kernel/sched/fair.c (ffffffff8116606c)
Location: kernel/sched/fair.c:11612
Inline: True
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
In kernel/sched/fair.c (ffffffff81172dcc)
Location: kernel/sched/fair.c:12076
Inline: True
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
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010148550)
Location: kernel/sched/fair.c:7999
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffff800010148550-ffff8000101485f0: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0394570)
Location: kernel/sched/fair.c:7999
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
c0394570-c039460c: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001994e0)
Location: kernel/sched/fair.c:7999
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
c0000000001994e0-c0000000001995a8: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f0f50)
Location: kernel/sched/fair.c:7999
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffe0000f0f50-ffffffe0000f0fd0: update_nohz_stats (STB_LOCAL)
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
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2170)
Location: kernel/sched/fair.c:7999
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810e2170-ffffffff810e21c7: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1250)
Location: kernel/sched/fair.c:7999
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810d1250-ffffffff810d12a7: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810de4f0)
Location: kernel/sched/fair.c:7999
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810de4f0-ffffffff810de547: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq *rq, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9ff0)
Location: kernel/sched/fair.c:7999
Inline: False
Direct callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810e9ff0-ffffffff810ea047: update_nohz_stats (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
