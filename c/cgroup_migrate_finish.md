# Function: <code>cgroup_migrate_finish</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct list_head *preloaded_csets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81115070)
Location: kernel/cgroup.c:2572
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81115070-ffffffff8111510b: cgroup_migrate_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct list_head *preloaded_csets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111b900)
Location: kernel/cgroup.c:2627
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
```
**Symbols:**

```
ffffffff8111b900-ffffffff8111b9af: cgroup_migrate_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct list_head *preloaded_csets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81123c50)
Location: kernel/cgroup.c:2632
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
```
**Symbols:**

```
ffffffff81123c50-ffffffff81123cff: cgroup_migrate_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81124950)
Location: kernel/cgroup/cgroup.c:2195
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81124950-ffffffff81124a99: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81130a90)
Location: kernel/cgroup/cgroup.c:2404
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81130a90-ffffffff81130bd9: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113f160)
Location: kernel/cgroup/cgroup.c:2422
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8113f160-ffffffff8113f2a9: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114ab80)
Location: kernel/cgroup/cgroup.c:2463
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8114ab80-ffffffff8114acc9: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156360)
Location: kernel/cgroup/cgroup.c:2606
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81156360-ffffffff811564ae: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161fc0)
Location: kernel/cgroup/cgroup.c:2607
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81161fc0-ffffffff8116210e: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173420)
Location: kernel/cgroup/cgroup.c:2533
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81173420-ffffffff8117356e: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170120)
Location: kernel/cgroup/cgroup.c:2529
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81170120-ffffffff8117026e: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170d50)
Location: kernel/cgroup/cgroup.c:2542
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81170d50-ffffffff81170e9e: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81197420)
Location: kernel/cgroup/cgroup.c:2597
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81197420-ffffffff8119756e: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c7400)
Location: kernel/cgroup/cgroup.c:2601
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811c7400-ffffffff811c753b: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120a300)
Location: kernel/cgroup/cgroup.c:2699
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8120a300-ffffffff8120a43b: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121f8e0)
Location: kernel/cgroup/cgroup.c:2668
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8121f8e0-ffffffff8121fa1b: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81237630)
Location: kernel/cgroup/cgroup.c:2677
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81237630-ffffffff8123776b: cgroup_migrate_finish (STB_GLOBAL)
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
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d3390)
Location: kernel/cgroup/cgroup.c:2607
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffff8000101d3390-ffff8000101d34c4: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0416124)
Location: kernel/cgroup/cgroup.c:2607
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c0416124-c041626c: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023e5c0)
Location: kernel/cgroup/cgroup.c:2607
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c00000000023e5c0-c00000000023e768: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014cbc0)
Location: kernel/cgroup/cgroup.c:2607
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffe00014cbc0-ffffffe00014ccec: cgroup_migrate_finish (STB_GLOBAL)
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
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a5e0)
Location: kernel/cgroup/cgroup.c:2607
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8115a5e0-ffffffff8115a72e: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d8d0)
Location: kernel/cgroup/cgroup.c:2607
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8114d8d0-ffffffff8114da18: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811583b0)
Location: kernel/cgroup/cgroup.c:2607
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811583b0-ffffffff811584fe: cgroup_migrate_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165400)
Location: kernel/cgroup/cgroup.c:2607
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81165400-ffffffff81165545: cgroup_migrate_finish (STB_GLOBAL)
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
