# Function: <code>cgroup_kn_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81115110)
Location: kernel/cgroup.c:1358
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_rmdir
```
**Symbols:**

```
ffffffff81115110-ffffffff81115184: cgroup_kn_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111c120)
Location: kernel/cgroup.c:1413
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rmdir
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup.c:cgroup_kn_lock_live
```
**Symbols:**

```
ffffffff8111c120-ffffffff8111c192: cgroup_kn_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81124460)
Location: kernel/cgroup.c:1418
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rmdir
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup.c:cgroup_kn_lock_live
```
**Symbols:**

```
ffffffff81124460-ffffffff811244d2: cgroup_kn_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811243f0)
Location: kernel/cgroup/cgroup.c:1310
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff811243f0-ffffffff81124462: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81130550)
Location: kernel/cgroup/cgroup.c:1481
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81130550-ffffffff811305c7: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113ec20)
Location: kernel/cgroup/cgroup.c:1484
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8113ec20-ffffffff8113ec97: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114a630)
Location: kernel/cgroup/cgroup.c:1522
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8114a630-ffffffff8114a6a7: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81155d50)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81155d50-ffffffff81155dc1: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811619b0)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff811619b0-ffffffff81161a21: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172f70)
Location: kernel/cgroup/cgroup.c:1553
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81172f70-ffffffff81172fe1: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116fc30)
Location: kernel/cgroup/cgroup.c:1550
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8116fc30-ffffffff8116fcad: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170860)
Location: kernel/cgroup/cgroup.c:1551
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81170860-ffffffff811708dd: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81196de0)
Location: kernel/cgroup/cgroup.c:1582
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81196de0-ffffffff81196e5d: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c6dc0)
Location: kernel/cgroup/cgroup.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff811c6dc0-ffffffff811c6e58: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81209980)
Location: kernel/cgroup/cgroup.c:1619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81209980-ffffffff81209a18: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121f0d0)
Location: kernel/cgroup/cgroup.c:1613
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8121f0d0-ffffffff8121f168: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81236d90)
Location: kernel/cgroup/cgroup.c:1608
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81236d90-ffffffff81236e28: cgroup_kn_unlock (STB_GLOBAL)
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
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d2c80)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffff8000101d2c80-ffff8000101d2d14: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0415ac4)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
c0415ac4-c0415b78: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023db80)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
c00000000023db80-c00000000023dcc0: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014c4e4)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffe00014c4e4-ffffffe00014c596: cgroup_kn_unlock (STB_GLOBAL)
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
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159fd0)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81159fd0-ffffffff8115a041: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d2c0)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8114d2c0-ffffffff8114d331: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157da0)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81157da0-ffffffff81157e11: cgroup_kn_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164df0)
Location: kernel/cgroup/cgroup.c:1563
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81164df0-ffffffff81164e73: cgroup_kn_unlock (STB_GLOBAL)
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
