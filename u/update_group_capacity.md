# Function: <code>update_group_capacity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bc5f0)
Location: kernel/sched/fair.c:6138
Inline: False
Direct callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810bc5f0-ffffffff810bc7b3: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bfdb0)
Location: kernel/sched/fair.c:6599
Inline: False
Direct callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810bfdb0-ffffffff810bff6d: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5d50)
Location: kernel/sched/fair.c:7145
Inline: False
Direct callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810c5d50-ffffffff810c5f3b: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf910)
Location: kernel/sched/fair.c:7141
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810bf910-ffffffff810bfb0b: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c70e0)
Location: kernel/sched/fair.c:7590
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810c70e0-ffffffff810c72cd: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cefe0)
Location: kernel/sched/fair.c:7904
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810cefe0-ffffffff810cf1c8: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d8550)
Location: kernel/sched/fair.c:7906
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810d8550-ffffffff810d86fc: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810df800)
Location: kernel/sched/fair.c:7801
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810df800-ffffffff810df9c2: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9ea0)
Location: kernel/sched/fair.c:7786
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810e9ea0-ffffffff810ea062: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4510)
Location: kernel/sched/fair.c:8098
Inline: False
Direct callers:
  - kernel/sched/topology.c:init_sched_groups_capacity
```
**Symbols:**

```
ffffffff810f4510-ffffffff810f46af: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f2790)
Location: kernel/sched/fair.c:8176
Inline: False
Direct callers:
  - kernel/sched/topology.c:init_sched_groups_capacity
```
**Symbols:**

```
ffffffff810f2790-ffffffff810f28c6: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4a80)
Location: kernel/sched/fair.c:8288
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810f4a80-ffffffff810f4c6a: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110e490)
Location: kernel/sched/fair.c:8426
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8110e490-ffffffff8110e756: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112a200)
Location: kernel/sched/fair.c:8400
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8112a200-ffffffff8112a4e6: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81153cf0)
Location: kernel/sched/fair.c:8923
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff81153cf0-ffffffff81153e7f: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81163d10)
Location: kernel/sched/fair.c:9215
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff81163d10-ffffffff81164004: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81170a20)
Location: kernel/sched/fair.c:9537
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:init_sched_groups_capacity
```
**Symbols:**

```
ffffffff81170a20-ffffffff81170cd5: update_group_capacity (STB_GLOBAL)
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
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014a088)
Location: kernel/sched/fair.c:7786
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffff80001014a088-ffff80001014a27c: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0397cd8)
Location: kernel/sched/fair.c:7786
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
c0397cd8-c0397ec4: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019c150)
Location: kernel/sched/fair.c:7786
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
c00000000019c150-c00000000019c3c8: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f3c06)
Location: kernel/sched/fair.c:7786
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffe0000f3c06-ffffffe0000f3da4: update_group_capacity (STB_GLOBAL)
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
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e4000)
Location: kernel/sched/fair.c:7786
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810e4000-ffffffff810e41c2: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d31b0)
Location: kernel/sched/fair.c:7786
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810d31b0-ffffffff810d3372: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e03d0)
Location: kernel/sched/fair.c:7786
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810e03d0-ffffffff810e0592: update_group_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_group_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebf50)
Location: kernel/sched/fair.c:7786
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810ebf50-ffffffff810ec112: update_group_capacity (STB_GLOBAL)
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
