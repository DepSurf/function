# Function: <code>update_sd_pick_busiest</code>

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
In kernel/sched/fair.c (ffffffff810bcad0)
Location: kernel/sched/fair.c:6376
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
In kernel/sched/fair.c (ffffffff810c0282)
Location: kernel/sched/fair.c:6841
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
In kernel/sched/fair.c (ffffffff810c6252)
Location: kernel/sched/fair.c:7404
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
In kernel/sched/fair.c (ffffffff810bfe66)
Location: kernel/sched/fair.c:7400
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
In kernel/sched/fair.c (ffffffff810c75f8)
Location: kernel/sched/fair.c:7849
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
In kernel/sched/fair.c (ffffffff810cf529)
Location: kernel/sched/fair.c:8188
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
In kernel/sched/fair.c (ffffffff810d8b02)
Location: kernel/sched/fair.c:8217
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
In kernel/sched/fair.c (ffffffff810dfd61)
Location: kernel/sched/fair.c:8114
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
In kernel/sched/fair.c (ffffffff810ea3fd)
Location: kernel/sched/fair.c:8097
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
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
In kernel/sched/fair.c (ffffffff810f477f)
Location: kernel/sched/fair.c:8425
Inline: True
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
In kernel/sched/fair.c (ffffffff810f299f)
Location: kernel/sched/fair.c:8503
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool update_sd_pick_busiest(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *sg, struct sg_lb_stats *sgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f2e60)
Location: kernel/sched/fair.c:8570
Inline: False
```
**Symbols:**

```
ffffffff810f2e60-ffffffff810f3003: update_sd_pick_busiest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool update_sd_pick_busiest(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *sg, struct sg_lb_stats *sgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110c590)
Location: kernel/sched/fair.c:8801
Inline: False
```
**Symbols:**

```
ffffffff8110c590-ffffffff8110c7a6: update_sd_pick_busiest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool update_sd_pick_busiest(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *sg, struct sg_lb_stats *sgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81127fb0)
Location: kernel/sched/fair.c:8798
Inline: False
```
**Symbols:**

```
ffffffff81127fb0-ffffffff811281d3: update_sd_pick_busiest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool update_sd_pick_busiest(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *sg, struct sg_lb_stats *sgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811513d0)
Location: kernel/sched/fair.c:9321
Inline: False
```
**Symbols:**

```
ffffffff811513d0-ffffffff811515f3: update_sd_pick_busiest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool update_sd_pick_busiest(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *sg, struct sg_lb_stats *sgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811609b0)
Location: kernel/sched/fair.c:9578
Inline: False
```
**Symbols:**

```
ffffffff811609b0-ffffffff81160be2: update_sd_pick_busiest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool update_sd_pick_busiest(struct lb_env *env, struct sd_lb_stats *sds, struct sched_group *sg, struct sg_lb_stats *sgs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116ad60)
Location: kernel/sched/fair.c:9972
Inline: False
```
**Symbols:**

```
ffffffff8116ad60-ffffffff8116afc2: update_sd_pick_busiest (STB_LOCAL)
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
In kernel/sched/fair.c (ffff80001014a5b8)
Location: kernel/sched/fair.c:8097
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
In kernel/sched/fair.c (c0398240)
Location: kernel/sched/fair.c:8097
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
In kernel/sched/fair.c (c00000000019c780)
Location: kernel/sched/fair.c:8097
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
In kernel/sched/fair.c (ffffffe0000f4058)
Location: kernel/sched/fair.c:8097
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
In kernel/sched/fair.c (ffffffff810e455d)
Location: kernel/sched/fair.c:8097
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
In kernel/sched/fair.c (ffffffff810d370d)
Location: kernel/sched/fair.c:8097
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
In kernel/sched/fair.c (ffffffff810e092d)
Location: kernel/sched/fair.c:8097
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
In kernel/sched/fair.c (ffffffff810ec4ad)
Location: kernel/sched/fair.c:8097
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
