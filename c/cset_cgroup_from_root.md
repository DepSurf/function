# Function: <code>cset_cgroup_from_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81113300)
Location: kernel/cgroup.c:1176
Inline: True
Direct callers:
  - kernel/cgroup.c:task_cgroup_path
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:proc_cgroup_show
```
**Symbols:**

```
ffffffff81113300-ffffffff8111334c: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111a9a0)
Location: kernel/cgroup.c:1250
Inline: True
Direct callers:
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/cgroup.c:task_cgroup_path
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff8111a9a0-ffffffff8111a9ec: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81122510)
Location: kernel/cgroup.c:1255
Inline: True
Direct callers:
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/cgroup.c:task_cgroup_path
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81122510-ffffffff8112255c: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81122580)
Location: kernel/cgroup/cgroup.c:1148
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_mount
```
**Symbols:**

```
ffffffff81122580-ffffffff811225df: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112df20)
Location: kernel/cgroup/cgroup.c:1317
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_mount
```
**Symbols:**

```
ffffffff8112df20-ffffffff8112df8c: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113c740)
Location: kernel/cgroup/cgroup.c:1320
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_mount
```
**Symbols:**

```
ffffffff8113c740-ffffffff8113c7ab: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81147e00)
Location: kernel/cgroup/cgroup.c:1355
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_mount
```
**Symbols:**

```
ffffffff81147e00-ffffffff81147e6b: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81153150)
Location: kernel/cgroup/cgroup.c:1396
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff81153150-ffffffff811531b3: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115eda0)
Location: kernel/cgroup/cgroup.c:1396
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8115eda0-ffffffff8115ee03: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811763cc)
Location: kernel/cgroup/cgroup.c:1387
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8116f140-ffffffff8116f1a3: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811730bc)
Location: kernel/cgroup/cgroup.c:1384
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8116bb70-ffffffff8116bbd3: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173cc9)
Location: kernel/cgroup/cgroup.c:1385
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8116c620-ffffffff8116c686: cset_cgroup_from_root (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff8119c127)
Location: kernel/cgroup/cgroup.c:1416
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
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
In kernel/cgroup/cgroup.c (ffffffff811cc403)
Location: kernel/cgroup/cgroup.c:1419
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
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
In kernel/cgroup/cgroup.c (ffffffff8120f953)
Location: kernel/cgroup/cgroup.c:1473
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
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
In kernel/cgroup/cgroup.c (ffffffff81225379)
Location: kernel/cgroup/cgroup.c:1467
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
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
In kernel/cgroup/cgroup.c (ffffffff8123cfad)
Location: kernel/cgroup/cgroup.c:1461
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
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
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101cf898)
Location: kernel/cgroup/cgroup.c:1396
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffff8000101cf898-ffff8000101cf934: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04132a4)
Location: kernel/cgroup/cgroup.c:1396
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
c04132a4-c0413324: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000238030)
Location: kernel/cgroup/cgroup.c:1396
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
c000000000238030-c0000000002380f4: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000149f8e)
Location: kernel/cgroup/cgroup.c:1396
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffe000149f8e-ffffffe000149ffe: cset_cgroup_from_root (STB_LOCAL)
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
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811573c0)
Location: kernel/cgroup/cgroup.c:1396
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff811573c0-ffffffff81157423: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114a6e0)
Location: kernel/cgroup/cgroup.c:1396
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff8114a6e0-ffffffff8114a743: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81155190)
Location: kernel/cgroup/cgroup.c:1396
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff81155190-ffffffff811551f3: cset_cgroup_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cgroup *cset_cgroup_from_root(struct css_set *cset, struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811626b0)
Location: kernel/cgroup/cgroup.c:1396
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
```
**Symbols:**

```
ffffffff811626b0-ffffffff81162713: cset_cgroup_from_root (STB_LOCAL)
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
