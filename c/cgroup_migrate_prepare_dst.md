# Function: <code>cgroup_migrate_prepare_dst</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup *dst_cgrp, struct list_head *preloaded_csets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81115b00)
Location: kernel/cgroup.c:2643
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81115b00-ffffffff81115d18: cgroup_migrate_prepare_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct list_head *preloaded_csets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111c860)
Location: kernel/cgroup.c:2707
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
```
**Symbols:**

```
ffffffff8111c860-ffffffff8111ca2b: cgroup_migrate_prepare_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct list_head *preloaded_csets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81124b90)
Location: kernel/cgroup.c:2712
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
```
**Symbols:**

```
ffffffff81124b90-ffffffff81124d5b: cgroup_migrate_prepare_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81124ac0)
Location: kernel/cgroup/cgroup.c:2281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81124ac0-ffffffff81124cee: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81130c00)
Location: kernel/cgroup/cgroup.c:2490
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81130c00-ffffffff81130e2e: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113f2d0)
Location: kernel/cgroup/cgroup.c:2508
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8113f2d0-ffffffff8113f4f9: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114acf0)
Location: kernel/cgroup/cgroup.c:2549
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8114acf0-ffffffff8114af19: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811564d0)
Location: kernel/cgroup/cgroup.c:2692
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811564d0-ffffffff811566f3: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81162130)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81162130-ffffffff81162353: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173590)
Location: kernel/cgroup/cgroup.c:2619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81173590-ffffffff811737b5: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170290)
Location: kernel/cgroup/cgroup.c:2615
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81170290-ffffffff811704b5: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170ec0)
Location: kernel/cgroup/cgroup.c:2628
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81170ec0-ffffffff811710e5: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811976f0)
Location: kernel/cgroup/cgroup.c:2683
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811976f0-ffffffff811979d0: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c76e0)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811c76e0-ffffffff811c79de: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120a600)
Location: kernel/cgroup/cgroup.c:2791
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8120a600-ffffffff8120a8fe: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121fbe0)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8121fbe0-ffffffff8121fede: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81237930)
Location: kernel/cgroup/cgroup.c:2769
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81237930-ffffffff81237c2e: cgroup_migrate_prepare_dst (STB_GLOBAL)
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d3518)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffff8000101d3518-ffff8000101d3824: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0416294)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c0416294-c04164a0: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023e790)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c00000000023e790-c00000000023ea5c: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014cd2c)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffe00014cd2c-ffffffe00014cf20: cgroup_migrate_prepare_dst (STB_GLOBAL)
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a750)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8115a750-ffffffff8115a973: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114da40)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8114da40-ffffffff8114dc63: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158520)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81158520-ffffffff81158743: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165570)
Location: kernel/cgroup/cgroup.c:2693
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81165570-ffffffff81165793: cgroup_migrate_prepare_dst (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct cgroup *dst_cgrp</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_cgrp, preloaded_csets</code> ➡️ <code>preloaded_csets</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_mgctx *mgctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_head *preloaded_csets</code>
</li>
</ul>
</details>
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
