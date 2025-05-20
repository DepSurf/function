# Function: <code>update_sg_lb_stats</code>

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
In kernel/sched/fair.c (ffffffff810bc834)
Location: kernel/sched/fair.c:6315
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810bffdf)
Location: kernel/sched/fair.c:6776
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810c5faf)
Location: kernel/sched/fair.c:7339
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810bfb97)
Location: kernel/sched/fair.c:7335
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810c7354)
Location: kernel/sched/fair.c:7784
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810cf2e7)
Location: kernel/sched/fair.c:8120
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
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
In kernel/sched/fair.c (ffffffff810d87a3)
Location: kernel/sched/fair.c:8138
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810dfabd)
Location: kernel/sched/fair.c:8045
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810ea15d)
Location: kernel/sched/fair.c:8028
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_sg_lb_stats(struct lb_env *env, struct sched_group *group, struct sg_lb_stats *sgs, int *sg_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f2bd0)
Location: kernel/sched/fair.c:8337
Inline: False
```
**Symbols:**

```
ffffffff810f2bd0-ffffffff810f2fb6: update_sg_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_sg_lb_stats(struct lb_env *env, struct sched_group *group, struct sg_lb_stats *sgs, int *sg_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f0da0)
Location: kernel/sched/fair.c:8415
Inline: False
```
**Symbols:**

```
ffffffff810f0da0-ffffffff810f11af: update_sg_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_sg_lb_stats(struct lb_env *env, struct sched_group *group, struct sg_lb_stats *sgs, int *sg_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3160)
Location: kernel/sched/fair.c:8485
Inline: False
```
**Symbols:**

```
ffffffff810f3160-ffffffff810f34b8: update_sg_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_sg_lb_stats(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *group, struct sg_lb_stats *sgs, int *sg_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110c7b0)
Location: kernel/sched/fair.c:8716
Inline: False
```
**Symbols:**

```
ffffffff8110c7b0-ffffffff8110cd13: update_sg_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_sg_lb_stats(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *group, struct sg_lb_stats *sgs, int *sg_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811281e0)
Location: kernel/sched/fair.c:8706
Inline: False
```
**Symbols:**

```
ffffffff811281e0-ffffffff81128843: update_sg_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_sg_lb_stats(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *group, struct sg_lb_stats *sgs, int *sg_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81151610)
Location: kernel/sched/fair.c:9229
Inline: False
```
**Symbols:**

```
ffffffff81151610-ffffffff81151ee9: update_sg_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_sg_lb_stats(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *group, struct sg_lb_stats *sgs, int *sg_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81160c00)
Location: kernel/sched/fair.c:9486
Inline: False
```
**Symbols:**

```
ffffffff81160c00-ffffffff8116122b: update_sg_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_sg_lb_stats(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *group, struct sg_lb_stats *sgs, int *sg_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116afe0)
Location: kernel/sched/fair.c:9876
Inline: False
```
**Symbols:**

```
ffffffff8116afe0-ffffffff8116b59e: update_sg_lb_stats (STB_LOCAL)
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
In kernel/sched/fair.c (ffff80001014a380)
Location: kernel/sched/fair.c:8028
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (c0397fec)
Location: kernel/sched/fair.c:8028
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (c00000000019c514)
Location: kernel/sched/fair.c:8028
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffe0000f3df6)
Location: kernel/sched/fair.c:8028
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810e42bd)
Location: kernel/sched/fair.c:8028
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810d346d)
Location: kernel/sched/fair.c:8028
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810e068d)
Location: kernel/sched/fair.c:8028
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810ec20d)
Location: kernel/sched/fair.c:8028
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sd_lb_stats *sds</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, group, sgs, sg_status</code> ➡️ <code>env, sds, group, sgs, sg_status</code>
</li>
</ul>
</details>
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
