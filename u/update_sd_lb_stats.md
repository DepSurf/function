# Function: <code>update_sd_lb_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bc7c0)
Location: kernel/sched/fair.c:6447
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810bc7c0-ffffffff810bccdd: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bff70)
Location: kernel/sched/fair.c:6916
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810bff70-ffffffff810c0476: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5f40)
Location: kernel/sched/fair.c:7495
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810c5f40-ffffffff810c6479: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bfb10)
Location: kernel/sched/fair.c:7491
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810bfb10-ffffffff810c00d6: update_sd_lb_stats (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810c72f8)
Location: kernel/sched/fair.c:7940
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
In kernel/sched/fair.c (ffffffff810cf214)
Location: kernel/sched/fair.c:8279
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d8700)
Location: kernel/sched/fair.c:8326
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810d8700-ffffffff810d8edd: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810df9d0)
Location: kernel/sched/fair.c:8223
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810df9d0-ffffffff810e01a1: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea070)
Location: kernel/sched/fair.c:8206
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810ea070-ffffffff810ea83f: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f46b0)
Location: kernel/sched/fair.c:8868
Inline: True
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810f46b0-ffffffff810f4af5: update_sd_lb_stats.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f28d0)
Location: kernel/sched/fair.c:8964
Inline: True
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810f28d0-ffffffff810f2ce6: update_sd_lb_stats.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4c70)
Location: kernel/sched/fair.c:9031
Inline: True
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810f4c70-ffffffff810f4ebb: update_sd_lb_stats.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110e760)
Location: kernel/sched/fair.c:9266
Inline: True
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff8110e760-ffffffff8110e9a8: update_sd_lb_stats.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112a4f0)
Location: kernel/sched/fair.c:9336
Inline: True
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff8112a4f0-ffffffff8112a8ce: update_sd_lb_stats.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff81153e90)
Location: kernel/sched/fair.c:9869
Inline: True
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff81153e90-ffffffff8115426e: update_sd_lb_stats.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff81164020)
Location: kernel/sched/fair.c:10138
Inline: True
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff81164020-ffffffff811643ee: update_sd_lb_stats.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff81170cf0)
Location: kernel/sched/fair.c:10557
Inline: True
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff81170cf0-ffffffff811710d5: update_sd_lb_stats.constprop.0 (STB_LOCAL)
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
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014a280)
Location: kernel/sched/fair.c:8206
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffff80001014a280-ffff80001014a9d0: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0397ec4)
Location: kernel/sched/fair.c:8206
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
c0397ec4-c0398648: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019c3d0)
Location: kernel/sched/fair.c:8206
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
c00000000019c3d0-c00000000019ccf4: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f3da4)
Location: kernel/sched/fair.c:8206
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffe0000f3da4-ffffffe0000f43d6: update_sd_lb_stats (STB_LOCAL)
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
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e41d0)
Location: kernel/sched/fair.c:8206
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810e41d0-ffffffff810e499f: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d3380)
Location: kernel/sched/fair.c:8206
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810d3380-ffffffff810d3b4f: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e05a0)
Location: kernel/sched/fair.c:8206
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810e05a0-ffffffff810e0d6f: update_sd_lb_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_sd_lb_stats(struct lb_env *env, struct sd_lb_stats *sds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec120)
Location: kernel/sched/fair.c:8206
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810ec120-ffffffff810ec90f: update_sd_lb_stats (STB_LOCAL)
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
