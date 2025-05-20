# Function: <code>cgroup_migrate_add_src</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff81113660)
Location: kernel/cgroup.c:2604
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81113660-ffffffff8111373f: cgroup_migrate_add_src.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff81120c1f)
Location: kernel/cgroup.c:2660
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
```
**Symbols:**

```
ffffffff8111aa50-ffffffff8111ab84: cgroup_migrate_add_src.part.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff8112910f)
Location: kernel/cgroup.c:2665
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
```
**Symbols:**

```
ffffffff811225b0-ffffffff811226e4: cgroup_migrate_add_src.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81125f41)
Location: kernel/cgroup/cgroup.c:2234
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811226d0-ffffffff81122789: cgroup_migrate_add_src.part.26 (STB_LOCAL)
ffffffff81124aa0-ffffffff81124abb: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81132271)
Location: kernel/cgroup/cgroup.c:2443
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8112f0d0-ffffffff8112f18f: cgroup_migrate_add_src.part.28 (STB_LOCAL)
ffffffff81130be0-ffffffff81130bfb: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81140953)
Location: kernel/cgroup/cgroup.c:2461
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8113d360-ffffffff8113d41f: cgroup_migrate_add_src.part.31 (STB_LOCAL)
ffffffff8113f2b0-ffffffff8113f2ca: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c3d3)
Location: kernel/cgroup/cgroup.c:2502
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81148e40-ffffffff81148eff: cgroup_migrate_add_src.part.32 (STB_LOCAL)
ffffffff8114acd0-ffffffff8114acea: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157fc4)
Location: kernel/cgroup/cgroup.c:2645
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81154280-ffffffff8115434e: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffff8115b412-ffffffff8115b45e: cgroup_migrate_add_src.part.0.cold (STB_LOCAL)
ffffffff811564b0-ffffffff811564ca: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81163c44)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8115fec0-ffffffff8115ff7f: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffff81162110-ffffffff8116212a: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174d7b)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81171440-ffffffff81171541: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffff81173570-ffffffff8117358a: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171a3b)
Location: kernel/cgroup/cgroup.c:2568
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8116deb0-ffffffff8116dfb1: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffff81170270-ffffffff8117028a: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172679)
Location: kernel/cgroup/cgroup.c:2581
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8116eab0-ffffffff8116ebb1: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffff81170ea0-ffffffff81170eba: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811975aa)
Location: kernel/cgroup/cgroup.c:2636
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81cb2f0f-ffffffff81cb2f24: cgroup_migrate_add_src.cold (STB_LOCAL)
ffffffff81197570-ffffffff811976ee: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c7571)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81e63cf3-ffffffff81e63d08: cgroup_migrate_add_src.cold (STB_LOCAL)
ffffffff811c7540-ffffffff811c76dd: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120a481)
Location: kernel/cgroup/cgroup.c:2744
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8205c189-ffffffff8205c19e: cgroup_migrate_add_src.cold (STB_LOCAL)
ffffffff8120a450-ffffffff8120a5ed: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121fa61)
Location: kernel/cgroup/cgroup.c:2713
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff820da97f-ffffffff820da994: cgroup_migrate_add_src.cold (STB_LOCAL)
ffffffff8121fa30-ffffffff8121fbcd: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812377b1)
Location: kernel/cgroup/cgroup.c:2722
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff821b65fd-ffffffff821b6612: cgroup_migrate_add_src.cold (STB_LOCAL)
ffffffff81237780-ffffffff8123791d: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d5404)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffff8000101cfa68-ffff8000101cfb34: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffff8000101d34c8-ffff8000101d3514: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (c0417048)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c041340c-c0413518: cgroup_migrate_add_src.part.0 (STB_LOCAL)
c041626c-c0416294: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000240a14)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c000000000239ef0-c000000000239fd8: cgroup_migrate_add_src.part.0 (STB_LOCAL)
c00000000023e770-c00000000023e790: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014e71a)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffe00014a1ba-ffffffe00014a264: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffe00014ccec-ffffffe00014cd2c: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c264)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811584e0-ffffffff8115859f: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffff8115a730-ffffffff8115a74a: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f554)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8114b930-ffffffff8114b9ef: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffff8114da20-ffffffff8114da3a: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a034)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811562b0-ffffffff8115636f: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffff81158500-ffffffff8115851a: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cgroup_migrate_add_src(struct css_set *src_cset, struct cgroup *dst_cgrp, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811670a4)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81163910-ffffffff811639cf: cgroup_migrate_add_src.part.0 (STB_LOCAL)
ffffffff81165550-ffffffff8116556a: cgroup_migrate_add_src (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
