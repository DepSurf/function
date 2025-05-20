# Function: <code>cgroup_migrate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81116c80)
Location: kernel/cgroup.c:2716
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81116c80-ffffffff81116d51: cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111dfb0)
Location: kernel/cgroup.c:2771
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
```
**Symbols:**

```
ffffffff8111dfb0-ffffffff8111e08a: cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811262e0)
Location: kernel/cgroup.c:2776
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_attach_task
```
**Symbols:**

```
ffffffff811262e0-ffffffff811263ba: cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81125340)
Location: kernel/cgroup/cgroup.c:2351
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81125340-ffffffff811253be: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81131610)
Location: kernel/cgroup/cgroup.c:2560
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81131610-ffffffff8113168e: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113fd60)
Location: kernel/cgroup/cgroup.c:2578
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8113fd60-ffffffff8113fdd9: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114b780)
Location: kernel/cgroup/cgroup.c:2619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8114b780-ffffffff8114b7f9: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157060)
Location: kernel/cgroup/cgroup.c:2759
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81157060-ffffffff811570d9: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81162cd0)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81162cd0-ffffffff81162d49: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811742e0)
Location: kernel/cgroup/cgroup.c:2686
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811742e0-ffffffff81174359: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170fc0)
Location: kernel/cgroup/cgroup.c:2682
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81170fc0-ffffffff8117103e: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171c40)
Location: kernel/cgroup/cgroup.c:2695
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81171c40-ffffffff81171cbe: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81198610)
Location: kernel/cgroup/cgroup.c:2750
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81198610-ffffffff81198779: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c86f0)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811c86f0-ffffffff811c8865: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120b6f0)
Location: kernel/cgroup/cgroup.c:2858
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8120b6f0-ffffffff8120b85b: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81220cf0)
Location: kernel/cgroup/cgroup.c:2827
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81220cf0-ffffffff81220e5b: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81238a40)
Location: kernel/cgroup/cgroup.c:2836
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81238a40-ffffffff81238afb: cgroup_migrate (STB_GLOBAL)
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
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d4258)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffff8000101d4258-ffff8000101d4340: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0416eec)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c0416eec-c0416f84: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023f790)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c00000000023f790-c00000000023f890: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014d7f0)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffe00014d7f0-ffffffe00014d8a6: cgroup_migrate (STB_GLOBAL)
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
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b2f0)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8115b2f0-ffffffff8115b369: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114e5e0)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8114e5e0-ffffffff8114e653: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811590c0)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811590c0-ffffffff81159139: cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct *leader, bool threadgroup, struct cgroup_mgctx *mgctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166120)
Location: kernel/cgroup/cgroup.c:2760
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81166120-ffffffff8116619a: cgroup_migrate (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct cgroup_root *root</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cgroup *cgrp</code>
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
<code>struct cgroup_root *root</code>
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
