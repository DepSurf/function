# Function: <code>pr_cont_kernfs_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128a4b0)
Location: fs/kernfs/dir.c:286
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
**Symbols:**

```
ffffffff8128a4b0-ffffffff8128a532: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b78e0)
Location: fs/kernfs/dir.c:285
Inline: False
Direct callers:
  - kernel/cgroup_pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
**Symbols:**

```
ffffffff812b78e0-ffffffff812b7962: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd070)
Location: fs/kernfs/dir.c:235
Inline: False
Direct callers:
  - kernel/cgroup_pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
**Symbols:**

```
ffffffff812cd070-ffffffff812cd0f2: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812da670)
Location: fs/kernfs/dir.c:245
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
**Symbols:**

```
ffffffff812da670-ffffffff812da6f2: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812feed0)
Location: fs/kernfs/dir.c:246
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
**Symbols:**

```
ffffffff812feed0-ffffffff812fef52: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:246
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
**Symbols:**

```
ffffffff8132d8f9-ffffffff8132d943: pr_cont_kernfs_path.cold.20 (STB_LOCAL)
ffffffff8132cba0-ffffffff8132cbe1: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:246
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffffffff81344cae-ffffffff81344cf8: pr_cont_kernfs_path.cold.18 (STB_LOCAL)
ffffffff81343ee0-ffffffff81343f21: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:245
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffffffff8136cf09-ffffffff8136cf54: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff8136c150-ffffffff8136c192: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffffffff8138508e-ffffffff813850d9: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff81384300-ffffffff81384342: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffffffff813cfc3f-ffffffff813cfc8a: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff813cede0-ffffffff813cee22: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - block/blk-iocost.c:transfer_surpluses
```
**Symbols:**

```
ffffffff81bec0e9-ffffffff81bec134: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff813e0a10-ffffffff813e0a52: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - block/blk-iocost.c:transfer_surpluses
```
**Symbols:**

```
ffffffff81bde147-ffffffff81bde192: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff813e7540-ffffffff813e7582: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - block/blk-iocost.c:transfer_surpluses
```
**Symbols:**

```
ffffffff81cc85ea-ffffffff81cc8635: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff81439250-ffffffff81439292: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:254
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - block/blk-iocost.c:transfer_surpluses
```
**Symbols:**

```
ffffffff81e7b325-ffffffff81e7b380: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff814b4260-ffffffff814b42c3: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b080)
Location: fs/kernfs/dir.c:261
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - block/blk-iocost.c:transfer_surpluses
```
**Symbols:**

```
ffffffff8154b080-ffffffff8154b135: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81582cd0)
Location: fs/kernfs/dir.c:258
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - block/blk-iocost.c:transfer_surpluses
```
**Symbols:**

```
ffffffff81582cd0-ffffffff81582d85: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bb900)
Location: fs/kernfs/dir.c:260
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - block/blk-iocost.c:transfer_surpluses
```
**Symbols:**

```
ffffffff815bb900-ffffffff815bb9b2: pr_cont_kernfs_path (STB_GLOBAL)
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
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010452d88)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffff800010452d88-ffff800010452e90: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0615ab8)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
c0615ab8-c0615b54: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056c080)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
c00000000056c080-c00000000056c158: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5680)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffffffe0002e5680-ffffffe0002e5722: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffffffff8137d66e-ffffffff8137d6b9: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff8137c8e0-ffffffff8137c922: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffffffff8136e124-ffffffff8136e16f: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff8136d3b0-ffffffff8136d3f2: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffffffff8137b13e-ffffffff8137b189: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff8137a3b0-ffffffff8137a3f2: pr_cont_kernfs_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pr_cont_kernfs_path(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:247
Inline: False
Direct callers:
  - kernel/cgroup/pids.c:pids_can_fork
  - mm/memcontrol.c:mem_cgroup_print_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
**Symbols:**

```
ffffffff8138ec31-ffffffff8138ec7c: pr_cont_kernfs_path.cold (STB_LOCAL)
ffffffff8138dea0-ffffffff8138dee2: pr_cont_kernfs_path (STB_GLOBAL)
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
