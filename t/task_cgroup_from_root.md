# Function: <code>task_cgroup_from_root</code>

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
In kernel/cgroup.c (ffffffff81113493)
Location: kernel/cgroup.c:1207
Inline: True
Inline callers:
  - kernel/cgroup.c:task_cgroup_path
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:proc_cgroup_show
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
In kernel/cgroup.c (ffffffff81120ff2)
Location: kernel/cgroup.c:1281
Inline: True
Inline callers:
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/cgroup.c:task_cgroup_path
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
In kernel/cgroup.c (ffffffff81129552)
Location: kernel/cgroup.c:1286
Inline: True
Inline callers:
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/cgroup.c:task_cgroup_path
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81128309)
Location: kernel/cgroup/cgroup.c:1179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff811243d0-ffffffff811243e7: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113493c)
Location: kernel/cgroup/cgroup.c:1350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81130530-ffffffff81130547: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114305c)
Location: kernel/cgroup/cgroup.c:1353
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8113ec00-ffffffff8113ec17: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114eb8c)
Location: kernel/cgroup/cgroup.c:1388
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8114a610-ffffffff8114a627: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a6f9)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81155d30-ffffffff81155d47: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811663a9)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81161990-ffffffff811619a7: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81177539)
Location: kernel/cgroup/cgroup.c:1420
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81172f50-ffffffff81172f67: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174219)
Location: kernel/cgroup/cgroup.c:1417
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8116fc10-ffffffff8116fc27: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174de9)
Location: kernel/cgroup/cgroup.c:1418
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81170840-ffffffff81170857: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119c11c)
Location: kernel/cgroup/cgroup.c:1449
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81196d70-ffffffff81196ddd: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cc3f8)
Location: kernel/cgroup/cgroup.c:1452
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff811c6d40-ffffffff811c6db9: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120f948)
Location: kernel/cgroup/cgroup.c:1486
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff812098f0-ffffffff81209969: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8122536e)
Location: kernel/cgroup/cgroup.c:1480
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8121f040-ffffffff8121f0b9: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123cfa2)
Location: kernel/cgroup/cgroup.c:1475
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:task_get_cgroup1
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81236ce0-ffffffff81236d74: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d80d8)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffff8000101d2c48-ffff8000101d2c7c: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041ad04)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
c0415aa4-c0415ac4: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000245024)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
c00000000023db60-c00000000023db78: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00015103a)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffe00014c4ac-ffffffe00014c4e4: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e9c9)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81159fb0-ffffffff81159fc7: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151c79)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8114d2a0-ffffffff8114d2b7: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c799)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81157d80-ffffffff81157d97: task_cgroup_from_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *task_cgroup_from_root(struct task_struct *task, struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811698b9)
Location: kernel/cgroup/cgroup.c:1429
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81164dd0-ffffffff81164de7: task_cgroup_from_root (STB_GLOBAL)
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
